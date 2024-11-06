# Definição
O Princípio da Casa dos Pombos, também conhecido como Princípio de Dirichlet, é uma ideia simples, mas poderosa, na matemática e na teoria da computação. Ele afirma que, se você tentar distribuir mais pombos do que casas disponíveis, pelo menos uma casa terá mais de um pombo.

Formalmente, o princípio pode ser enunciado como:
- Se $n$ itens são colocados em $m$ recipientes e $n > m$, então pelo menos um dos recipientes conterá mais de um item.

O princípio pode ser generalizado. Por exemplo, se você tiver $n$ pombos e $m$ casas e $n = km + r$ (onde $k$ e $r$ são inteiros e $r$ é o resto da divisão), então pelo menos uma casa terá $k + 1$ pombos se $r \neq 0$.

Este princípio é uma ferramenta fundamental em matemática discreta, combinatória e teoria da computação, pois fornece uma base lógica para provar a existência de certas condições sem necessidade de construir explicitamente as configurações.
## Exemplos
### Exemplo 1
Imagine que você tem 10 pombos e 9 casas de pombos. Usando o princípio, você pode concluir que pelo menos uma casa terá mais de um pombo.
### Exemplo 2
Considere um exemplo clássico: Digamos que você tenha 13 pessoas em uma sala e queira provar que pelo menos duas pessoas compartilham o mesmo mês de aniversário. Aqui, $n = 13$ (pessoas) e $m = 12$ (meses do ano). Pelo Princípio da Casa dos Pombos, com 13 pessoas e 12 meses, pelo menos um mês terá mais de uma pessoa nascida nele.

## Aplicações
- **[[Teoria dos Números]]**:
    - Garantir que dentro de um [[Conjunto dos Inteiros|conjunto de inteiros]], existam pares com propriedades específicas, como a mesma [[Soma|soma]] ou [[Produto|produto]].

- **[[Análise Combinatória|Combinatória]]**:
    - Provar a existência de [[Subconjunto|subconjuntos]] com determinadas características.
    - Exemplo: Em um grupo de pessoas, sempre haverá pelo menos duas com o mesmo número de amigos se o número total de pessoas for maior que o número máximo de amigos possíveis.

- **[[Teoria da Computação]]**:
    - Provar a existência de colisões em [[Função de Hash|funções de hash]].

- **[[Problemas de Contagem e Alocação]]**:
    - Distribuição de recursos ou itens onde restrições garantem que algumas alocações compartilhem recursos.