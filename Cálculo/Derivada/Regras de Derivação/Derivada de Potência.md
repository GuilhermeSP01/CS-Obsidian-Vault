# Definição
A **regra da potência** é uma das [[Regras de Derivação|regras]] mais fundamentais no cálculo diferencial e permite calcular a [[derivada]] de [[Função|funções]] na forma de uma [[Portência|potência]] de uma [[Variável|variável]]. Ela se aplica a funções da forma $f(x)=x^n$, onde $n$ é um [[Número Real|número real]] (geralmente um [[Número Inteiro|inteiro]] ou um [[Número Racional|número racional]]).

Se $f(x)=x^n$, então a derivada de $f(x)$ em relação a $x$ é dada por:
$$ f′(x) = n \cdot x^{n−1} $$
## Explicação

- O expoente $n$ é trazido para frente como um fator multiplicativo.
- O novo expoente da variável $x$ será $n−1$, ou seja, subtraímos 1 do expoente original.

## Exemplos
### Exemplo 1: Derivada de $f(x) = x^3$
$$ f'(x) = 3 \cdot x^{3-1} = 3x^2 $$
### Exemplo 2: Derivada de $f(x) = x^{-2}$
$$ f'(x) = -2x^{-2-1} = -2x^{-3} $$
### Exemplo 3: Derivada de $f(x) = x^{1/2}$
$$ f(x) = \frac 1 2 x^{\frac 1 2 - 1} = \frac 1 2 x^{-\frac 1 2}  $$
## Aplicação em Polinômios
A regra da potência é frequentemente usada para derivar termos individuais em polinômios. Por exemplo, para derivar o polinômio $f(x)=5x4+3x2−x+7$, aplicamos a regra da potência em cada termo:

- Para $5x^4$, temos: $f′(x)= 4 \cdot 5x^{4−1} = 20x^{3}$
- Para $3x^2$, temos: $f′(x)= 2 \cdot 3x^{2−1} = 6x$
- Para $−x$, temos: $f′(x)= −1 \cdot x^{1−1}= −1$
- O termo constante $7$ tem derivada zero.

Portanto, a derivada do polinômio é:

f′(x)=20x3+6x−1f′(x)=20x3+6x−1