As **classes de equivalência** são [[Subconjunto|subconjuntos]] de um [[conjunto]] que agrupam elementos que estão relacionados entre si por uma **[[relação de equivalência]]**. Elas surgem quando aplicamos uma relação de equivalência a um conjunto, dividindo-o em partes disjuntas, nas quais todos os elementos são considerados "equivalentes" de acordo com a relação definida.

Seja $A$ um conjunto e $∼$ uma relação de equivalência em $A$. Para cada elemento $a∈A$, a **classe de equivalência** de $a$, denotada por $[a]$, é o conjunto de todos os elementos de $A$ que são equivalentes a $a$ segundo a relação $∼$.
$$ [a] = \{x \in A : x ∼ a\} $$
Ou seja, a classe de equivalência de $a$ é o conjunto de todos os elementos que estão relacionados com $a$ pela relação de equivalência.

# Propriedades
As classes de equivalência possuem algumas propriedades importantes:

1. **Partição do Conjunto**: As classes de equivalência particionam o conjunto original. Isso significa que:
    
    - Cada elemento do conjunto pertence a exatamente uma classe.
    - As classes são disjuntas (não têm elementos em comum).
    - A união de todas as classes é igual ao conjunto original.
    
2. **Elementos Equivalentes**: Se dois elementos estão na mesma classe, eles são equivalentes entre si. Se dois elementos estão em classes diferentes, eles não são equivalentes.

# Exemplo com [[Congruência Módulo n|Congruência Módulo]]
Um exemplo clássico de classes de equivalência surge na [[aritmética modular]]. Considere o [[conjunto dos inteiros]] $\mathbb{Z}$ e a relação de congruência módulo $n$, denotada por $\equiv \ (\text{mod}\ n)$. Dois [[Número Inteiro|números inteiros]] $a$ e $b$ são congruentes módulo $n$ se tiverem o mesmo resto quando divididos por $n$, ou seja, $a-b$ é divisível por $n$. As **classes de equivalência** nesse caso são chamadas **classes residuais** ou **classes modulares**. Para cada inteiro $a$, sua classe de equivalência módulo $n$ é o conjunto:
$$ [a]=\{x\in \mathbb{Z}:x\equiv a\ (\text{mod}\ n)\} $$

Por exemplo, no caso do módulo 3:

- A classe residual de 0 é: =\{...,-6,-3,0,3,6,...\}
- A classe residual de 1 é: =\{...,-5,-2,1,4,7,...\}
- A classe residual de 2 é: =\{...,-4,-1,2,5,8,...\}

Essas três classes particionam o conjunto dos inteiros $\mathbb{Z}$ em subconjuntos disjuntos.

# Exemplo com Relação "Igualdade"
Se considerarmos a relação usual de igualdade no [[conjunto dos números reais]] $\mathbb{R}$, cada [[número real]] forma sua própria classe de equivalência. Ou seja, para cada número real $x$, temos:
$$ [x]=\{x\} $$

Nesse caso, as classes de equivalência são triviais porque cada elemento está apenas relacionado consigo mesmo.

## **Aplicações das Classes de Equivalência**

As classes de equivalência aparecem em várias áreas da matemática e têm diversas aplicações práticas:

- **Aritmética Modular**: Como mencionado acima, as classes residuais são usadas para simplificar cálculos em sistemas modulares.
- **Geometria**: Na geometria projetiva e afim, pontos ou figuras podem ser considerados equivalentes sob certas transformações.
- **Teoria dos Conjuntos**: As classes de equivalência ajudam a definir partições e conjuntos quocientes.
- **Teoria dos Grupos**: Em álgebra abstrata, as classes laterais (ou cosets) são um exemplo importante.

Seja $E = \{x \in\ Z / -5 \le x \le 5\}$ e considere a relação $R = \{(x,y) \in ExE / x^2 + 2x = y^2 + 2x\}$. Assinale a alternativa que contenha a classe de equivalência do inteiro 2:
a) $[2] = \{-4,3\}$
b) $[2] = \{-4,2\}$
c) $[2] = \{-3,4\}$
d) $[2] = \{-3,4\}$
e) $[2] = \{2,3\}$