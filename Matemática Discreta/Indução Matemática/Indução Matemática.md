# Definição
**Indução Matemática** é um método de prova utilizado em [[matemática]] para demonstrar a veracidade de proposições que envolvem [[Número Natural|números naturais]]. Ele é especialmente útil para provar afirmações sobre um número infinito de casos, como fórmulas envolvendo somas, produtos ou desigualdades.

A indução matemática segue dois passos principais:

1. **Passo Base**: Demonstra-se que a proposição é verdadeira para o menor valor de $n$, geralmente $n=0$ ou $n=1$, dependendo do contexto. Este passo estabelece o ponto inicial da prova.

2. **Passo Indutivo**: Assume-se que a proposição é verdadeira para um número arbitrário $n=k$ (essa suposição é chamada de _[[Hípotese de Indução|hipótese de indução]]_), e então prova-se que a proposição também é verdadeira para $n=k+1$. Este passo garante que, se a proposição for verdadeira para um número qualquer $k$, ela também será verdadeira para o próximo número.

Se ambos os passos forem provados, conclui-se que a proposição é verdadeira para todos os números naturais $n$.

## Exemplos
### Dominós
Uma maneira intuitiva de entender a indução matemática é compará-la a uma fila de dominós:

- O **passo base** garante que o primeiro dominó cai.
- O **passo indutivo** garante que, se um dominó cair, o próximo também cairá.  

Assim, todos os dominós cairão, ou seja, a proposição será verdadeira para todos os números naturais.

### Soma dos Primeiros $n$ Números Naturais
Vamos provar, por indução matemática, que a soma dos primeiros $n$ números naturais é dada pela fórmula: 
$$ S(n) = 1 + 2 + 3 + ... + n = \frac {n \cdot (n + 1)} {2} $$
**Passo Base**:
Para $n=1$, temos:
$$ S(1) = 1 = \frac {1 \cdot (1 + 1)} {2} = 1 $$
Logo, a fórmula é verdadeira para $n=1$.

**Passo Indutivo**:
Suponha que a fórmula seja verdadeira para algum número natural $k$. Ou seja, assumimos que:
$$ S(k) = 1 + 2 + 3 + ... + k = \frac {k \cdot (k + 1)} {2}$$
Agora, precisamos provar que a fórmula também vale para $k+1$. A soma dos primeiros $k+1$ números naturais é:
$$ S(k + 1) = S(k) + (k + 1) $$
Substituindo a hipótese de indução:
$$ S(k+1) = \frac {k \cdot (k + 1)} 2 + (k + 1) $$
Colocando $k+1$ em evidência:
$$ S(k+1) = (k+1) \cdot \Bigl(\frac k 2 + 1\Bigl) $$
Logo:
$$ S(k+1) = \frac {(k+1) \cdot (k+2)} 2 $$
Portanto, a fórmula também vale para $k+1$.

Como mostramos que a fórmula é verdadeira para $n=1$ (passo base) e que, se for verdadeira para $n=k$, então também será verdadeira para $n=k+1$ (passo indutivo), concluímos por indução matemática que a fórmula é válida para todos os números naturais $n$.

## Generalizações
Existem variações da indução matemática, como:

- **[[Indução Forte|Indução forte]]**: Além de assumir que a proposição vale para $n=k$, assume-se também que ela vale para todos os valores menores ou iguais a $k$.

- **[[Indução Transfinita|Indução transfinita]]**: Utilizada em conjuntos bem ordenados além dos números naturais, como [[Número Ordinal|ordinais]].

Em resumo, a indução matemática oferece uma maneira rigorosa e eficiente de provar propriedades sobre números naturais e outros conjuntos bem ordenados