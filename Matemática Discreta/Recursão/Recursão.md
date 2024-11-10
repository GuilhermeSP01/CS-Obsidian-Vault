# Definição
Em matemática, **recursão** é um conceito em que um objeto (como uma [[função]] ou [[Sequência|sequência]]) é definido em termos de si mesmo. Isso significa que a solução de um problema é expressa como uma chamada repetida a uma versão menor ou mais simples do mesmo problema, até que se atinja um caso base, onde a solução é direta e não recursiva.

Uma definição recursiva geralmente segue dois passos:

1. **Caso base**: Define o valor da função para um ou mais casos específicos, que não dependem de outras chamadas recursivas. Este é o ponto onde a recursão termina.

2. **Caso recursivo**: Define o valor da função em termos de uma chamada à própria função com argumentos menores ou mais simples, aproximando-se do caso base.

## Exemplos
### [[Fatorial]]
Um exemplo clássico de recursão é a função fatorial ($n!$), que pode ser definida recursivamente da seguinte forma:
$$
n! = \begin{cases}
	1 & \text{se}\ n = 0 \\
	n \cdot (n-1)! & \text{se}\ n > 0
\end{cases}
$$
Neste exemplo:

- O **caso base** é $0!=1$.
- O **caso recursivo** define $n!$ como $n×(n−1)!$, ou seja, o fatorial de $n$ depende do fatorial de $n−1$.
### [[Sequência de Fibonacci]]
A sequência de Fibonacci também pode ser definida recursivamente. O $n$-ésimo número da sequência é a soma dos dois números anteriores:

$$
F(n) = \begin{cases}
	0 & \text{se}\ n = 0 \\
	1 & \text{se}\ n = 1 \\
	F(n-1) + F(n-2) & \text{se}\ n > 1
\end{cases}
$$

Aqui, os casos base são $F(0)=0$ e $F(1)=1$, e o caso recursivo define cada termo como a soma dos dois anteriores.

## Aplicações da Recursão
A recursão é amplamente utilizada em diversas áreas da [[Matemática|matemática]] e da [[Ciência da Computação|ciência da computação]], como:

- Definição de funções matemáticas (como o fatorial e Fibonacci).
- Resolução de problemas algorítmicos complexos (como a [[Torre de Hanói]]).
- Definição de sequências e [[Conjunto|conjuntos]].

Em resumo, a recursão é uma ferramenta poderosa para resolver problemas complexos dividindo-os em subproblemas menores e mais gerenciáveis, até que se chegue a uma solução direta.