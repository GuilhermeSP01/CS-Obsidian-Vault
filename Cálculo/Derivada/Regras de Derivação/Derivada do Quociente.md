# Definição
A **[[Regras de Derivação|regra da derivada]] do [[Quociente|quociente]]**, também conhecida como **regra do quociente**, é uma fórmula usada para calcular a [[derivada]] de uma [[função]] que é o quociente (divisão) de duas outras funções. Assim como a regra do produto, ela envolve tanto as funções quanto suas derivadas, mas com uma estrutura mais complexa devido à divisão.

Seja $f(x) = \frac {g(x)} {h(x)}$, onde $g(x)$ e $h(x)$ são funções diferenciáveis e $h(x) \ne 0$, então a derivada de $f(x)$ é dada por:
$$ f'(x) = \frac {g'(x) \cdot h(x) - g(x) \cdot h'(x)} {[h(x)]^2} $$
## Exemplo
Considere a função $f(x) = \frac {x^2} {x+1}$
Aqui, temos:
- $g(x) = x^2$, então $g'(x) = 2x$
- $h(x) = x + 1$, então $h'(x) = 1$

Aplicando a regra do quociente:
$$ f'(x) = \frac {(2x) \cdot (x + 1) - (x^2) \cdot (1)} {(x + 1)^2} $$
Agora, simplificamos:
$$ f'(x) = \frac {2x (x + 1) - x^2} {(x+1)^2} $$
Expandimos os termos:
$$ f'(x) = \frac {2x^2 + 2x - x^2} {(x + 1)^2} $$
Portanto a derivada é:
$$ f'(x) = \frac {x(x + 2)} {(x + 1)^2} $$