# Definição
[[Função|Funções]] exponenciais são funções matemáticas em que a variável independente aparece no expoente. A forma geral de uma função exponencial é:
$$f(x) = a.b^x$$
Onde:
- $a$ é uma constante que representa o valor inicial (interseção com o eixo $y$ quando $x = 0$);
- $b$ é a base da exponencial e deve ser um número positivo diferente de 1;
- $x$ é a variável independente.

## Crescimento e Decaimento
Se $b > 1$, a função é crescente e representa um crescimento exponencial.
Se $0 < b < 1$, a função é decrescente e representa um decaimento exponencial.

## Taxa de Crescimento
Em funções exponenciais crescentes, a taxa de crescimento aumenta à medida que $x$ aumenta.
Em funções exponenciais decrescentes, a taxa de decaimento diminui à medida que $x$ aumenta.

## [[Gráfico]]
O gráfico de uma função exponencial é uma curva que aumenta ou diminui rapidamente.
A curva nunca cruza o eixo $x$; em vez disso, se aproxima dele assintoticamente.

$f(x) = 2.3^x$
```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = 2.3^x
```
$f(x) = 5.(0.5)^x$
```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = 5.(0.5)^x
```
## [[Derivada]]
A derivada de uma função exponencial $f(x) = a.b^x$ depende da base $b$. Se $f(x) = e^x$ (onde $e$ é a base dos logaritmos naturais, aproximadamente igual a 2,718), a derivada é:
$$f'(x) = e^x$$
Se a base for um valor qualquer, a derivada de $f(x) = a.b^x$ é:
$$f'(x) = a.b^x.ln(b)$$
