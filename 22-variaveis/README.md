# Aula 21 - Variáveis
Silimar ao que acontece com uma linguagem de programação, no css podemos criar variáveis para armazenar valores a serem reutilizáveis ao decorrer do código css, no que diz respeito a estilização do documento html

Para fazer isso, necessário selecionar o elemento root, e então nomear suas principais variáveis.

```css
:root {
    --cor-principal: #3c59e7;
    --cor-claro: #cfc9c9;
    --cor-escuro: #232323;
    --preenchimento-pq: .25rem 1rem;
    --preenchimento-md: 2rem;
    --preenchimento-gd: 4rem;
}
```

E para utilizar os elementos salvos, utilizar a função var como valor das propriedades selecionadas quaisquer, que o código irá funcionar

```css
header {
    background-color: var(--cor-escuro);
    color: var(--cor-claro);
    padding: var(--preenchimento-pq);
}

section {
    background-color: var(--cor-claro);
    padding: var(--preenchimento-md);
}

div {
    --preenchimento-pq: 1rem;
    background-color: var(--cor-principal);
    color: var(--cor-claro);
    padding: var(--preenchimento-pq);
}

.red-box {
    --cor-principal: #f64348;
}
```