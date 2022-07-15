# HTML5

### Definição e estrutura básica

- Criado em 1991 por Tim Berners-Lee para melhorar a comunicação entre ele e seus colegas de trabalho 
- Se tornou a base da web
- Um elemento HTML é formado por:
  - tag de abertura e seus atributos
  - conteúdo 
  - uma tag de fechamento

- Estrutura básica de um arquivo HTML:
  - A primeira linha do documento deve ser o < !DOCTYPE html >
  - Indica para o navegador que ele está lidando com um arquivo do tipo HTML5

### Elementos

1. html
   - é a raiz do documento
   - todos os elementos devem estar dentro dela
2. head
   - elementos que serão lidos pelo navegador
3. bory
   - todo o conteúdo visível para o usuário

### Semântica

1. section
   - seção genérica de conteúdo 
2. header
   - cabeçalho da página ou de uma seção da página e normalmente contém logotipos, menus, campos de busca
3. article
   - em uma barra lateral ou um bloco de comentários
   - pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens
4. aside
   - seção com conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografia do autor e publicidade
5. footer
   - rodapé do conteúdo 
   - ex: informações do autor e *links* relacionados.
6. h1 - h6
   - marcam a importância dos títulos, sendo h1 mais importante e h6 menos importante
   - boa prática: usar apenas um h1 por página

### Textos e links

- p

  - representa um parágrafo

  - suporta texto, imagens, código, vídeos, etc

- a
  - âncora,
  - representa um hyperlink

- href 
  - representa o *hyperlink* para onde sua âncora aponta
  - pode apontar para um site, um e-mail e até mesmo um telefone
  - email precisa do prefixo mailto: 
  - telefone precisa do prefixo tel:

- target 
  - abre o link em outra aba do navegador, usando o valor _blank

### Imagens

- Representado por < img >
- Tem apenas 2 atributos próprios: o src e o alt
  - src é obrigatório e guarda o caminho para a imagem que você quer mostrar na página
  - alt não é obrigatório, mas é altamente recomendado por melhorar a acessibilidade. Mostra a descrição da imagem caso ela não carregue.

### Listas

- ul
  - cria uma lista não ordenada
  - a ordem dos elementos não é importante
  - representada com pontos, círculos ou quadrados

- ol
  - Cria lista ordenadas,
  - a ordem importa
  - representada com números, algarismos romanos ou letras.

- li 

  - item dentro de uma dessas listas

  - pode conter vários tipos de conteúdos, como parágrafos, imagens e até outras listas

    

Referência: Digital Innovation One - DIO, Bootcamp FullStack, Introdução a criação de websites com HTML e CSS3. Disponível em: <https://web.dio.me/course/introducao-criacao-de-websites-com-html5-e-css3/learning/6ca1d02e-480b-4eea-b0d0-c78135dff209> Acesso em: 10 jul 2022. 

 

