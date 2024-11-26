# Aula 9 - Box Model: margin e padding
Esse nome se orginica do model de caixa que cada elemento do documento html utiliza

Cada elemento é composto pelos seguintes componentes:
- conteúdo da caixa (texto, itens de lista, etc)
- preenchimento interno (padding)
- borda
- preenchimento externo (margin)

## margin e padding
Ambos sendo preenchimento a um elemento, sendo o primeiro externo à borda e o segundo interno à borda e entre o 
conteúdo interno da caixa

Podem ser utilizando separadamente a partir da região escolhida (top, right, bottom, left) ou em apenas uma linha, 
com os valores sendo utilizado em ordem horária.

Ex.:
``` css
.box {
	/* margem */
  margin-top: 30px;
  margin-right: 40px;
  margin-bottom: 30px;
  margin-left: 40px;

	/* preenchimento */
  padding-top: 10px;
  padding-right: 20px;
  padding-bottom: 10px;
  padding-left: 20px;
}
```