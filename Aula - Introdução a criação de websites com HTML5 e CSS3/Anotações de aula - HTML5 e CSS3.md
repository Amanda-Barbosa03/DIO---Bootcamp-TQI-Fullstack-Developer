# Anotação de aula
## Introdução a criação de websites com HTML5 e CSS3

### HTML5
 - HTML: HyperText Markup Language -Linguagem de marcação de hipertexto; 
 - Criação de Tim Berners-Lee em 1991 (HTML1); 2014 (HTML5)
 - Importate: utilizada para definir o significado e a estrutura do conteúdo da web
 - Elementos HTML: podemos agrupar tipos de conteúdo, alterar tamanho e forma de fontes e adicionar diferentes mídias ao nossa página na web.
 	- Formato: Abertura da tag (`<h1>`) // atributo (class= "titulo") // conteúdo (título) // fechamento da tag (`</h1>`)
		- Ex.: ```<h1 class= "título"> Título </h1>```

 ### Estrutura básica:
`<!DOCTYPE html>` --> declara o tipo do documento que estou editando. 

`<html>` --> tag raiz; engloba todos os elementos.

`<head>` --> contém os metadados que serão lidos pelo navegador. 

`<meta>` --> codificação de caractere. 
	
`<title></title>` --> declara o título na página e na barra do navegador. 
	
`</head>` --> fechamento da tag head.

`<body>` --> container que engloba todos os elementos visíveis/conteúdo da página.

`</body>` --> fechamento da tag body. 

`</html>` --> fechamento da tag html.

### Semântica:
Significado estabelecido pela ligação fornecida por uma tag entre o conteúdo e a estrutura do documento. 
`<div>` --> Divisão de conteúdo geral (container); 

`<section>` --> Divisão de conteúdo independente e de maior relevância dentro da página, separação de artigos;

`<header>` --> Logo; seções de cabeçalho; suporte introdutório e navegacional; 

`<article>` --> post;

`<aside>` --> barras laterias;

`<footer>` --> notas de rodapé;

### TAGS para textos:

`<h1>-<h6>` --> níveis de títulos;

   ##### **Exemplos:**

  >  ```<h1>Título 1 - Título da página</h1>``` <h1>Título 1 - Título da página</h1> 

  > ```<h2>Título 2 - Título da seção</h2> ``` <h2>Título 2 - Título da seção</h2>

  >  ```<h3>Título 3 - Título do artigo</h3>``` <h3>Título 3 - Título do artigo</h3>

  > ```<h4>Título 4</h1>``` <h4>Título 4</h4>

  > ```<h5>Título 5</h5>``` <h5>Título 5</h5>

  > ```<h6>Título 6</h6>``` <h6>Título 6</h6>

 `<p></p>` --> parágrafos.

### TAGs para links:

`<a>Link</a>` --> âncora; direciona para links.

`<a href="url">Nome da página</a>` --> atrituto para indicar o caminho do link. 

`<a target="_blank">Link</a>` --> atrituto para indicar o que o link deve ser aberto em uma nova guia.

  ##### **Exemplos:**

  >```<a href="https://github.com/Amanda-Barbosa03"target="_blank" >GitHub</a>```
  >
  ><a href="https://github.com/Amanda-Barbosa03" target="_blank">GitHub</a>

### TAGs para imagens:
`<img>` --> tag/elemento para inserir uma imagem.

`<img scr ="img/avatar.jpg">` --> recurso obrigatório para indicar o caminho da imagem

`<img alt ="descrição da foto">` --> recurso recomendado para melhorar a sensibilidade, mostra a descrição da imagem qaundo ela não é carregada ou para mostar para o usuário, por meio de leitor de tela, o que a imagem significa. 

### TAGs para listas (Agrupamento de coleção de itens):

`<ul>` --> "Unordered list" - tag/elemento para inserir uma lista em que a ordem dos elementos é irrelevante.
  #### Exemplos:
  Lista não ordenada:
  <ul> 
    <li>Aline</li>
    <li>Alessandra</li>
    <li>Amanda</li>
  </ul>

`<ol>` --> tag/elemento para inserir uma lista em que a ordem dos elementos importa.
  #### Exemplos:
  Lista ordenada (Alfabética):
  <ol> 
    <li>Alessandra</li>
    <li>Aline</li>
    <li>Amanda</li>
  </ol>

`<li>` --> representa um item da lista.

### CSS5
- 1996 - Crição da linguagem de estilo CSS para formatação de páginas web. 
- Sintaxe simples; 
- Criação de regras de estilos para elementos ou para grupo de elementos que podem ser formadas por seletores (elementos de html) ou um grupo de seletores. 

