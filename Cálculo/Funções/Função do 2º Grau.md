# Definição
[[Função|Funções]] de 2º grau, também conhecidas como funções quadráticas, são aquelas cujo maior expoente da variável é 2. A forma geral de uma função do 2º grau é:
$$f(x) = ax^2 + bx + c$$
Onde:
- $a$, $b$ e $c$ são constantes com $a ≠ 0$
- $x$ é a variável independente.

## [[Gráfico]]
O gráfico de uma função do 2º grau é uma parábola. A orientação da parábola (se abre para cima ou para baixo) depende do sinal do coeficiente $a$:
	Se $a > 0$, a parábola se abre para cima.
	Se $a < 0$, a parábola se abre para baixo.

Dada a função $f(x) = 2x^2 -4x + 1$, o gráfico que a representa é:

```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = 2x^2 - 4x + 1
```


## Vértice
O ponto de mínimo ou máximo da parábola, dependendo da orientação. A coordenada $x$ do vértice pode ser encontrada usando a fórmula $x = -\frac{b}{2a}$.

## Raízes
Os pontos onde a parábola intercepta o eixo $x$, também conhecidos como zeros ou soluções da função quadrática. Eles podem ser encontrados resolvendo a equação quadrática $ax^2 + bx + c = 0$ usando a fórmula de Bhaskara:
$$x = \frac{-b ± \sqrt{b^2 - 4ac}}{2a}$$

## [[Derivada]]
A derivada de uma função de 2º grau $f(x) = ax^2 + bx + c$ é:
$$f'(x) = 2ax + b$$Essa derivada é uma função linear (de 1º grau) e representa a inclinação da parábola em qualquer ponto $x$.