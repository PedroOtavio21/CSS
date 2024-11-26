# Aula 11 - Seletores básicos
O css permite que sejam selecionados elementos de maneira diferente do convencional, como selecionar elementos por 
suas tags.  

Geralmente utilizados para estilizar um documento específico, ou vários elementos, ou simplesmente todos os elementos de uma página!

## Seletor universal
Permite selecionar todos os elementos ao mesmo tempo

Geralmente utilizado para "zera" o estilo padrão do navegador, visto que ao iniciar a estilização do documento html, 
o documento já possui um estilo padrão

Ex.:
``` css
/* seletor universal */
* {
    margin: 0;
    padding: 0;
}
```

## Seletor de tag
O mesmo já utilizado até o momento, sendo utilizado o nome da tag na seleção

Ex.:
``` css
/* seletor de tag */
header, footer {
    background-color: #333;
    color: #fff;
    padding: 10px;
}
```

## Seletor de elementos aninhados
Utilizado para selecionar um elemento que esteja por dentro de uma determinada tag, não necessáriamente sendo um 
filho direto do elemento pai

Ex.:
``` css
/* seletor de elementos aninhados */
nav a {
    color: #27ae60;
}
```

## Seletor de elementos filhos
Parecido com o seletor de elementos aninhados, porém ele seleciona o elemento que será um filho direto do elemento pai

Ex.:
``` css
/* seletor de filhos */
nav > a {
    display: block;
    color: #f5a623;
    padding: 10px;
}
```

## Seletor de classes
Um dos seletores mais utilizados, tanto pela sua facilidade de selecionar vários elementos, estes já sendo definidos 
pelo documento html, além de ser um padrão em frameworks css

Você ususará na maioria das vezes para estilizar vários elementos da mesma maneira

Ex.:
``` css
/* seletor de classes */
.laranja {
    color: #f5a623;
}
.verde {
    color: #27ae60;
}
```

## Seletor de id´s
Outro também muito utilizado, como os seletores de classes, porém utilizado para estilizar um elemento específico, já 
estabelecido dentro do documento html

Ex.:
``` css
/* seletor de id */
#secao-principal {
    padding: 20px;
    text-align: center;
}
```

## Combinação de seletores
Como o nome já disse, possibilidade de em um único bloco de estilização, combinar vários seletores

``` css
/* combinação de seletores */
#secao-principal > * {
    margin-top: 10px;
}
```

## Seletor de sequência
Não muito comum de se utilizar, tendo como ideia principal estilizar um elemento que está logo em seguida do 
selecionado

```css
input {
    display: block;
    padding: 5px;
    margin: 5px;
}

/* seletor de sequência */
input + input {
    margin-top: 30px;
    margin-bottom: 30px;
}

h2 + p {
    padding: 30px;
}
```

## Seletor de propriedade/atributo
Este é bastante útil também, onde você seleciona um determinado elemento com sua propriedade escolhida

Ex.:
```css
/* seletores de propriedade */
input[name="email"] {
    background-color: #f5a623;
}

input[type="password"] {
    background-color: #27ae60;
}
```