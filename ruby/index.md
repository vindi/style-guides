# Ruby

## RuboCop

[RuboCop](http://rubocop.readthedocs.io/) é a ferramenta que utilizamos para analisar código Ruby. Todo projeto Ruby na Vindi deve conter o arquivo [`.rubocop.yml`](.rubocop.yml) em sua raiz, sempre atualizado conforme a última versão deste repositório.

Definições adicionais não suportadas pelo RuboCop devem ser incluídas neste arquivo que você está lendo.

## Sidekiq

[Sidekiq](https://github.com/mperham/sidekiq) é a biblioteca utilizada para execução de tarefas em background.

### Nomenclatura
Workers devem ser criados no caminho `app/workers/[entity]/[action].rb` utilizando o nome `Workers::[Entity]::[Action]`. Exemplo:

```ruby
# app/workers/customer/archive.rb
class Workers::Customer::Archive
end
```
