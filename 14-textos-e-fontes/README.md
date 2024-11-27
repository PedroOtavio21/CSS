# Aula 14 - Textos e Fontes
Nesta aula em específico, será trabalhada a utilização de textos e fontes utilizando o css, desde seus formatos e tamanhos

Segue abaixo as principais propriedades relacionadas a estilização de textos no css

## text-align
Serve exclusivamente para alinhar textos no documento html, e não elementos em si.

Ex.:
```css
h1 { text-align: center; }
```

## text-decoration
É o próprio sublinhado existente nos textos, como utilizado geralmente nos links

Existem vários valores, porém geralmente são utilizados os valores none para remover de links ou os próprios sublinhados com line-throught, underline, etc.

Ex.:
``` css
h1 { text-decoration: underline;}
```

## text-transform
Propriedade responsável por trocar o formato do texto para capitalize, lower case, etc.

Ex.:
```css
h1{ text-transform: capitalize;}
```
## font-family
Uma das propriedades mais importantes na web, no que diz a estilização de textos com css, visto que na maioria das vez, a marca registrada de seu site se encontra na família de seu texto.

**Nota:** Sempre que utilizar uma fonte "principal" em seu projeto, necessário selecionar em conjunto uma font de fallback, pois nem sempre todos os navegadores terão sua fonte principal disponível para a leitura.

Ex.:
```css
p{ font-family: monospace;}
```

## font-weight
Responsável por definir o peso de sua fonte, sendo ela extremamente fina, ou então com um forte negrito (bold)

**Nota:** Cada fonte tem seu próprio estilo de negrito. Bom ficar de olho

Ex.:
```css
p{ font-weight: 700;}
```

## font-size
O próprio tamanho do texto. 

Ex.:
```css
h2{ font-size: 16px;}
```

## letter-spacing
Uma espécie de separação entre as letras do texto, onde geralmente é utilizado para melhorar a visualização do texto.

Ex.:
```css
h2{ letter-spacing: 10px;}
```

## negrito e itálico
Como visto antes no curso de html, não é muito usual utilizar as tags semânticas para deixar seu texto em itálico ou negrito.

Uma boa prática é utilizar classes para realizar essa alteração no estilo do texto.

Ex.:
```css
.bold { font-weight: 700}
.italic { font-style: italic}