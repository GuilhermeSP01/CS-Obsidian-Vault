# Definição
[[Função|Funções]] contínuas são funções que não têm interrupções, saltos ou quebras em seu domínio. Em termos mais formais, uma função $f(x)$ é contínua em um ponto $c$ se ela atende às três condições a seguir:

- **A função está definida em c**
	$f(c)$ existe
- **O [[Limite|limite]] de $f(x)$ quando $x$ se aproxima de $c$ existe**
	$\lim_{x\ ->\ c} f(x)$ existe
- **O valor da função em $c$ é igual ao limite de $f(x)$ quando $x$ se aproxima de $c$**
	$f(c) = \lim_{x\ ->\ c} f(x)$

Se essas condições são satisfeitas para todos os pontos no domínio da função, então a função é dita contínua em todo o seu domínio.

## Características
**Sem quebras**
	O [[Gráfico|gráfico]] da função pode ser desenhado sem levantar o lápis do papel.

**Sem saltos**
	Não há saltos ou interrupções no gráfico da função.

**Conexão**
	Para qualquer intervalo fechado {a, b}, a imagem da função no intervalo é um intervalo contínuo.

## Exemplo
$f(x) = x^2 + 1$ é uma função contínua, como pode ser visualizado no gráfico:
```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = x^2 + 1
```
