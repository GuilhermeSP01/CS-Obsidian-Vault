# Definição
Equações lineares com soluções inteiras não negativas referem-se a um sistema de [[Equação Linear|equações lineares]] onde estamos interessados em encontrar soluções que sejam [[Número Inteiro|números inteiros]] e, ao mesmo tempo, não sejam [[Número Negativo|negativos]] (ou seja, sejam [[Zero|zero]] ou [[Número Positivo|positivos]]).

Uma equação linear tem a forma geral:
$$ ax + by + cz +\ ...\ = d $$
Onde $a$, $b$, $c$, ... e $d$ são [[Coeficiente|coeficientes]] ([[Constante|constantes]]), e $x$, $y$, $z$, ... são [[Variável|variáveis]]

As soluções inteiras não negativas são aquelas onde $x$, $y$, $z$, ... são números inteiros ($Z$) e $x$, $y$, $z$, ... $\ge$ 0.

## Fórmula
Para encontrar o número de soluções inteiras não negativas da [[Equação|equação]] $x_1 + x_2 +\ ...\ + x_k = n$, utilizamos a fórmula:
$$ \binom{n + k - 1}{k - 1} $$
[[Número Binomial]] [[Combinação Simples]]

### Explicação
#### Representação da Equação
- Considere a soma dos $k$ termos $x_1, x_2,\ ...\ x_k$ que devem resultar em $n$.
#### Composição com Repetição
- Visualmente, podemos representar cada unidade de $n$ como uma bolinha e a separação entre diferentes $x_i$ como um divisor.
- Por exemplo, para $n = 5$ e $k = 3$, poderíamos ter: ∙∙∣∙∣∙∙
#### Total de Objetos
- Temos $n$ bolinhas e $k - 1$ divisores (já que precisamos de $k-1$ divisores para separar $k$ grupos).
#### Número de Combinações
- O problema se reduz a determinar de quantas maneiras podemos organizar $n + k - 1$ objetos, onde $n$ são bolinhas e $k - 1$ são divisores.
## Exemplos
### Exemplo 1: duas variáveis
Considere a equação linear
$$ 2x + 3y = 6 $$
Queremos encontrar as soluções inteiras não negativas para $x$ e $y$.

Possíveis soluções:
- ($x$, $y$) = (0, 2) porque $2.(0) + 3.(2) = 6$
- ($x$, $y$) = (3, 0) porque  $2.(3) + 3.(0) = 6$
Portanto, (0, 2) e (3, 0) são soluções inteiras não negativas.

### Exemplo 2: três variáveis
Considere a equação linear
$$ x + y + z = 4 $$
Queremos encontrar as soluções inteiras não negativas para $x$, $y$ e $z$.

Possíveis soluções:
- $(x, y, z) = (0, 0, 4)$
- $(x, y, z) = (1, 1, 2)$
- $(x, y, z) = (2, 1, 1)$
- $(x, y, z) = (1, 2, 1)$
...

Aplicando a fórmula para encontrar a quantidade de soluções possíveis:
$n = 4$
$k = 3$
$$
\binom{n + k - 1}{k - 1}
= \binom{4 + 3 - 1}{3 - 1}
= \binom{6}{2}
= \frac {6!} {2!.4!}
= \frac {6.5.4!} {2.4!}
= 3.5
= 15
$$