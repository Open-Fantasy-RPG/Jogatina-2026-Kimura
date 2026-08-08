# 5e.tools — referência externa

O projeto 5e.tools é usado como referência técnica externa para consulta de regras e estrutura de dados.

## Repositório upstream

- Projeto: `5etools-mirror-3/5etools-src`
- Site: `https://5e.tools/`

O README do projeto declara licença MIT para o software. Porém, o próprio guia de contribuição informa que o repositório contém dados oficiais publicados pela Wizards of the Coast e busca manter cópias 1:1 desses dados.

Por isso, este repositório **não espelha o corpus completo de livros comerciais** do 5e.tools.

## O que pode entrar aqui

- referências de estrutura e nomenclatura;
- código próprio de integração;
- índices e metadados;
- conteúdo do SRD / Creative Commons que tenha licença compatível;
- regras resumidas para uso na campanha;
- material autoral da campanha.

## O que não deve ser versionado aqui

- cópias integrais de livros oficiais não redistribuíveis;
- bancos completos de magias, monstros, classes ou itens provenientes de livros comerciais quando o texto não estiver coberto por licença de redistribuição;
- imagens, mapas ou artes oficiais sem licença apropriada.

## Objetivo futuro

Podemos construir um compêndio pesquisável dentro de `compendium/srd/` e adicionar índices por:

- classes;
- espécies;
- magias;
- condições;
- talentos;
- equipamentos;
- monstros SRD;
- regras gerais.

As fichas dos personagens podem então apontar diretamente para essas referências locais.
