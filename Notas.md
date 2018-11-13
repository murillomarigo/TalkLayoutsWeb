# Historia dos Layouts na Web e Grid CSS

- Apresentação os Marigos

## Pré historia e Tabelas

- 1996 lançamento do IE pela Microsoft, introdução de style sheets, mas era uma tecnica obscura
- Os web designers começaram a usar tabelas para criar layout complexos e multi colunas
- Visual + estética mais importante estrutura semântica
- Misturava semântica e apresentação
- Dezembro de 96 W3C apresentou o CSS
- Desktop apenas

## Tableless

- Evolução do css e cada vez mais navegadores atendendo essas especificações
- Responsivo - Mobile
- Uso do float para posicionamento
- media queries para layout responsivo
  
## Bootstrap e Grid Systems

- Surgimento de sistemas que dividem o layout geralmente em 12 colunas
- Não foi o bootstrap que criou, mas popularizou
- Na versão 3 usa float, na versão 4 usa flex
- Facilita layouts responsivos

## Flexbox

- Defini como os elementos filho de um container vão se organizar e ocupar seu espaço
- Mesmo sendo possível fazer fazer layout complexos com o flexbox, o ideal é usa-lo para organizar o conteúdo dentro de cada bloco do site
- Unidimensional

## Grid CSS

- Bidimensional
- Elimina necessidade de containers para agrupar blocos de conteúdo
- Curiosidade - Existe graças ao IE 10
  
### Conceitos

- display : grid | inline-grid
- grid track : grid-template-columns e grid-template-rows
- tamanho usando fr (fração)  
- grid-template-areas : Constrói o template do grid usando o nome das areas
  
        .item-a {
            grid-area: header;
        }
        .item-b {
            grid-area: main;
        }
        .item-c {
            grid-area: sidebar;
        }
        .item-d {
            grid-area: footer;
        }

        .container {
            grid-template-columns: 50px 50px 50px 50px;
            grid-template-rows: auto;
            grid-template-areas: 
                "header header header header"
                "main main ` sidebar"
                "footer footer footer footer";
        }

### Hands on

### Mas e browser antigos

- Mostre o layout mobile

## Referencias

- https://en.wikipedia.org/wiki/Web_design#1988–2001
- https://www.codigofonte.com.br/codigos/estrutura-de-uma-pagina-para-sites-em-tabelas
- https://tableless.com.br/introducao-sobre-media-queries/
- https://getbootstrap.com/docs/4.1/layout/grid/
- https://getbootstrap.com/docs/3.3/css/#grid
- https://960.gs
- https://css-tricks.com/snippets/css/a-guide-to-flexbox/
- https://www.youtube.com/watch?v=7kVeCqQCxlk
- https://caniuse.com/#feat=css-grid
- https://gridbyexample.com