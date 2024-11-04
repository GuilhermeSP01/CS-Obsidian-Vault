# Definição
A [[Função|função]] módulo, também conhecida como função valor absoluto, é uma função matemática que associa a cada número real seu valor absoluto. O valor absoluto de um número real $x$ é a distância de $x$ até a origem (zero) na reta numérica, sem levar em conta o sinal de $x$.

A função módulo é definida como:
$$
|x| = \begin{cases} 
	\ \ \ x & \text{se } x \ge 0 \\
	-x & \text{se } x \lt 0
	\end{cases}
$$

## Características
- **Sem Negativos**: O valor absoluto de um número é sempre não negativo. Ou seja, ${x} \ge 0$ para qualquer número real $x$.
- **Simetria**: Para qualquer número $x$, $|x| = |-x|$. Isso significa que o valor absoluto de um número positivo é igual ao valor absoluto de seu correspondente negativo.
- **Distância**: O valor absoluto representa a distância de um número à origem (zero) na reta numérica.

## [[Gráfico]]
O gráfico da função valor absoluto $f(x) = |x|$ tem a forma de um "V", com o vértice na origem $(0,\ 0)$. a função é crescente para $x \ge 0$ e decrescente para $x \lt 0$.

```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = x < 0 ? -x : x
```
