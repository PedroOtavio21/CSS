# Aula 5 - Cores no CSS
No CSS, podemos trabalhar com cores em vários formatos diferentes

## Usando nomes de cores:
Ex.:
``` css 
p { color: red;}
```

**Não recomendado**, pois não há uma garantia na padronização das cores

Implementado pelo navegador

## Usando os códigos das cores:
Forma **recomendada**, pois especifica a cor exata a ser usada de forma precisa

### Códigos RGB:
Utiliza a função **rgb()** do CSS para processar uma cor a partir dos valores de vermelho (R), verde (G) e azul (B)

Os valores vão de 0 à 255

Ex.:
``` css
h1 { color: rgb(255, 0, 0);}
```

### Códigos hexadecimais:
Utiliza a numeração hexadecimal para especificar cores no formato RGB de forma abreviada

O formato usado é **#RRGGBB**, e os valores são convertidos de hexadecimal para decimal

*Obs*: números hexadecimais representam os valores decimais de 0 à 15, porém usando os algarismos de 0 à F

Ex.:
``` css
h1 { color: #ff0000;}
```

### Códigos HSL
Formato diferente, porém muito útil para manipulação de cores

Utiliza o esquema de tonalidade, saturação e brilho, ou *Hue, Saturation e Lightness*, para definir uma cor

Assim como no RGB, o CSS também possui uma função ***hsl()***

Ex.:
``` css
h1 { color: hsl(0, 100%, 50%);}
```

## Dica
Use ferramentas de seleção de cores, ou color picker!