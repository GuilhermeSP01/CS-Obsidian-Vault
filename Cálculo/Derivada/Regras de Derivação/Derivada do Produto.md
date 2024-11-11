# Definição
A **[[Regras de Derivação|regra da derivada]] do [[Produto|produto]]**, também conhecida como **regra do produto**, é uma fórmula usada para calcular a [[derivada]] do produto de duas [[Função|funções]]. Ela afirma que a derivada do produto de duas funções não é simplesmente o produto das derivadas, mas sim uma combinação específica das funções e suas derivadas.

Seja $f(x)=g(x)⋅h(x)$, onde $g(x)$ e $h(x)$ são funções diferenciáveis, então a derivada de $f(x)$ é dada por:
$$ f′(x)=g′(x)⋅h(x)+g(x)⋅h′(x) $$
## Explicação

- A regra do produto diz que a derivada de um produto de duas funções é a soma de dois termos:
    
    1. A derivada da primeira função multiplicada pela segunda função.
    2. A primeira função multiplicada pela derivada da segunda função.
    

Isso significa que, ao calcular a derivada de um produto, você precisa levar em consideração tanto a variação da primeira função quanto a variação da segunda função.

## Exemplo
Considere a função $f(x) = (3x - 1) \cdot (x^2 + 4x + 5)$

Neste caso, temos:
- $g(x) = 3x - 1$. Então $g'(x) = 3$
- $h(x) = x^2 + 4x + 5$. Então $h'(x) = 2x + 4$

Aplicando a regra do produto:
$$ f'(x) = 3 \cdot (x^2 + 4x + 5) + (3x - 1) \ cdot (2x + 4) $$
Agora, expandimos os termos:
$$ f(x) = 3x^3 + 12x + 15 + 6x^2 + 12x - 2x - 4 $$
Simplificando:
$$ f'(x) = 9x^2 + 22x + 11 $$