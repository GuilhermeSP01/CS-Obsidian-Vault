# Definição
O Triângulo de Pascal é uma disposição triangular dos [[Número Binomial|coeficientes binomiais]] que foi amplamente estudada pelo matemático francês Blaise Pascal. Cada linha do triângulo representa os coeficientes binomiais de uma expansão binomial, e ele é uma ferramenta útil em várias áreas da matemática, incluindo álgebra, combinatória e teoria dos números.

A ideia é formar um triângulo onde cada linha é representada pelo valor $n$ e cada coluna pelo valor $k$ de um número binomial
$$ \binom{n \implies linha}{k \implies coluna} $$

| $n$ / $k$ | 0                | 1                | 2                | 3                | 4                | 5                |
| --------- | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- | ---------------- |
| 0         | $$\binom{0}{0}$$ |                  |                  |                  |                  |                  |
| 1         | $$\binom{1}{0}$$ | $$\binom{1}{1}$$ |                  |                  |                  |                  |
| 2         | $$\binom{2}{0}$$ | $$\binom{2}{1}$$ | $$\binom{2}{2}$$ |                  |                  |                  |
| 3         | $$\binom{3}{0}$$ | $$\binom{3}{1}$$ | $$\binom{3}{2}$$ | $$\binom{3}{3}$$ |                  |                  |
| 4         | $$\binom{4}{0}$$ | $$\binom{4}{1}$$ | $$\binom{4}{2}$$ | $$\binom{4}{3}$$ | $$\binom{4}{4}$$ |                  |
| 5         | $$\binom{5}{0}$$ | $$\binom{5}{1}$$ | $$\binom{5}{2}$$ | $$\binom{5}{3}$$ | $$\binom{5}{4}$$ | $$\binom{5}{5}$$ |
Que resulta no triângulo:

| $n$ / $k$ | 0   | 1   | 2   | 3   | 4   | 5   |
| --------- | --- | --- | --- | --- | --- | --- |
| 0         | 1   |     |     |     |     |     |
| 1         | 1   | 1   |     |     |     |     |
| 2         | 1   | 2   | 1   |     |     |     |
| 3         | 1   | 3   | 3   | 1   |     |     |
| 4         | 1   | 4   | 6   | 4   | 1   |     |
| 5         | 1   | 5   | 10  | 10  | 5   | 1   |

## Propriedades
### Simetria
O Triângulo de Pascal é simétrico em relação ao seu centro vertical.
$$ \binom{n}{k} = \binom{n}{n - k} $$
### Soma das Linhas
A soma dos números em qualquer linha $n$ é $2^n$
#### Exemplo
Na linha 3
$$ \binom{3}{0} + \binom{3}{1} + \binom{3}{2} + \binom{3}{3} = 1 + 3 + 3 + 1 = 8$$
Usando a propriedade:
$$ 2^3 = 8 $$
### Relação Recursiva (Rel. de Stifel)
Cada número é a soma dos dois números diretamente acima dele:
$$ \binom{n}{k} = \binom{n - 1}{k - 1} + \binom{n - 1}{k} $$
#### Exemplo
$$ \binom{5}{3} = \binom{4}{2} + \binom{4}{3} = 6 + 4 = 10 $$
### Soma de Colunas
A soma dos elementos de uma coluna até a linha $n$ resulta no valor que está abaixo e a direita do elemento na linha $n$
#### Exemplo
$$ \binom{1}{1} + \binom{2}{1} + \binom{3}{1} + \binom{4}{1} = \binom{5}{2} $$
$$ 1 + 2 + 3 + 4 = 10 $$
### Soma de Diagonais
A soma dos elementos de uma diagonal até a linha $n$ resulta no valor que está abaixo do elemento na linha $n$
#### Exemplo
$$ \binom{1}{0} + \binom{2}{1} + \binom{3}{2} + \binom{4}{3} + \binom{5}{4} = \binom{6}{4} $$
$$ 1 + 2 + 3 + 4 + 5 = 15 $$
### Diagonais
- A primeira diagonal consiste apenas em 1s.
- A segunda diagonal consiste nos números naturais: 1, 2, 3, 4, ...
- A terceira diagonal consiste nos números triangulares: 1, 3, 6, 10, ...

### Números de Fibonacci #WIP
A soma dos números ao longo das diagonais descendentes alternadas é um [[Número de Fibonacci|número de Fibonacci]].

## Exemplos
### Exemplo 1
$$ \binom{8}{2} + \binom{8}{3} = \binom{9}{3} $$
$$
\binom{9}{3}
= \frac{9!} {3!\ 6!}
= \frac{9.8.7.6!} {3.2\ . 6!}
= 3 . 4 . 7
= 84
$$
### Exemplo 2
$$ \binom{7}{0} + \binom{7}{1} + \binom{7}{2} +\ ...\ + \binom{7}{7} = 2^7 = 128 $$
### Exemplo 3
$$ \binom{2}{0} + \binom{3}{1} + \binom{4}{2} + \binom{5}{3} + \binom{6}{4} = \binom{7}{4} $$
$$
\binom{7}{4}
= \frac {7!} {4!\ 3!}
= \frac {7.6.5.4!} {4!\ 6}
= 7.5
= 35
$$
### Exemplo 4
$$ \binom{2}{2} + \binom{3}{2} + \binom{4}{2} +\ ...\ + \binom{9}{2} = \binom{10}{3} $$
$$
\binom{10}{3} = \frac {10!} {3!\ 7!}
= \frac {10.9.8.7!} {3.2\ 7!}
= 10.3.4
= 120
$$