# Definição
Sequência ordenada de elementos, onde a ordem importa. Por exemplo, a lista {1, 2, 3} é diferente da lista {3, 2, 1}, mesmo que contenham os mesmos números. Elas são úteis quando queremos manter uma sequência ou quando a posição dos elementos tem relevância.

A lista {1, 2, 2, 3} é perfeitamente válida, ao contrário dos conjuntos que não permitem repetição de elementos.

## Comprimento da lista
O comprimento de uma lista é o número total de elementos que ela contém. Por exemplo, a lista {4, 7, 9} tem um comprimento de 3 porque inclui três elementos.

Denotada como len(lista) em linguagens de programação.

## Igualdade entre listas
Igualdade entre listas significa que duas listas são consideradas iguais se contiverem exatamente os mesmos elementos, na mesma ordem. Por exemplo, a lista {1, 2, 3} é igual à lista {1, 2, 3}, mas é diferente da lista {3, 2, 1}, mesmo que contenham os mesmos elementos. Esse conceito é super importante, especialmente em programação, onde a ordem dos elementos pode alterar completamente o resultado de uma operação ou função.

## Lista vazia
Uma lista vazia é simplesmente uma lista que não contém nenhum elemento. Ela é representada por colchetes vazios: { }. O comprimento de uma lista vazia é zero, pois não há elementos nela. Apesar de parecer trivial, listas vazias são super úteis em programação e algoritmos, especialmente quando inicializamos estruturas de dados ou verificamos condições.

## Contagem de listas
A contagem de listas refere-se ao número de maneiras diferentes de organizar ou selecionar elementos em uma lista. 

O número total de listas possíveis é dado por
$$ n^k $$
onde:
- $n$: Número de elementos
- $k$: Comprimento da lista

### Exemplo
Por exemplo, se você tiver 3 elementos e quiser formar listas de comprimento 2, o número de listas possíveis é
$3^2 = 6$ listas possíveis

## Princípio da multiplicação
O Princípio da Multiplicação, ou Princípio Fundamental da Contagem, é uma ferramenta matemática usada para calcular o número total de maneiras de realizar uma série de escolhas independentes.

Por exemplo, se você tiver 3 camisetas (A, B e C) e 2 calças (X e Y), o número total de combinações possíveis de uma camiseta e uma calça é:

Número total de combinações = (número de camisetas) * (número de calças) = 3 * 2 = 6

Portanto, há 6 combinações possíveis: AX, AY, BX, BY, CX e CY. O Princípio da Multiplicação simplifica a contagem dessas combinações de maneira eficiente.