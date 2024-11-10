# Definição
O **Segundo Princípio da Indução**, também conhecido como **Indução Forte** ou **Indução Completa**, é uma variação do método de prova por [[Indução Matemática|indução matemática]]. Ele é utilizado para provar proposições sobre [[Número Natural|números naturais]], mas difere do **Primeiro Princípio da Indução** no passo indutivo.

Em vez de assumir que a proposição é verdadeira apenas para um número específico $n=k$ e provar que ela vale para $n=k+1$, o segundo princípio assume que a proposição é verdadeira para **todos os valores menores ou iguais a $k$** e, com essa suposição mais forte, prova que a proposição também vale para $n=k+1$.

Assim como no primeiro princípio, o segundo princípio da indução envolve dois passos principais:

1. **Passo Base**: Provar que a proposição é verdadeira para o menor valor de $n$ (geralmente $n=0$ ou $n=1$). Este passo estabelece o ponto inicial da indução.

2. **Passo Indutivo (Hipótese Forte)**: Suponha que a proposição seja verdadeira para todos os números naturais menores ou iguais a um número arbitrário $k$. Ou seja, assume-se que a proposição é verdadeira para todos os valores de $n≤k$. Com essa suposição, prova-se que a proposição também é verdadeira para $n=k+1$. Esse é o passo indutivo mais forte em comparação ao primeiro princípio.

Se ambos os passos forem provados, conclui-se que a proposição é verdadeira para todos os números naturais.

## Exemplo
Vamos usar o segundo princípio da indução para provar uma propriedade fundamental dos números naturais: **todo número natural maior que 1 pode ser [[Fatoração|fatorado]] como um produto de [[Número Primo|números primos]]**.

**Passo Base**:
Para o menor número natural maior que 1, temos:

- Para $n=2$, ele já é um número primo, então ele pode ser escrito como o produto de um único número primo (ele mesmo).

**Passo Indutivo**:
Agora, suponha que todo número natural maior que 1 e menor ou igual a um número arbitrário $k≥2$ possa ser fatorado como um produto de números primos. Precisamos provar que o mesmo vale para o número seguinte, ou seja, para $k+1$.

- Se $k+1$ for primo, então ele já está fatorado como um produto de números primos (ele mesmo).
- Se $k+1$ não for primo, então ele pode ser escrito como o produto de dois números naturais menores do que ele: digamos, $k+1=a×b$. Pela hipótese de indução forte, sabemos que tanto $a$ quanto $b$ podem ser fatorados como produtos de números primos (pois são menores ou iguais a $k$). Logo, podemos escrever $k+1$ como o produto dos fatores primos de $a$ e dos fatores primos de $b$.

Assim, provamos que todo número natural maior que 1 pode ser fatorado como um produto de números primos.

## Quando Usar o Segundo Princípio da Indução
O segundo princípio da indução é especialmente útil em situações onde cada caso depende não apenas do caso imediatamente anterior ($n=k$), mas também de vários casos anteriores ($n≤k$). Alguns exemplos incluem:

- Provas envolvendo divisibilidade.
- Provas sobre propriedades de sequências definidas recursivamente.
- Provas sobre algoritmos ou estruturas combinatórias onde cada etapa depende de várias etapas anteriores.