# Definição
O Teorema Binomial ou desenvolvimento do binômio de Newton é uma fórmula que permite expandir a [[Potência|potência]] de um [[Binômio|binômio]]. Um binômio é uma expressão algébrica que contém duas partes, por exemplo, $(a + b)$. O Teorema Binomial nos dá uma maneira sistemática de escrever a expansão de $(a + b)^n$ como uma soma de termos envolvendo [[Número Binomial|coeficientes binomiais]].

## Fórmula do Teorema Binomial
Para um número inteiro não negativo $n$, a expansão de $(a + b)^n$ é dada por:
$$ (a + b)^n = \sum_{k\ =\ 0}^n \binom{n}{k} . a^{n-k} . b^k $$
Onde $\binom{n}{k}$ são os coeficientes binomiais, que podem ser calculados usando a fórmula:
$$ \binom{n}{k} = \frac {n!} {k!\ (n - k)!} $$
## Exemplo
Expandir $(a + b)^3$ usando o Teorema Binomial:
$$ (a + b)^n = \sum_{k\ =\ 0}^3 \binom{3}{k} . a^{3-k} . b^k $$
Calculando os termos:
- Para k = 0
	$$
	\binom{3}{0}.a^{3-0}.b^0
	= 1.a^3.1
	= a^3
	$$
- Para k = 1
	$$
	\binom{3}{1}.a^{3-1}.b^1
	= 3a^2b
	$$
- Para k = 2
	$$
	\binom{3}{2} . a^{3-2} . b^2
	= 3ab^2
	$$
- Para k = 3
	$$
	\binom{3}{3} . a^{3-3} . b^3
	= b^3
	$$
Portanto, a expressão completa é:
$$ (a + b)^3 = a^3 + 3a^2b + 3ab^2 + b^3 $$

