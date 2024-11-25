# Aula 2 - Oque é CSS e como utilizá-lo
Cascading Style Sheets, ou folhas de estilo em cascata. (Ou seja, se um estilo na linha de baixo estilizar o mesmo 
elemento da linha acima, ele terá ordem de prioridade na estilização!)

Linguagem usada para definir os estilos em um documento HTML

## Pode ser incluido no documento html de três modos:
- Com o atributo style. Ex.: 

``` html
<h1 style="color: red">Titulo Vermelho</h1>
```
- Com a tag style, por exemplo:

```html
<head>
    <style>
        h1 {color: red;}
    </style>
</head>
```
- Com a tag link apontando para um arquivo CSS, por exemplo:

```html
<link rel="stylesheet" href="style.css">
```
## Estrutura de um código CSS
Tomando como base o código exemplo

``` css
h1 { color: red; }
```
h1 é o **seletor**, ou seja, o termo que seleciona qual a parte do documento terá esse estilo

As chaves **{}** delimitam o **bloco de declarações**, ou seja, onde começam e terminam os estilos a serem aplicados 
no(s) elemento(s) selecionado(s)

As declarações **color: red;** define um estilo. Declarações são sempre compostas por duas partes, a **propriedade** 
e o **valor**, e finalizadas com *ponto e virgula*.