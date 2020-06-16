# Novo modelo de projeto

![GitHub](https://img.shields.io/github/license/JefersonLucas/new-project-template)

Este é um documento vivo e novas ideias para melhorar os códigos correspondentes são sempre bem vindas. Contribua: faça fork, clone, branch, commit, push, pull request.

## Índice

- [Traduções](#traduções)
- [Início](#início)
  - [Clonando o repositório](#clonando-o-repositório)
  - [Baixando o repositório](#baixando-o-repositório)
  - [Fazendo um fork](#fazendo-um-fork)
- [Readme](#readme)
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
- [Referências](#referências)
- [Licença](#licença)

## Traduções

* [ORIGINAL](https://github.com/JefersonLucas/new-project-template)
* [Portuguese - Brazil](https://github.com/JefersonLucas/new-project-template/tree/master/translations/pt-br)

## Início

Para iniciar, baixe uma cópia desse repositório na sua máquina local. Siga passo a passo as seguinte formas de obter esse modelo na sua máquina local.

### Clonando o repositório

Para clonar esse repositório na sua máquina local, utilize as linhas de comando:

```
#Clonar com SSH

mkdir new-project-template
cd new-project-template
git init
git clone git@github.com:JefersonLucas/new-project-template.git
```

```
#Clonar com HTTPS

mkdir new-project-template
cd new-project-template
git init
git clone https://github.com/JefersonLucas/new-project-template.git
```

### Baixando o repositório

Você também pode [baixar](https://github.com/JefersonLucas/new-project-template/archive/master.zip) esse repositório em formato zip.

### Fazendo um fork

Faça um fork e contribua com esse projeto.

## Readme

O README é uma linguagem de marcação markdown que vem com a extensão `.md`, assim como o HTML a sua função é a estilização e formatação como imagens, GIFs, links, listas, quotes, tasklists e código. Quando se tem esse aquivo específico na sua página inicial, ele será apresentado primeiramente para guiar o usuário que está visitando a saber do que o seu projeto se trata. Veremos algumas sintaxes básicas em arquivos markdown:

### Títulos

Para criar um título, adicione de um a seis símbolos `#` antes do texto do título. O número de # que você usa determinará o tamanho do título.

Sintaxe:

```
# O título maior
## O segundo maior título
###### O título menor

```
Resultado:

# O título maior
## O segundo maior título
###### O título menor

### Estilizar texto
Você pode dar ênfase usando texto em negrito, itálico ou tachado.

Estilo | Sintaxe | Resultado |
------ | ------- | --------- |
Negrito | ** ** ou __ __ | **Esse texto está em negrito** |
Itálico | * * ou _ _ | *Esse texto está em itálico* |
Tachado | * * ou _ _ | ~~Esse texto estava errado~~ |
Negrito e itálico aninhado | ** ** e _ _ | **Esse texto é _extremamente_ importante** |
Todo em negrito e itálico | *** ***	 | ***Todo esse texto é importante*** |

### Citar texto
Você pode citar texto com um `>`.

Sintaxe:

Nas palavras de Abraham Lincoln:

> Pardon my French.

### Links
Você pode criar um link inline colocando o texto do link entre colchetes `[ ]` e, em seguida, o URL entre parênteses `( )`.

Ex.: Este site foi construído usando `[GitHub Pages](https://pages.github.com/)`.

### Listas
Você pode criar uma lista não ordenada precedendo uma ou mais linhas de texto com `-` ou `*`.

Sintaxe:

```
- George Washington
- John Adams
- Thomas Jefferson
```

Resultado:

- George Washington
- John Adams
- Thomas Jefferson

Para listas ordenadas, utilize o número do item seguido de ponto `.`:

Sintaxe:

```
1. Item 1
2. Item 2
3. Item 3
```

Resultado:

1. Item 1
2. Item 2
3. Item 3

### Listas aninhadas

Você pode criar uma lista aninhada recuando um ou mais itens da lista abaixo de outro item. você pode alinhar sua lista visualmente. Digite caracteres de espaço na fonte do item da lista aninhada, até que o caractere de marcador da lista (`-` ou `*`) fique diretamente abaixo do primeiro caractere do texto no item acima dele.

Sintaxe:

```
1. First list item
   - First nested list item
     - Second nested list item
```

Resultado:

1. First list item
   - First nested list item
     - Second nested list item

### Listas de tarefas

Para criar uma lista de tarefas, anteceda os itens da lista com um caractere de espaço regular seguido por `[]`. Para marcar uma tarefa como concluída, use `[x]`.

Sintaxe:

```
- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request
```

Resultado:

- [x] Finish my changes
- [ ] Push my commits to GitHub
- [ ] Open a pull request

### Parágrafos
Você pode criar um parágrafo deixando uma linha em branco entre as linhas de texto.

### Imagens
O código para inserir uma imagem no conteúdo é semelhante ao código de inserir links-âncora, adicionando um ponto de exclamação ! no início do código, como no exemplo abaixo:

Sintaxe:

```
![Alt ou título da imagem](URL da imagem)
```

Esta é uma linha com uma imagem personalizada ![GitHub](http://www.w3schools.com/html/smiley.gif).

Imagens grandes podem estar em linhas individuais, para serem exibidas em maior tamanho.

### Códigos

Há dois modos de adicionar trechos de código ao Markdown:
* **Código em linha** (_inline_): adicione um acento grave `ˋ` no início e no final do código.
* **Múltiplas linhas de código**: envolva as linhas de código com três acentos graves ` ˋˋˋ ` ou três tils `~~~`.

Esta é uma linha que contém um `código`.

```
Esta é uma linha de código
```
 
Para especificar que tipo de linguagem está sendo apresentada no bloco de códigos adicionando o nome da linguagem de programação após o ` ˋˋˋ ` ou `~~~`, por exemplo `~~~ javascript` ou `~~~ ruby`. Veja nos exemplos abaixo:

Sintaxe:

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

Resultado:

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

Sintaxe:

```
Exemplo   | Valor do exemplo
--------- | ------
Exemplo 1 | R$ 10
Exemplo 2 | R$ 8
Exemplo 3 | R$ 7
Exemplo 4 | R$ 8
```

Resultado:

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

Sintaxe:

```
Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor
```

Resultado:

Alinhado a esquerda | Centralizado | Alinhado a direita
:--------- | :------: | -------:
Valor | Valor | Valor

### Emojis
Você pode adicionar emojis digitando `:EMOJICODE:`.

Sintaxe:

```
@octocat :+1: Este PR parece ótimo - está pronto para o merge! :shipit:
```
Resultado:

@octocat :+1: Este PR parece ótimo - está pronto para o merge! :shipit:

Para obter uma lista completa de emojis e códigos disponíveis, confira [emoji-cheat-sheet.com](https://www.webfx.com/tools/emoji-cheat-sheet/).

### Badges

O Shields.io é um site que você cria seus badges customizáveis que pode utilizá-lo para o seu projeto.

Sintaxe:

```
![GitHub](https://img.shields.io/github/license/JefersonLucas/new-project-template)
```

Resultado:

![GitHub](https://img.shields.io/github/license/JefersonLucas/new-project-template)

Para obter uma lista completa de badges disponíveis, confira o [Shields.io](https://shields.io/).

## Referências

* [guia-basico-de-markdown](https://docs.pipz.com/central-de-ajuda/learning-center/guia-basico-de-markdown#open)
* [basic-writing-and-formatting-syntax](https://help.github.com/pt/github/writing-on-github/basic-writing-and-formatting-syntax)
* [@raullesteve](https://medium.com/@raullesteves/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8)
* [uma-imagem-como-um-link](https://sites.google.com/site/sitesrecord/o-que-e-html/uma-imagem-como-um-link)

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE.md](https://github.com/JefersonLucas/new-project-template/blob/master/LICENSE) para obter detalhes.
