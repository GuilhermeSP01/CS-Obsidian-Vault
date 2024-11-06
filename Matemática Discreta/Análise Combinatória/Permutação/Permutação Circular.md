# Definição
Permutação circular é o arranjo de objetos em um círculo, onde a posição relativa dos objetos é importante, mas a rotação do círculo não cria uma nova [[Permutação Simples|permutação]]. Em outras palavras, duas permutações são consideradas iguais se puderem ser transformadas uma na outra por uma rotação do círculo.

Para calcular o número de permutações distintas de $n$ objetos dispostos em um círculo, usa-se a seguinte fórmula:
$$ P = (n-1)! $$
Essa fórmula resulta em um circulo, pois uma das posições é considerada fixa para evitar contagens duplicadas devido à rotação

A permutação circular é uma área interessante em [[Análise Combinatória|combinatória]] que destaca como pequenas mudanças na estrutura de um problema podem afetar drasticamente a contagem de soluções possíveis.

## Exemplo
4 objetos (A, B, C, D) são dispostos em um círculo. O número de permutações distintas é dado por:
$$ P = (4-1)! = 3! = 6 $$
Portanto, há 6 maneiras distintas de arranjar 4 objetos em um círculo.

## Aplicações
- **Problemas de Arranjo**: Organizar pessoas ao redor de uma mesa redonda, onde a ordem dos lugares importa.
- **[[Criptografia]]**: Utilizado em algoritmos que requerem arranjos circulares de símbolos.
- **Design**: Distribuição de elementos em projetos circulares, como cadeiras ao redor de uma mesa, pedras preciosas em joias circulares, ou layout de rodas.