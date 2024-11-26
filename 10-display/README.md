# Aula 10 - Display
Umas das, ou senão a mais importante no que diz a estilização do documento html com css

Seu uso possibilita abrir novas portas para a estilização de um documento qualquer

O display possui os seguintes valores em sua propriedade:

## inline
Padrão de boa parte dos elementos presentes no documento html

Permite apenas uma estilização horizontal nos elementos, seguindo o fluxo do texto do elemento, ocupando uma largura 
mínima e não quebrando de linha quando utilizado

Exemplo de elemento com display inline:
- span

Ex.:
``` css
.inline {
    display: inline;
    margin-top: 100px;
    margin-bottom: 100px;
    margin-left: 20px;
    margin-right: 20px;
    padding-top: 100px;
    padding-bottom: 100px;
    padding-left: 20px;
    padding-right: 20px;
}
```

## block
O contrário do elemento inline, ocupando a largura total do elemento pai em que se encontra, além de permitir uma 
estilização vertical.

Exemplos de elementos com display block:
- h1
- p
- div

Ex.:
``` css
.block {
    display: block;
    margin-top: 10px;
    margin-bottom: 10px;
    margin-left: 20px;
    margin-right: 20px;
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 20px;
    padding-right: 20px;
}
```

## inline-block
Uma junção das características de display inline e block

Não quebra de linha quando utilizado, permitindo estilização vertical e horizontal

Ex.:
``` css
.inline-block {
    display: inline-block;
    margin-top: 10px;
    padding-top: 10px;
}
```