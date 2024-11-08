# Definição
A **cardinalidade da [[união de conjuntos]]** refere-se ao número de elementos no [[conjunto]] resultante da união de dois ou mais conjuntos. A união de dois conjuntos $A$ e $B$, denotada por $A∪B$, é o conjunto que contém todos os elementos que pertencem a $A$, a $B$, ou a ambos. Para calcular a cardinalidade da união, é necessário levar em consideração os elementos comuns aos conjuntos, para evitar contá-los mais de uma vez.
## Fórmula
A fórmula para calcular a cardinalidade da união de dois conjuntos $A$ e $B$ é:
$$ ∣A∪B∣\ =\ ∣A∣+∣B∣−∣A∩B∣ $$

Onde:
- $∣A∣$ é a cardinalidade (número de elementos) do conjunto $A$.
- $∣B∣$ é a cardinalidade do conjunto $B$.
- $∣A∩B∣$ é a cardinalidade da [[Interseção de Conjuntos|interseção]] entre os conjuntos, ou seja, o número de elementos que estão em ambos os conjuntos.

A soma $∣A∣+∣B∣$ contabiliza todos os elementos dos dois conjuntos.

No entanto, se houver elementos comuns entre os dois conjuntos (ou seja, se $A ∩ B \ne ∅$), eles serão contados duas vezes. Para corrigir isso, subtraímos $∣A∩B∣$, que representa o número de elementos que aparecem em ambos os conjuntos.
## Exemplo
Considere os seguintes conjuntos:
- $A=\{1,2,3\}$
- $B=\{3,4,5\}$

A união dos conjuntos será:  
$A∪B=\{1,2,3,4,5\}$

Agora, aplicando a fórmula:
$$ ∣ A ∪ B ∣\ =\ 3 + 3 − 1 = 5 $$
Portanto, a cardinalidade da união de $A$ e $B$ é 5.
## Extensão para Mais Conjuntos
Para três conjuntos $A$, $B$, e $C$, a fórmula da cardinalidade da união é um pouco mais complexa:
$$ ∣A∪B∪C∣\ =\ ∣A∣+∣B∣+∣C∣−∣A∩B∣−∣A∩C∣−∣B∩C∣+∣A∩B∩C∣ $$

Essa fórmula segue o mesmo princípio: somamos as cardinalidades dos conjuntos individuais e subtraímos as interseções duplas para evitar contagens repetidas. Em seguida, adicionamos as interseções triplas para corrigir o excesso de subtração.