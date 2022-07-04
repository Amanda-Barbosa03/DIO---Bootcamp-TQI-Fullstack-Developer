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
- Criação de regras de estilos para elementos ou para grupo de elementos. Regra CSS formada por seletores (elementos de html) ou um grupo de seletores.
    FORMA: Seletores {Declarações}
#### Exemplos:

SELETORES DE TIPO:

  > a, p, h1, h3 { color: blue; font-size: 14px ; }
  
  >Obs.: Mesma aparência para os elementos dos tipos declarados. 

SELETORES ID x Classe:  

- Utilizados para definir uma aparência diferente para cada elemento. Representa qualquer tipo de elemento. 

> No HTML 
>
> ID  -  `<header id="header"  class="header></header>`
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
> OBS.:O ID só pode ser utilizado uma vez na página. 


## Links úteis
[Download VS Code - Editor de código](https://code.visualstudio.com/download)
	
[Sobre Html](https://www.w3schools.com/html/html_intro.asp)

[Sobre CSS](https://www.w3schools.com/css/css_intro.asp)