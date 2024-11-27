# Aula 16 - Unidade de Medida
Além do píxel, utilizado como unidade me medida padrão na maior parte da estilização em css nos estudos do módulo, há outros tipos de unidades de medida essênciais e mais responsivos do que estes.

## px
Representa exatamente 1 píxel da tela de seu monitor

Legal utilizar em elementos com estilizações pequenas, como a largura de uma borda de um elemento qualquer

Ex.:
```css
.px {
    height: 10px;
}
```

## rem
Root element, sendo uma unidade que toma como base o tamanho raiz da fonte de um elemento

A exemplo dos textos, tendo eles 16px em seu valor padrão, se utilizar 3 rem, será equivalente a 48px.

Ex.:
```css
/* root element -> 16px * 3 = 48px */
.rem {
    height: 3rem;
}
```

## em
Diferente de *rem*, ele é baseado ao tamanho de fonte do elemento atual, e não o elemento raiz

Legal para trabalhar com elementos de tamanhos variáveis, como botões

```css
.em {
    font-size: 20px;
    padding: 1em;
}
```

## Porcentagem
Toma como base o valor do elemento pai, como suas alturas, larguras e etc.

```css
.prcnt-33 {
    height: 33%;
}

.prcnt-66 {
    height: 66%;
}

.prcnt-100 {
    height: 100%;
}
```

## vh
Viewport height, ou seja, cálcula o valor tomando como base a altura de visualização de um elemento na tela

Ou seja, se utilizar 100vh, ele irá ocupar toda a área de visualização vertical da tela

```css
/* viewport height */
.vh {
    height: 30vh;
}
```

## vw
Viewport width, sendo similar ao vh, porém relacionado a área de visualização horizontal da tela.

```css
/* viewport width */
.vw {
    width: 50vw;
}
```