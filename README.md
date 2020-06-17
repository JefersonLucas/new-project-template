# Novo modelo de projeto

![GitHub](https://img.shields.io/github/license/JefersonLucas/new-project-template)
![GitHub contributors](https://img.shields.io/github/contributors/JefersonLucas/new-project-template)

> "Toda linha de código deve parecer que foi escrita por uma única pessoa, não importa a quantidade de contribuidores."
> #### _Provérbio Chinês_

Este é um documento vivo e novas ideias para melhorar esse repositório correspondente serão sempre bem vindas.

O documento a seguir descreve as regras de escrita nas linguagens de desenvolvimento em: **HTML**, **CSS** e **JavaScript**.

A ideia desse repositório não é ser um guia de projeto completo. Mas sim ter um local para que eu e outros desenvolvedores  consigam se organizar e assim terem projetos padronizados, com códigos mais limpos e bem legíveis.

## Contribuindo

Leia [CONTRIBUTING.md](https://github.com/JefersonLucas/new-project-template/blob/master/CONTRIBUTING.md) para obter detalhes sobre nosso código de conduta e o processo para enviar solicitações pull para nós.

## Traduções

* [Original](https://github.com/JefersonLucas/new-project-template)
* [English](https://github.com/JefersonLucas/new-project-template/tree/master/translations/eng)

## Sumário

- [Commit](#commit)
- [README](#readme)
- [HTML](#html)
- [CSS](#css)
- [JavaScript](#javascript)
- [Considerações finais](#considerações-finais)
- [Referências](#referências)
- [Licença](#licença)

## Commit
Para facilitar a contribuição de qualquer pessoa nos projetos, todas as mensagens de `commit`, `pull requests` ou discussões devem ser em **Inglês**.

> **Motivo**: hoje em dia o inglês é o idioma universal. Se você usa outro idioma, está excluindo potenciais colaboradores.

Antes de commitar ajustes no projeto, verifique se existe uma `issue` aberta e faça referência a ela usando `#` na sua mensagem de commit.

```javascript
// Bom
git commit -m "Add placeholder on input #10"

// Ruim
git commit -m "Add placeholder on input"
```

## README

A principal influência de template no README.md é o [@PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)

### Readme Sumário

- [Introdução](#introdução)
- [Títulos](#títulos)
- [Estilizar texto](#estilizar-texto)
- [Citar texto](#citar-texto)
- [Links](#links)
- [Listas](#listas)
- [Listas aninhadas](#listas-aninhadas)
- [Listas de tarefas](#listas-de-tarefas)
- [Parágrafos](#parágrafos)
- [Imagens](#imagens)
- [Códigos](#códigos)
- [Tabelas](#tabelas)
- [Emojis](#emojis)
- [Badges](#badges)

### Introdução

O [README.md](https://github.com/JefersonLucas/new-project-template#new-project-template) é uma linguagem de marcação markdown que vem com a extensão `.md`, assim como o HTML a sua função é a estilização e formatação como imagens, GIFs, links, listas, quotes, tasklists e código, etc. Quando se tem esse aquivo específico na sua página inicial, ele será apresentado primeiramente para guiar o usuário que está visitando a saber do que o seu projeto se trata. Veremos algumas sintaxes básicas em arquivos markdown:

### Títulos

Para criar um título, adicione de um a seis símbolos `#` antes do texto do título. O número de # que você usa determinará o tamanho do título.

**Sintaxe**:

```
# O título maior
## O segundo maior título
###### O título menor

```

**Resultado**:

# O título maior
## O segundo maior título
###### O título menor

### Estilizar texto
Você pode dar ênfase usando texto em negrito, itálico ou tachado.

Estilo | Sintaxe | Resultado |
------ | :-----: | --------- |
Negrito | ** ** ou __ __ | **Esse texto está em negrito** |
Itálico | * * ou _ _ | *Esse texto está em itálico* |
Tachado | * * ou _ _ | ~~Esse texto estava errado~~ |
Negrito e itálico aninhado | ** ** e _ _ | **Esse texto é _extremamente_ importante** |
Todo em negrito e itálico | *** ***  | ***Todo esse texto é importante*** |

### Citar texto
Você pode citar texto com um `>`.

**Sintaxe**:

```
Nas palavras de _Abraham Lincoln_:

> Pardon my French.
```

**Resultado**:

Nas palavras de _Abraham Lincoln_:

> Pardon my French.

### Links
Você pode criar um link inline colocando o texto do link entre colchetes `[ ]` e, em seguida, o URL entre parênteses `( )`.

**Sintaxe**:

Este site foi construído usando `[GitHub Pages](https://pages.github.com/)`.

**Resultado**:

Este site foi construído usando [GitHub Pages](https://pages.github.com/).

### Listas
Você pode criar uma lista não ordenada precedendo uma ou mais linhas de texto com `-` ou `*`.

**Sintaxe**:

```
- George Washington
- John Adams
- Thomas Jefferson
```

**Resultado**:

- George Washington
- John Adams
- Thomas Jefferson

Para listas ordenadas, utilize o número do item seguido de ponto `.`:

**Sintaxe**:

```
1. Item 1
2. Item 2
3. Item 3
```

**Resultado**:

1. Item 1
2. Item 2
3. Item 3

### Listas aninhadas

Você pode criar uma lista aninhada recuando um ou mais itens da lista abaixo de outro item. você pode alinhar sua lista visualmente. Digite caracteres de espaço na fonte do item da lista aninhada, até que o caractere de marcador da lista (`-` ou `*`) fique diretamente abaixo do primeiro caractere do texto no item acima dele.

**Sintaxe**:

```
1. First list item
   - First nested list item
     - Second nested list item
```

**Resultado**:

1. First list item
   - First nested list item
     - Second nested list item

### Listas de tarefas

Para criar uma lista de tarefas, anteceda os itens da lista com um caractere de espaço regular seguido por `[]`. Para marcar uma tarefa como concluída, use `[x]`.

**Sintaxe**:

```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```

**Resultado**:

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

### Parágrafos
Você pode criar um parágrafo deixando uma linha em branco entre as linhas de texto.

### Imagens
O código para inserir uma imagem no conteúdo é semelhante ao código de inserir links-âncora, adicionando um ponto de exclamação ! no início do código, como no exemplo abaixo:

**Sintaxe**:

Esta é uma linha com uma imagem personalizada `![GitHub](http://www.w3schools.com/html/smiley.gif)`.

**Resultado**:

Esta é uma linha com uma imagem personalizada ![GitHub](http://www.w3schools.com/html/smiley.gif).

Imagens grandes podem estar em linhas individuais, para serem exibidas em maior tamanho.

### Códigos

Há dois modos de adicionar trechos de código ao Markdown:
* **Código em linha** (_inline_): adicione um acento grave `ˋ` no início e no final do código.
* **Múltiplas linhas de código**: envolva as linhas de código com três acentos graves ` ˋˋˋ ` ou três tils `~~~`.

**Sintaxe**:

Esta é uma linha que contém um `código`.

**Resultado**:

```
Esta é uma linha de código
```
 
Para especificar que tipo de linguagem está sendo apresentada no bloco de códigos adicionando o nome da linguagem de programação após o ` ˋˋˋ ` ou `~~~`, por exemplo `~~~ javascript` ou `~~~ ruby`. Veja nos exemplos abaixo:

**Sintaxe**:

``` 
~~~javascript
Esta é uma linha de código em Javascript.
~~~

~~~php
Esta é uma linha de código em PHP.
~~~

~~~html
Esta é uma linha de código em HTML.
~~~
```

**Resultado**:

~~~javascript
Esta é uma linha de código em Javascript.
~~~

~~~php
Esta é uma linha de código em PHP.
~~~

~~~html
Esta é uma linha de código em HTML.
~~~

### Tabelas
Escolha os títulos das colunas e use `|` para delimitar as colunas. Depois, utilize hífen `-` na segunda linha para indicar que acima estão os títulos das colunas, usando novamente o `|` para delimitar colunas. Veja um exemplo abaixo:

**Sintaxe**:

```
Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8
```

**Resultado**:

Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8

Para especificar o tipo de alinhamento que deseja ter nas tabelas, utilize `:` ao lado do campo horizontal de hífens `---`, na segunda linha da sua tabela. Veja abaixo:

* **Alinhado a esquerda**: usar `:` no lado esquerdo (alinhamento padrão);
* **Alinhado a direita**: usar `:` no lado direito;
* **Centralizado**: usar `:` dos dois lados.

**Sintaxe**:

```
Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor
```

**Resultado**:

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor

### Emojis
Você pode adicionar emojis digitando `:EMOJICODE:`.

**Sintaxe**:

```
@octocat :+1: Este PR parece ótimo - está pronto para o merge! :shipit:
```

**Resultado**:

@octocat :+1: Este PR parece ótimo - está pronto para o merge! :shipit:

Para obter uma lista completa de emojis e códigos disponíveis, confira [emoji-cheat-sheet.com](https://www.webfx.com/tools/emoji-cheat-sheet/).

### Badges

O Shields.io é um site que você cria seus badges customizáveis que pode utilizá-lo para o seu projeto.

**Sintaxe**:

```
![GitHub](https://img.shields.io/github/license/JefersonLucas/new-project-template)
```

**Resultado**:

![GitHub](https://img.shields.io/github/license/JefersonLucas/new-project-template)

Para obter uma lista completa de badges disponíveis, confira o [Shields.io](https://shields.io/).

## HTML

A principal influencia das regras de HTML é o [coding style](https://github.com/felipefialho/coding-style).

### HTML Sumário
- [HTML Sintaxe](#html-sintaxe)
- [HTML Comentários](#html-comentários)
- [HTML Encoding de Caracteres](#html-encoding-de-caracteres)
- [HTML Ordem dos Atributos](#html-ordem-dos-atributos)
- [HTML Performance](#html-performance)
- [HTML Código Base](#html-código-base)

### HTML Sintaxe

Use soft-tabs com quatro espaços. Você pode configurar o seu editor dessa forma.

```html
<!-- Bom -->
<nav class="navbar">
    <ul class="nav">
        <li class="nav-item">
            <a class="nav-link">
              
<!-- Ruim-->
<nav class="navbar">
  <ul class="nav">
    <li class="nav-item">
      <a class="nav-link">
```

Sempre use aspas duplas.

```html
<!-- Bom -->
<main class="main">

<!-- Ruim -->
<main class='main'>
```

Não inclua `/` em elementos viúvos.

```html
<!-- Bom -->
<hr>

<!-- Ruim -->
<hr />
```

Separe os blocos usando uma linha vazia e agrupe os elementos internos do bloco.

```html
<!-- Bom -->
<ul class="nav-tabs">
  <li>...</li>
  <li>...</li>
  <li>...</li>
  <li>...</li>
</ul>

<div class="tab-content">
  ...
</div>

<!-- Ruim -->
<ul class="nav-tabs">

  <li>...</li>

  <li>...</li>

  <li>...</li>

  <li>...</li>

</ul>
<div class="tab-content">
  ...
</div>
```
### HTML Comentários

Siga esta regra para adicionar comentários no HTML.

```html
<!-- Este é um bom exemplo -->
<!-- /Fechando um bom exemplo -->
```
### HTML Encoding de Caracteres

Sempre use UTF-8 para encoding de caracteres.

```html
<head>
  <meta charset="UTF-8">
</head>
```
### HTML Ordem dos Atributos

Os atributos do HTML devem estar na seguinte ordem para facilitar a leitura.

1. `class`
1. `id`, `name`
1. `data-*`
1. `src`, `for`, `type`, `href`
1. `title`, `alt`
1. `aria-*`, `role`

```html
<a class="..." id="..." data-modal="#overlay" href="#">

<input class="form-control" type="text">

<img class="img-rounded" src="..." alt="...">
```

### HTML Performance

Nos includes dos arquivos CSS e JavaScript não é necessário especificar o tipo de arquivo como `text/css` e `text/JavaScript`.

```html
<!-- Bom -->
<link rel="stylesheet" href="assets/css/style.css">
<script src="scripts.min.js"></script>

<!-- Ruim -->
<script type="text/JavaScript" src="scripts.min.js"></script>
</head>
<body>
```

Para uma melhor performance, todos os arquivos JavaScripts devem estar antes de fechar o `</body>`, no fim do documento.

```html
<!-- Bom -->
<script src="scripts.min.js"></script>
</body>

<!-- Ruim -->
<script src="assets/js/scripts.min.js"></script>
</head>
<body>
```

### HTML Código Base

O código a seguir é uma base em HTML para iniciar rápidamente os projetos.

```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="utf-8">
    <meta name="format-detection" content="telephone=no">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <meta name="autor" content="Your Name">
    <link rel="shortcut icon" href="./assets/img/ico/favicon.ico">
    <link rel="logo" type="image/svg" href="./assets/img/logo/logo.svg">
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Nome do seu projeto</title>
</head>
<body>
    <h1>Seu modelo de projeto aqui</h1>
    <script src="./assets/js/scripts.js"></script>
</body>
</html>
```

Para fornecer suporte para versões antigas do Internet Explorer...

```html
<!DOCTYPE html>
<!--[if IE]><![endif]-->
<!--[if IE 7 ]> <html lang="en" class="ie7">    <![endif]-->
<!--[if IE 8 ]>    <html lang="en" class="ie8">    <![endif]-->
<!--[if IE 9 ]>    <html lang="en" class="ie9">    <![endif]-->
<!--[if (gt IE 9)|!(IE)]><!--><html lang="pt-br"><!--<![endif]-->
<head>
...
```

## CSS

As principais influências para as regras de CSS são o [Code Guide by @mdo](https://github.com/mdo/code-guide), [idiomatic CSS](https://github.com/necolas/idiomatic-css/) e o [coding style](https://github.com/felipefialho/coding-style).

### CSS Sumário

- [CSS Sintaxe](#css-sintaxe)
- [CSS Ordem de Declaração](#css-ordem-de-declaração)
- [CSS Nome das Classes](#css-nome-das-classes)
- [CSS Performance](#css-performance)
- [CSS Media Queries](#css-media-queries) 
- [CSS Comentários](#css-comentários)
- [CSS Código Base](#css-código-base)

### CSS sintaxe

Use soft-tabs com quatro espaços. Você pode configurar o seu editor dessa forma.

```css
/* Bom */
.nav-item {
    display: inline-block;
    margin: 0 5px;
}

/* Ruim */
.nav-item {
  display: inline-block;
  margin: 0 5px;
}
```

Sempre use aspas duplas.

```css
/* Bom */
[type="text"]
[class="..."]

.nav-item:after {
    content: "";
}

/* Ruim */
[type='text']
[class='...']

.nav-item:after {
    content: '';
}
```

Inclua um espaço antes de abrir o `}` da regra.

```css
/* Bom */
.header {
    ...
}

/* Ruim */
.header{
    ...
}
```

Inclua um espaço depois do `:` da declaração.

```css
/* Bom */
.header {
    margin-bottom: 20px;
}

/* Ruim */
.header{
    margin-bottom:20px;
}
```

Inclua um `;` no fim da declaração.

```css
/* Bom */
.header {
    margin-bottom: 20px;
}

/* Ruim */
.header{
    margin-bottom:20px
}
```

Mantenha uma declaração por linha.

```css
/* Bom */
.selector-1,
.selector-2,
.selector-3 {
  ...
}

/* Ruim */
.selector-1, .selector-2, .selector-3 {
    ...
}
```

Declarações únicas devem ficar em uma linha.

```css
/* Bom */
.selector-1 { width: 50%; }

/* Ruim */
.selector-1 {
    width: 50%;
}
```

Separe as regras por uma linha em branco.

```css
/* Bom */
.selector-1 {
  ...
}

.selector-2 {
  ...
}

/* Ruim */
.selector-1 {
  ...
}
.selector-2 {
  ...
}
```

Use caixa-baixa, valores hexadecimais reduzidos e não especifique unidades quando o valor é zero.

```css
/* Bom */
.selector-1 {
    color: #aaa;
    margin: 0;
}

/* Ruim */
.selector-1 {
    color: #AAAAAA;
    margin: 0px;
}
```

### CSS Ordem de Declaração

As declarações devem ser adicionadas em ordem alfabética.

```css
/* Bom */
.selector-1 {
    background: #fff;
    border: #333 solid 1px;
    color: #333;
    display: block;
    height: 200px;
    margin: 5px;
    padding: 5px;
    width: 200px;
}

/* Ruim */
.selector-1 {
    padding: 5px;
    height: 200px;
    background: #fff;
    margin: 5px;
    width: 200px;
    color: #333;
    border: #333 solid 1px;
    display: block;
}
```

### CSS Nome das Classes

Mantenha as classes em caixa-baixa e use hífen para separar os nomes.

```css
/* Bom */
.page-header { ... }

/* Ruim */
.pageHeader { ... }
.page_header { ... }
```

Hífens e underlines servem como uma transição natural entre classes relacionadas. O primeiro nome deve ser baseado no parente imediato da classe que deseja criar.

```css
/* Bom */
.navbar { ... }
.nav { ... }
.nav__item { ... }
.nav__link { ... }

/* Ruim */
.item-nav { ... }
.link-nav { ... }
```

Use somente um hífem para separar os nomes de elementos.

```css
/* Bom */
.page-header-action { ... }
.page-header-action-title { ... }
.page-header-active { ... }

.btn { ... }
.btn-primary { ... }

/* Ruim */
.page-header__action { ... }
.page-header__action__title { ... }
.page-header--active { ... }

.btn { ... }
.btn--primary { ... }
```

Evite usar nomes muito curtos e sempre use nomes relacionados com a função da classe.

```css
/* Bom */
.btn { ... }
.page-header { ... }
.progress-bar { ... }

/* Ruim */
.s { ... }
.ph { ... }
.block { ... }
```
### CSS Performance

Nunca use IDs.

```css
/* Bom */
.header { ... }
.section { ... }

/* Ruim */
#header { ... }
#section { ... }
```

Não use seletores padrões para regras genéricas. Sempre use classes.

```css
/* Bom */
.form-control { ... }
.header { ... }
.section { ... }

/* Ruim */
input[type="text"] { ... }
header
section
```

Evite elementos aninhados. A preferência é sempre para o uso de classes.

```css
/* Bom */
.navbar { ... }
.nav { ... }
.nav-item { ... }
.nav-link { ... }

/* Ruim */
.navbar ul { ... }
.navbar ul li { ... }
.navbar ul li a { ... }
```

Aninhe somente quando precisar alterar o comportamento de uma classe por interferência de outra. Mantenha um limite de três elementos aninhados.

```css
/* Bom */
.modal-footer .btn { ... }
.progress.active .progress-bar { ... }

/* Ruim */
.modal-btn { ... }
.progress.active .progress-bar .progress-item span { ... }
```

Sempre minifique o código CSS. Automatizadores de tarefas como o [Grunt](http://gruntjs.com/) tornam isso muito mais fácil.

```css
<!-- Bom -->
.navbar { ... }.nav { ... }.nav-item { ... }.nav-link { ... }

<!-- Ruim -->
.nav-item {
    ...
}
.nav-link {
    ...
}
```
### CSS Media Queries

Comece o desenvolvimento usando regras genéricas e adiciona media queries começando com mobile. Leia esse artigo com mais informações, [CSS Modular com Mobile First](http://www.felipefialho.com/blog/2014/css-modular-com-mobile-first/).

```css
/* Bom */
.navbar {
    margin-bottom: 20px;
}

@media (min-width: 480px) {
    .navbar {
        padding: 10px;
    }
}

@media (min-width: 768px) {
    .navbar {
        position: absolute;
        top: 0;
        left: 0;
    }
}

@media (min-width: 992px) {
    .navbar {
        position: fixed;
    }
}

/* Ruim */
.navbar {
    position: fixed;
    top: 0;
    left: 0;
}

@media (max-width: 767px) {
    .navbar {
        position: static;
        padding: 10px;
    }
}

```

Mantenha os media queries o mais próximo possível da regra que deseja alterar. Não coloque em documentos separados ou no fim do stylesheet.

```css
.navbar { ... }
.nav { ... }
.nav-item { ... }

@media (min-width: 480px) {
    .navbar { ... }
    .nav { ... }
    .nav-item { ... }
}
```
### CSS Comentários

Todos os comentários devem ser feitos usando a sintaxe do pré-processador em uso.

```js
//
// Seção
// ==================================================

//
// Sub-seção
// --------------------------------------------------

// Separador 
// --------------------------------------------------

//
// Bloco de comentário
//
//

// Comentário simples
```
### CSS Código Base

Um pequeno hacking para começar com fazer algum projeto centralizado.

```css
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
body {
  align-items: center;
  background-color: #FFF;
  display: flex;
  height: 100vh;
  justify-content: center;
  width: 100%;
}
```

## JavaScript

As principais influências para as regras de JavaScript são o [Code Guide by @mdo](https://github.com/mdo/code-guide), [idiomatic CSS](https://github.com/necolas/idiomatic-css/) e o [coding style](https://github.com/felipefialho/coding-style).

- [JavaScript Sintaxe](#javascript-sintaxe)
- [JavaScript Variáveis](#javascript-variáveis)
- [JavaScript Performance](#javascript-performance)
- [JavaScript e HTML5 Data Attributes](#javascript-e-html5-data-attributes)
- [JavaScript Comentários](#javascript-comentários)

### JavaScript Sintaxe

Use soft-tabs com quatro espaços. Você pode configurar o seu editor dessa forma.

```js
// Bom
while (condition) {
    statements
}

// Ruim
while (condition) {
  statements
}
```

Sempre use `;`.

```js
// Bom
var me = $(this);
test();

// Ruim
var me = $(this)
test()
```

Sempre use aspas duplas.

```js
// Bom
var string = "<p class="foo">Lorem Ipsum</p>";
var noteClick = me.attr("data-note");

// Ruim
var string = '<p class="foo">Lorem Ipsum</p>';
var noteClick = me.attr('data-note');
```

Mantenha o `else` na mesma linha que fechar o `if`.

```js
// Bom
if ( true ) {
  ...
} else {
  ...
}

// Ruim
if ( true ) {
  ...
}
else {
  ...
}
```

Adicione espaços entre os operadores.

```js
// Bom
for (i = 0; i < 10; i++) {
  ...
}

// Ruim
for (i=0;i<10;i++) {
  ...
}
```

Nunca adicione espaço entre a chave de função e o nome da função.

```js
// Bom
foo(function() {
  ...
});

// Ruim
foo ( function () {
  ...
});
```

Adicione espaços fora dos `()`, mas nunca dentro deles.

```js
// Bom
if (condition) {
    statement
}

// Ruim
if( condition ){
    statement
}
```

Para condicionais, sempre use `{}`.

```js
// Bom
if (condition) {
    statement
} else if (condition) {
    statement
} else {
    statement
}

// Ruim
if (condition) statement;
else if (condition) statement;
else statement;
```

Para checar igualdade, use `===` ao invés de usar `==`.

```js
// Bom
if (foo === 'foo') {
    statement
}

// Ruim
if (foo == 'foo') {
    statement
}
```

### JavaScript Variáveis

Todas as variáveis devem ser declaradas antes de usar.

```js
// Bom
var me = $(this);
var noteClick = me.attr('data-note');
notes[noteClick].play();

// Ruim
notes[noteClick].play();
var me = $(this);
var noteClick = me.attr('data-note');
```

Sempre use `var` para declarar uma variável.

```js
// Bom
var me = $(this);

// Ruim
me = $(this);
```

### JavaScript Performance

Use o [JSHint](http://www.jshint.com/) para detectar erros e potenciais problemas.

Sempre concatene e minifique o código JavaScript. Automatizadores de tarefas como o [Grunt](http://gruntjs.com/) tornam isso muito mais fácil.

### JavaScript e HTML5 Data Attributes

Evite usar classes para iniciar interações em JavaScript. Prefira usar ***HTML5 Data Attributes***.

```js
// Bom
$('[data-component="tab"]');

// Ruim
$('.tab');
```
### JavaScript Comentários

Uma única linha acima do código que é comentado.

```js
// Bom
// Bom exemplo de comentário
var me = $(this);

// Ruim
var me = $(this); // Exemplo ruim de comentário
```
## Considerações finais

Como este é um novo documento, algumas regras podem não ter sido aplicadas em meus projetos antigos. Este é um documento vivo e mudanças podem acontecer a qualquer momento. Fique a vontade para contribuir fazendo fork, clone, branch, commit, push, pull request.

## Referências

* [guia basico de markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)
* [basic writing and formatting syntax](https://help.github.com/pt/github/writing-on-github/basic-writing-and-formatting-syntax)
* [como fazer um readme.md bonitão](https://medium.com/@raullesteves/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8)
* [Code Guide by @mdo](https://github.com/mdo/code-guide)
* [idiomatic CSS](https://github.com/necolas/idiomatic-css/)
* [idiomatic.js](https://github.com/rwldrn/idiomatic.js/)
* [Zeno Rocha Coding Style](https://github.com/zenorocha/my-coding-style/)
* [Airbnb JavaScript Style Guide](https://github.com/airbnb/JavaScript)

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE.md](https://github.com/JefersonLucas/new-project-template/blob/master/LICENSE) para obter detalhes.
