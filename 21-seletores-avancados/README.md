# Aula 21 - Seletores avançados
Além dos principais seletores vistos anteriormente, há outros seletores tão importantes quanto, na estilização de um documento html com css.

## nth-chiild
Seletor responsável para selecionar um filho específico de um elemento pai

No parênteses, pode ser usuado qualquer tipo de parâmetro, sendo até uma operção matemática como 2n, 2n - 1, etc.

```css
li:nth-child(2) {
    color: #f00;
}

li:nth-child(3n) {
    color: #00f;
}
```

## :first-child e :last-child
similares ao seletor nth-child(), pegando o primeiro e último do elemento selecionado.

```css
li:first-child {
    color: rgb(255, 174, 0);
}

li:last-child {
    color: rgb(255, 0, 179);
}
```

## :not
É um seletor que ocasiona em uma negação de um elemento selecionado (lembre das tabelas verdade!)

```css
li:not(:first-child) {
    color: rgb(0, 255, 255);
}
```

## seletores de estados
Situações em que elementos se encontram em uma página

### :hover
É acionado quando um mouse é passado encima de um elemento qualquer (botão, div qualquer, ect)

```css
li:hover {
    background-color: #999;
}
```

### :focus
Quando um elemento se encontra focado, como um input

```css
input:focus {
    background-color: #f00;
}
```

## Pseudo-elementos
Cada elemento de sua página, tem a possibilidade de ter 2 pseudo-elementos. Elementos estes que não estão no documento html, mas são visíveis no navegador pela estilização do css

### ::before
Um pseudo-elemento que será posto antes do elemento selecionado

```css
li::before {
    content: "(antes) ";
}
```

### ::after
Um pseudo-elemento que será posto depois do elemento selecionado

```css
li::after {
    content: " (depois)";
}
```

