# Definição
[[Função|Funções]] descontínuas são aquelas que apresentam uma ou mais interrupções, saltos ou quebras em seu domínio. Em outras palavras, em certos pontos, a função não segue uma progressão suave e contínua. A continuidade de uma função é crucial para muitas aplicações matemáticas, e a descontinuidade pode revelar comportamentos importantes de fenômenos reais.

## Visualização gráfica
**[[Função Contínua]]**
[[Gráfico]] sem interrupções, pode ser desenhado sem levantar o lápis do papel

**Função Descontínua**
Gráfico com saltos, quebras ou pontos onde a função não é definida.

## Tipos de descontinuidade

### Descontinuidade de Salto
Ocorre quando o limite da função à direita de um ponto é diferente do limite à esquerda.

Exemplo: Função degrau unitário

$f(x) = \begin{cases} 0 & x < 0 \\ 1 & x \ge 0 \end{cases}$
```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = x < 0 ? 0 : 1
```

### Descontinuidade Infinita
Ocorre quando a função tende ao [[Infinito|infinito]] em um determinado ponto.

O exemplo abaixo contém uma descontinuidade infinita em $x = 0$, isso por que o [[Limite|limite]] de $f(x)$ quando $x$ tende a 0 é infinito.

$f(x) = \frac {1} {x} \ \ \ \ \ \ \ \ \ \lim_{x\ ->\ 0^+} f(\frac {1} {x}) = +\infty \ \ \ \ \ \ \ \ \ \lim_{x\ ->\ 0^-} f(\frac {1} {x}) = -\infty$
```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = 1/x
```

### Descontinuidade Removível
Ocorre quando o limite da função existe, mas não está definido naquele ponto ou o valor da função naquele ponto é diferente do limite.

No exemplo a baixo, para $x \ne 1$, $f(x)$ pode ser simplificado para $x + 1$. No entanto, em $x + 1$, temos uma descontinuidade removível.

$f(x) = \begin{cases} \frac {x^2 - 1} {x - 1} & x \ne 1 \\ 2 & x = 1 \end{cases}$

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-1,4,-1,4]
disableZoom: true
grid: true
---
f(x) = x > 0.95 & x < 1.05 ? 1 : (x^2 - 1) / ( x - 1)
```



