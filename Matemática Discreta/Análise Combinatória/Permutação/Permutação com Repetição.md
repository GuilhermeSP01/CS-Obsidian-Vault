# Definição
Permutação com repetição refere-se à contagem das diferentes maneiras de organizar um conjunto de elementos em que alguns dos elementos podem se repetir. Esse conceito é útil quando estamos interessados em determinar o número de arranjos possíveis de um conjunto onde alguns elementos não são distintos.

A fórmula para calcular o número de permutações com repetição é dada por:
$$ P = \frac {n!} {n_1!\ .\ n_2!\ .\ [...]\ .\ n_k!} $$
onde:
- $n$ é o número total de elementos;
- $n_1$, $n_2$, ... , $n_k$ são as frequências dos elementos que se repetem.

## Exemplo
A palavra "CAIXA" possui 5 letras, onde "A" se repete. Para encontrar o número de diferentes permutações das letras da palavra, basta utilizar a permutação om repetições.

**Total de letras**: $n = 5$ (C, A, I, X, A)
**Frequência das letras**:
- A aparece 2 vezes, então $n_1 = 2$
- C, I e X aparecem 1 vez cada, então $n_2 = n_3 = n_4 = 1$

$$ P = \frac{5!} {2!.1!.1!.1!} = \frac {5.4.3.2!} {2!} = 5.4.3 = 60 $$
Portanto, há 60 maneiras diferentes de permutar a palavra "CAIXA".

## Aplicações
- **Arranjos de palavras**: Determinar o número de diferentes palavras que podem ser formadas com as letras de uma palavra dada.

- **[[Análise Combinatória|Combinatória]]**: Problemas de contagem em contextos como a distribuição de itens idênticos em caixas distintas.

- **[[Criptografia]]**: Analisar a segurança de cifragem baseada em permutações de símbolos.