# Webpack Boilerplate

Este repositório contém um pequeno esqueleto de um projeto que utiliza webpack e babel para criar um bundle para uma página em HTML.

Adicionalmente, também há um simples *loader* de CSS, que injeta estilos na página via JavaScript.

## Principais Dependências

**Babel:** O Babel é o parser utilizado para transpilar os códigos de JavaScript para versões mais antigas, tornando-o possível ser entendido por navegadores mais antigos. Para sua integração com o webpack, utilizo o pacote *babel-loader*.

**Webpack:** Este é o nosso bundler, que cuida de transformar nosso código fonte em um único arquivo (possivelmente) minificado.