# Definição
**Sequências [[Recursão|recursivas]]** são [[Sequência|sequências numéricas]] em que cada termo é definido em [[função]] de termos anteriores da própria sequência. Ou seja, para calcular um termo específico, utilizam-se os valores de um ou mais termos anteriores, junto com uma fórmula ou regra recursiva.

Uma sequência recursiva é normalmente definida por dois componentes principais:

1. **Condições iniciais (casos base)**: São os primeiros termos da sequência, que não dependem de nenhum outro termo.

2. **Relação de recorrência (caso recursivo)**: É a fórmula que define os termos subsequentes da sequência em função dos termos anteriores.

Sequências recursivas são uma maneira poderosa de definir [[Conjunto|conjuntos numéricos]] onde cada valor depende dos valores anteriores. Elas são usadas para modelar padrões repetitivos e têm aplicações em várias áreas da matemática e ciências exatas. A chave para entender essas sequências está na identificação clara dos **casos base** e das **relações de recorrência**, que determinam como cada novo termo será calculado.
## Exemplos
### [[Progressão Aritmética Recursiva]]
Cada termo é obtido somando uma constante ao termo anterior. Por exemplo:
$$ a_n = a_{n-1} + d $$
Onde:
- $a_0$ (ou $a_1$) é o primeiro termo da sequência (caso base).
- $d$ é a diferença comum entre os termos.

Se $a_0 = 2$ e $d = 3$, então os primeiros termos da sequência serão: 2, 5, 8, 11...
### [[Progressão Geométrica Recursiva]]
Na **progressão geométrica**, cada termo é obtido multiplicando o termo anterior por uma constante chamada razão $r$:
$$ a_n​ = a_{n−1} ​\cdot r $$
Se $a_0​=2$ e $r=3$, os primeiros termos seriam: 2, 6, 18, 54, ...
### [[Sequência de Collatz]]
Dada por uma regra simples: se o número atual for par, divida-o por dois; se for ímpar, multiplique por três e some um. A sequência termina quando chega ao número 1.
$$
C(n) = \begin{cases}
	n/2 & \text{se}\ n\ \text{for par} \\
	3n + 1 & \text{se}\ n\ \text{for ímpar}
\end{cases}
$$