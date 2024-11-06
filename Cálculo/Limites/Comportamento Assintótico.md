# Definição
Comportamento assintótico refere-se ao comportamento de uma [[Função|função]] à medida que a [[Função#^6dec47|variável independente]] se aproxima de um valor extremo, como o [[Infinito|infinito]] ($\infty$) ou menos infinito ($-\infty$). Em outras palavras, descreve como uma função se comporta "no [[Limite|limite]]" ou "nas extremidades" de seu [[Função#^559652|domínio]].

O comportamento assintótico é essencial em várias áreas da matemática e da ciência. Ele permite prever o comportamento de sistemas complexos em condições extremas, simplificar equações e funções para análise, e compreender melhor as tendências de crescimento ou decaimento em modelos matemáticos.

Exemplos de uso:
- **Física**: O comportamento assintótico é usado para descrever forças que se enfraquecem com a distância, como a gravidade ou a força eletrostática.
    
- **Economia**: Modelos de oferta e demanda podem usar assíntotas para prever comportamentos em extremos de preços ou quantidades.
    
- **Engenharia**: Em análise de sinais e sistemas, o comportamento assintótico ajuda a entender a resposta a longo prazo de circuitos e sistemas dinâmicos.

## Assíntotas Horizontais
Uma função $f(x)$ tem uma assíntota horizontal se, à medida que $x$ se aproxima de $\infty$ ou $-\infty$, $f(x)$ se aproxima de um valor constante $L$.

**Exemplo**
Para $f(x) = \frac {1} {x}$, temos que $lim_{x \to \infty} f(x) = 0$ e $lim_{x \to -\infty} f(x) = 0$, então $y = 0$ é uma assíntota horizontal.

## Assíntotas Verticais
Uma função $f(x)$ tem uma assíntota vertical se, à medida que $x$ se aproxima de um valor $c$, $f(x)$ tende para $\infty$ ou $-\infty$.

**Exemplo**
Para $f(x) = \frac {1} {x}$, temos que $\lim_{x \to 0^+} f(x) = \infty$ e $\lim_{x \to 0^-} f(x) = -\infty$, então $x = 0$ é uma assíntota vertical.

## Assíntotas Oblíquas (ou Assíntotas Inclinadas)
Se uma função $f(x)$ tem uma assíntota oblíqua, à medida que $x$ se aproxima de $\infty$ ou $-\infty$, a função se aproxima de uma linha reta não paralela aos eixos $x$ ou $y$.

**Exemplo***
Para $f(x) = \frac {x^2 - 1} {x}$, remos uma assíntota oblíqua $y = x$.
```functionplot
---
title: 
xLabel: X
yLabel: Y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = (x^2 - 1) / x
```
