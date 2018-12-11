# Vindi Style Guides

Um guia de estilo é um tipo de manual que determina regras e convenções para escrita de código em determinada linguagem de programação, dentro de uma organização, projeto ou comunidade.

É comum encontrar diversas formas de escrever código que gera o mesmo resultado lógico, porém utilizamos guias de estilo para padronizar a forma de escrita e reduzir o esforço de compreensão.

Na Vindi, utilizamos guias de estilo que devem ser aplicados tanto nos projetos internos quanto nos de projetos de código aberto.

## Ferramentas de análise de código

Quando possível, é preferível declarar estas regras utilizando sintaxe compatível com ferramentas de análise de código (também conhecidas como _linters_). Dessa forma podemos utilizar ferramentas que verificam estas regras automaticamente, eliminando discussões desnecessárias no momento em que alterações de código forem submetidas via pull request.

A ferramenta de análise estática oficial da Vindi é o [Ebert](https://ebertapp.io), que deve ser configurada em todos os projetos da empresa.
Os arquivos de configuração dos linters devem ser mantidos na raiz deste repositório para serem lidos através da configuração `styleguide: vindi/style-guides` no `.ebert.yml` de cada projeto.

## Linguagens

- [Ruby](ruby/index.md)
