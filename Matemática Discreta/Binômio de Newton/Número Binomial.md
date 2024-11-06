# Definição
Números binomiais, também conhecidos como coeficientes binomiais, são os coeficientes dos termos na expansão de um binômio elevado a uma potência, conforme descrito pelo [[Teorema Binomial de Newton]]. Eles são denotados como $\binom{n}{k}$ e são lidos como "$n$ escolhe $k$".

O coeficiente binomial $\binom{n}{k}$ é definido como:
$$ \binom{n}{k} = \frac {n!} {k!\ (n - k)!} $$

O Coeficiente binomial tem a mesma definição de [[Combinação Simples]]
## Propriedades
### Simetria
$$ \binom{n}{k} = \binom{n}{n-k} $$

### Valor em 0 e n
$$ \binom{n}{0} = \binom{n}{n} = 1 $$
### Valor em n-1
$$ \binom{n}{n-1} = n $$

### Propriedade Recursiva
$$
\binom{n}{k} = 
\binom{n - 1}{k - 1}
+ \binom{n - 1}{k}
$$
#### Exemplo
Dados $\binom{4}{1} = 4$ e $\binom{4}{2} = 6$, calcule $\binom{5}{2}$
$$ \binom{5}{2} = \binom{4}{1} + \binom{4}{2} = 4 + 6 = 10 $$

## Números Binomiais Complementares

Números binomiais complementares referem-se a pares de coeficientes binomiais que estão relacionados por meio de uma propriedade específica. Esta propriedade decorre da [[#Simetria|simetria]] dos coeficientes binomiais.

### Demonstração
$$
\binom{5}{2}
= \frac {5!} {2!\ (5-2)!}
= \frac {5.4.3!} {2 . 3!}
= \frac {20} {2}
= 10
$$

$$
\binom{5}{3}
= \frac {5!} {3!\ (5 - 3)!}
= \frac {5 . 4 . 3!} {3!\ 2!}
= \frac {20} {2}
= 10
$$
Portanto:
$$
\binom{5}{2} = \binom{5}{3} = 10
$$