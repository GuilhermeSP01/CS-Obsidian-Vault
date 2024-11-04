# Definição
[[Função|Funções]] logarítmicas são o inverso das funções exponenciais. Em termos simples, se você tiver uma função exponencial $y = b^x$, a função logarítmica correspondente é $x = log_b(y)$. O logaritmo de um número é o expoente ao qual a base deve ser elevada para obter esse número.

A função logarítmica com base $b$ é definida como:
$$f(x) = log_b(x)$$
Onde $b$ é a base do logaritmo e $b > 0$ e $b \ne 1$.

## Domínio e contradomínio
O domínio de $f(x) = log_b(x)$ é $x > 0$.
O contradomínio é todos os números reais ($R$).

## [[Gráfico]]
O gráfico de uma função logarítmica é uma curva que cresce lentamente para a direita.
A curva passa pelo ponto $(1, 0)$ por que $log_b(1) = 0$ para qualquer base $b$.
Se $b > 1$, a função é crescente.
Se $0 < b < 1$, a função é decrescente.

$f(x) = log_2(x)$
```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = log2(x)
```
$f(x) = log_{0.5}(x)$
```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = log(x) / log(0.5)
```

## Propriedades importantes
$log_b(b) = 1$, porque $b^1 = b$.
$log_b(1) = 0$, porque $b^0 = 1$.
$log_b(b^x) = x$, para qualquer $x$.
$b^{log_b(x)} = x$, para qualquer $x$.

## [[Derivada]]
A derivada de uma função logarítmica $f(x) = log_b(x)$ é:
$$f'(x) = \frac{1}{x\ln(b)}$$
Onde $\ln(b)$ é o logaritmo natural da base $b$.