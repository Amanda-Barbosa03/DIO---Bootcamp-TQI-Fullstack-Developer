# Anotação de aula
## Introdução ao Java Script
 - Linguagem de programação
 - Linguagem interpretada, rodada em tempo real, não necessita de compilação. O output é simultaneo a execução do código.  
 - Baseada em Protótipos: conjunto de funções e possibilidades em comum em várias estruturas de dados. 
 - Multiparadigma: pode ser utilizada para programação orientada ao objeto, Programação estruturada ou programação funcional.   
 - Comumente utilizada em aplicações web cliente-side (voltada para a experiência e interação do usuário). 
 - Segue o padrão ECMAScript: conjunto de normas que regem funcionalidades da linguagem.
- Criado em 1995, porém apenas em 1997 começou a seguir o padrão ECMAScript1.  
- 2015 ECMAScript6: declaração de classes, função loop, arrow functions, declaração de variáveis, concatenação de variaveis e strings. 
- Aplicações: We, Mobile, SmartWatches, Games, Internet of things, APIs.
- Server-side: back-side comunicação da lingagem JavaScript por meio de  Node.JS para comunicação com Softwares tipo Alexa.

#### Comentários:
- Linha: "//.....". Atalho do teclado: ctrl+/
- Trechos do código: "/* ... */" Atalho do teclado: 

#### Variavies e Constantes
São delarações utilizadas para execurar funções. As 
- Variáveis:  podem ser manipuladas posteriormente,  o valor atribuído a ela pode ser redeclarado. Elas são declaradas, por boas práticas do JavaScript, com letras minúsculas e com um nome que identifique sua utilização.
Ex. `var desconto = 2`

- Constantes: não se alterarm durante o desenvolvimento do código. Devem ser escritas em maíuscula.
Ex. `const preco = 50`

#### Funções
- Declarar uma função:  colocamos "function" o nome da função, um conjunto de parênteses, nos quais podemos colocar ou não parâmetros, abrimos chaves para incluir a forma que queremos o output. Para armazenarmos o valor para utilizá-lo em outra função, utilizamos o "return (operação)" e para mostrar o valor no console ou terminal usamos o "console.log (operação). 
EX. `function soma(a,b) {`
     `return a + b;` <!--console.log (a + b);-->
`}`

 ####  Console
 - Na página web: botão direito do mouse e opção inpecionar. Selecionar console, pode digitar as variáveis e testar as funções. Utilizado para debugar ou para apresentar a interface para o cliente.
 - No console do terminal por meio do Node.jS: utilizado para debugar, rodando a versão do servidor. 

 #### Estrutura de projeto
 - Arquitetura do projeto: forma que está organizada os arquivos que pertencem ao projeto. 
 - Pasta "assets": ferramentas para o desenvolvimento do projeto. Ex. Imagens, arquivos .css e .js. 
 - Para inserir o Css numa páguna HTML, pode adicionálo antes da tag title, abaixo das tags metas. 
 Modelo: `<link rel="stylesheet" href="assets/css/style.css"/>`
 - Para inserir o JavaScript numa página HTML: POde ser linkado no início do arquivo antes da tag "title", mas é recomendado em projetos grandes que ele seja inserido antes da tag de fechmento "html".
 Modelo: `<script src="assets/js/scripts.js"></script>`

### Links úteis
[Download Git](https://git-scm.com/downloads)

[Crie sua conta e seu repositório - GitHub](https://github.com/)
