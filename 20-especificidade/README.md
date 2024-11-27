# Aula 20 - Especificidade
A especificidade determina a ordem de prioridade das regras CSS que se aplicam a elementos HTML

## Ordem de aplicação das regras:
Pelo formato de cascata do CSS os estilos são aplicados em uma ordem

Regras definidas têm a maior especificidade

Regras em arquivos externos são aplicadas por último e têm menor especificidade 

## Especificidade de seletores
Seletores universais têm baixa especificidade 

Seletores de tipo têm uma especificidade maior que os universais

Seletores de classe e atributo têm maior especificidade que os seletores de tipo

Seletores de id tem maior especificidade que os seletores de classe e atributo

## Combinação de seletores
Quando múltiplos seletores se aplicam a um elemento, suas especificidades se somam

A ordem dos seletores também importa em casos de empate na especificidade

### !important
O "!important" sobrepôe todas as outras regras de especificidade

Evite o uso excessivo de !important para não prejudicar a manutenção de código

## Resumo
Ordem em cascata:
- **Estilos inline**: Estilos definidos diretamente no elemento HTML, usando o atributo style.

- **IDs**: Seletores de IDs específicos, como #myElement.

- **Classes, Pseudo-classes e Atributos**: Seletores com classes (.myClass), pseudo-classes (:hover, :nth-child()) e seletores de atributos ([type="text"])

- **Elementos e Pseudo-elementos**: Seletores que se referem a elementos HTML (div, p) e pseudo-elementos (::before, ::after)

Pontuações de especificidade
- Estilos inline (1000 pontos)

- IDs (100 pontos)

- Classes, Pseudo-classes e Atributos (10 pontos)

- Elementos e Pseudo-elementos (1 ponto)