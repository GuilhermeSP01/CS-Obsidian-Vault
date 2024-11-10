# Definição
**[[Conjunto|Conjuntos]] [[Recursão|recursivos]]**, também conhecidos como **conjuntos decidíveis** ou **computáveis**, são conjuntos para os quais existe um [[Algoritmo|algoritmo]] que pode determinar, em tempo finito, se um elemento pertence ou não ao conjunto.

Em termos formais, um conjunto $A$ é [[Recursão|recursivo]] se existe uma [[função]] característica computável $χA​(x)$, que retorna 1 se $x∈A$ e 0 se $x∉A$. Isso significa que, dado qualquer elemento $x$, o algoritmo pode decidir de maneira definitiva se $x$ está ou não no conjunto.

Um conjunto $A⊆N$ ([[Conjunto dos Números Naturais|conjunto dos números naturais]]) é chamado **recursivo** se existe uma [[Máquina de Turing|máquina de Turing]] (ou um algoritmo equivalente) que, para qualquer entrada $x$, responde corretamente:
- **Sim**: Se $x∈A$,
- **Não**: Se $x∉A$.

Em outras palavras, a máquina de Turing sempre termina (ou seja, é decidível) e fornece uma resposta correta sobre a pertinência do elemento ao conjunto.

## Exemplo
Considere o conjunto dos [[Número Par|números pares]] $P=\{0,2,4,6,8,...\}$. Esse conjunto é recursivo porque podemos construir um algoritmo simples que verifica se um número é par (por exemplo, verificando se o número é divisível por 2). O algoritmo sempre termina e dá a resposta correta.

## Relação com Conjuntos Recursivamente Enumeráveis
Um conceito relacionado é o de **conjuntos recursivamente enumeráveis**. Um conjunto é **recursivamente enumerável** se existe um algoritmo que pode listar seus elementos, mas esse algoritmo pode nunca parar para elementos que não pertencem ao conjunto. Diferentemente dos conjuntos recursivos, onde há uma decisão definitiva sobre a pertinência de qualquer elemento, em conjuntos recursivamente enumeráveis o algoritmo pode rodar indefinidamente sem dar uma resposta para elementos fora do conjunto.