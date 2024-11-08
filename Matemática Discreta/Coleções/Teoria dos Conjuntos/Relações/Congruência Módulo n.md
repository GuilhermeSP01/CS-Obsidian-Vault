# Definição
A **congruência módulo $n$** é um conceito da [[Aritmética Modular|aritmética modular]] que define uma [[relação]] entre dois [[Número Inteiro|números inteiros]] com base no [[Resto da Divisão|resto da divisão]] por um número fixo $n$, chamado de **módulo**.

Dizemos que dois inteiros $a$ e $b$ são **congruentes módulo $n$**, e escrevemos $a\equiv b\ (\text{mod}\ n)$, se a diferença entre eles, $a-b$, for divisível por $n$. Em outras palavras, isso significa que a e b deixam o mesmo resto quando divididos por $n$.

Formalmente:
$$ a\equiv b\ (\text{mod}\ n)\quad \text{se e somente se}\quad n|(a-b) $$
Ou seja, existe um inteiro $k$ tal que:
$$ a-b=k\cdot n $$
## Exemplos
- $38\equiv 14\ (\text{mod}\ 12)$, porque 38-14=24, e 24 é divisível por 12.
- $17\equiv 5\ (\text{mod}\ 6)$, porque 17-5=12, que também é divisível por 6.

# Propriedades
A congruência módulo n possui algumas propriedades importantes:

1. **Reflexividade**: Para qualquer inteiro a, temos que $a\equiv a\ (\text{mod}\ n)$.
2. **Simetria**: Se $a\equiv b\ (\text{mod}\ n)$, então $b\equiv a\ (\text{mod}\ n)$.
3. **Transitividade**: Se $a\equiv b\ (\text{mod}\ n)$ e $b\equiv c\ (\text{mod}\ n)$, então $a\equiv c\ (\text{mod}\ n)$.
4. **Compatibilidade com operações aritméticas**:
    
    - Se $a_1\equiv b_1(\text{mod}~n)$ e $a_2\equiv b_2(\text{mod}~n)$, então:
        
        - $a_1+a_2\equiv b_1+b_2(\text{mod}~n)$
        - $a_1-a_2\equiv b_1-b_2(\text{mod}~n)$
        - $a_1\cdot a_2\equiv b_1\cdot b_2(\text{mod}~n)$

# Classes de Congruência
A congruência módulo define classes de equivalência chamadas **classes de resíduos**. Todos os números que são congruentes entre si módulo n pertencem à mesma classe de resíduo. Por exemplo, no caso do módulo 12, os números que deixam o mesmo resto quando divididos por 12 pertencem à mesma classe de resíduo.

# Aplicações
A congruência módulo é amplamente usada em diversas áreas da matemática e da ciência da computação, como:

- [[Criptografia]]
- [[Teoria dos Números]]
- [[Algoritmo de Hasing|Algoritmos de hashing]]
- Geração de [[Número Pseudo-aleatório|números pseudo-aleatórios]]

Em resumo, congruência módulo é uma forma de comparar números com base no seu resto após divisão por um número fixo, e é uma ferramenta poderosa na aritmética modular