### Regras de estilo CSS
- FORMA: Seletores {Declarações (propriedade+valor) }
#### Exemplos:
  #### Seletores de tipo :

  > a, p, h1, h3 { color: blue; font-size: 14px ; }
  
  >Obs.: Mesma aparência para os elementos dos tipos declarados. 

  #### Seletores ID e Class : 

  - Utilizados para definir uma aparência diferente para cada elemento. Representa qualquer tipo de elemento. 

> No HTML 
>
> ID  -  `<header id="header" class="header></header>`
>
> CLASS - `<header class="header"></header>`

> No CSS 
>
> CLASS - .header {
>                  padding: 10px;
>                  }
>
> ID -     #header {
>                  padding: 10px;
>                  }
>
> OBS.: O ID só pode ser utilizado uma vez na página. 

### Representação dos elementos no navegador:

- Box model: Caixa retangular que representa cada elemento html, que pode ser alterada com o CSS.

>Margin: Espaçamento entre elementos
>
>Border: Delimitam o padding e o conteúdo. Podemos alterar lagura e cor.
> 
>Padding: Espaçamento entre borda e conteúdo.
>
>Content: Conteúdo que o box representa: imagem, vídeo ou texto.

### Estilização de elementos:

- Padding e Margin: espaçamentos. 

  - Eixo y, x: o primeiro valor se refere à parte superior e inferior e o segundo aos lados esquerdo e direito. Ex. `.class {padding: 10px 3px;}`

  - Valor para cada lado do box: referindo-se respectivamente ao topo, ao lado direiro, a parte inferior e ao lado esquerdo. Ex. `#id {padding: 15px 10px 5px 0;}`  

  - Propriedades específicas para cada lado: usado quando três lados são iguais e um é diferente. Ex. `.class {paddin-top: 15px;}`. 

- Backgorund: cor de fundo, colocar imagem de fundo e alterar posicionamento. 

  - Nome da cor em inglês: `.class {background-color: green;}`

  - Valor da cor em hexadecimal: `.class {background-color: #008800;}`

  - Atalho: `.class {background: #008000;}`

- Border: Bordas. Podem apresentar três valores: largura, cor e estilo.

  - Largura: Definida em pixel, em ou mm. (border-width)

  - Cor: nome me inglês ou código hexadecimal. (border-color)

  - Estilo: palavras chaves. (border-style)
      - solid: borda simples e reta; Ex.: `.class {border: 3px solid blue;}`
      - dotted: borda potilhada. Ex.: `.class {border-top: 2px dotted green;}`
      - dashed: borda tracejada. Ex.: `.class {border-right: 4px dashed pink;}`

  - Border-radius: arredonda cantos de um elemento com pixels ou porcentagens.

  ### Estilização de texto:

  - font-family:  alterar a fonte dos textos.Web safe fonts: presentes em diferentes computadores. Ex. Verdada, Arial.

  - font-size: mudar o tamanho do texto em pixels.

  - font-style: tonrar um texto italico usando o valor _italic_ ou remover o itálico com o valor _normal_.

  - font-weight: altera o peso do texto. Valor normal ou **bold**.

  - text-transform: alterar texto entre maiúsculas e minísculas. Valo r"uppercase" todas em maiúscula, valor "lowercase" todas em minúscula e valor "capitalize" apenas a primeira letra de cada palavra em maíscula. 

  - text-decoration: dar destaque em algum texto acrescentando linha. Valor "underline" coloca uma linha abaixo da palavra, o valor "overline" coloca uma linha a cima da palavra e o valor "line-through" coloca uma linha cortando a palavra. 

  ### Estilização de listas:
  - list-style-type: alterar marcadores das listas. 
 Valores: Square; upper-roman; "\1f44d"; nome.

  - list-style-image: adicionar uma imagem como marcador.
  Valor: url("rocket.png"); 

  ### Propriedades de dimensões e alinhamentos:
   - Widht e Heigt: ajustar largura e altura respectivamente.

   - Max-widht e max-height: limite máximo de largura e altura. 

   - Margin: valor alto que permite o alinhamento de um objeto automaticamente alem de espaçamento. Valor "auto" alinha horizontalemnte no centro.

   - text-align: alinhar texto com os valores "left", "right", "center" e "justify". 

## Links úteis
[Download VS Code - Editor de código](https://code.visualstudio.com/download)
	
[Sobre Html](https://www.w3schools.com/html/html_intro.asp)

[Sobre CSS](https://www.w3schools.com/css/css_intro.asp)