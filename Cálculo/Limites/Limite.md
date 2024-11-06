# Definição
O limite é um conceito fundamental em matemática que descreve o comportamento de uma [[Função|função]] quando a variável de entrada se aproxima de um determinado valor. Ele é essencial para entender muitos aspectos do cálculo e da análise matemática.

Os limites são fundamentais para definir [[Derivada|derivadas]] e [[Integral|integrais]], que são as bases do cálculo diferencial e integral. Eles também são usados para estudar a [[Função Contínua|continuidade das funções]] e o [[Comportamento Assintótico|comportamento assintótico]].

## Definição Intuitiva
Intuitivamente, o limite de uma função $f(x)$ à medida que $x$ se aproxima de um valor $c$ é o valor que $f(x)$ parece estar se aproximando. Esse valor é denotado como $\lim_{x \to c} f(x)$.

## Definição Formal
Formalmente, dizemos que o limite de $f(x)$ quando $x$ se aproxima de $c$ é $L$ (escrito como $\lim_{{x \to c}} f(x) = L)$ se, para cada número positivo $\epsilon$, existe um número positivo $\delta$ tal que para todos os $x$:

$$
0 < |x - c| < \delta 
\implies |f(x) - L| < \epsilon
$$

## Exemplos
**[[Função do 1º Grau|Função Linear]]**
	Para $f(x) = 2x + 1$, o limite quando $x$ se aproxima de 3 é:
	$$ \lim_{x \to 3} (2x + 1) = 2.3 + 1 = 7 $$
**[[Função Descontínua#Descontinuidade Removível|Função com Descontinuidade Removível]]**
	Para a função
	$$
	f(x) = \begin{cases}
		\frac {x^2 - 1} {x - 1} & x \ne 1 \\
		2 & x = 1
	\end{cases}
	$$
	Embora $f(x)$ não esteja definida em $x = 1$, podemos encontrar o limite:
	$$
	\lim_{x \to 1} \frac {x^2 - 1} {x - 1}
	= \lim_{x \to 1} (x + 1)
	= 2
	$$
# Exercícios

##### Exercício 1 (UEL)
O valor do limite é
$$\lim_{x->2}(\frac{x - 3}{x + \frac{1}{2}})$$
a) $-5/2$
b) $-3/2$
c) $-1$
d) $-2/3$
e) $-2/5$
###### Resposta
e) $-2/5$

Resolução:
$$
\lim_{x->2}(\frac{x - 3}{x + \frac{1}{2}}) 
= \frac{2-3}{2 + \frac{1}{2}} 
= \frac{-1}{\frac{5}{2}} 
= \frac{-2}{5}
$$

##### Exercício 2 (EFOMM)
Determine o valor do limite
$$\lim_{x->1}(\frac{x-1}{x^2-1})$$
a) 1
b) +$\infty$
c) -$\infty$
d) Zero
e) 0,5
###### Resposta
e) 0,5

Resolução:
Não é possível resolver por substituição de $x$ direto, pois resulta em uma indeterminação.
$$
\frac{1-1}{1^2-1}
= \frac{0}{0}
$$
Então será necessário utilizar a propriedade de identidade algébrica.

$$
a^2 - b^2 = (a+b) . (a-b)
$$
$$
\lim_{x -> 1}(\frac{x - 1}{x^2 - 1})
= \lim_{x -> 1}(\frac{x - 1}{(x + 1) . (x - 1)})
= \lim_{x -> 1}(\frac{1}{x + 1})
= \frac{1}{1 + 1}
= \frac{1}{2}
= 0,5
$$

##### Exercício 3 (EFOMM)
Os valores de A, sabendo que a função abaixo é contínua para todos os valores de x, será
$$
f(x) = \begin{cases}
A^2 x - A & x \ge 3\\
4 & x \lt 3
\end{cases}
$$
a) 1 ou -1/2
b) 1 ou -2
c) 2 ou 4
d) 2 ou 3/4
e) -1 ou 4/3
###### Resposta
e) -1 ou 4/3

Resolução:
$$
f(3)
= \lim_{x\ ->\ 3^+} f
= \lim_{x\ ->\ 3^-} f
$$
$$
\begin{cases}
f(3) & = A^2 . 3 - A \\
\lim_{x\ ->\ 3^+} & = A^2 . 3 - A\\ 
\lim_{x\ ->\ 3^-} & = 4
\end{cases}
$$
Então, $f(3)$ deve ser igual a 4.
$A^2 . 3 - A = 4$
$3A^2 - A = 4$
$3A^2 - A - 4 = 0$

Aplicando Bhaskara:
$a = 3$
$b = -1$
$c = -4$
$$\frac{-b\ \pm \sqrt{b^2\ -\ 4ac}}{2a}$$
$$
x_1 = \frac{-(-1) + \sqrt{(-1)^2\ - 4.3.(-4)}}{2.3}
= \frac{1\ + \sqrt{1 - (-48)}}{6}
= \frac{1 + \sqrt{49}}{6}
= \frac{1\ + 7}{6}
= \frac{8}{6}
= \frac{4}{3}
$$
$$
x_2 = \frac{-(-1) - \sqrt{(-1)^2\ - 4.3.(-4)}}{2.3}
%= \frac{1 - \sqrt{(-1)^2\ - 4.3.(-4)}}{6}
%= \frac{1 - \sqrt{1 - (-48)}}{6}
%= \frac{1 - \sqrt{49}}{6}
= \frac{1 - 7}{6}
= \frac{-6}{6}
= -1
$$
##### Exercício 4 (EFOMM)
Para que a função
$$
f(x) = \begin{cases}
\frac{5x^3 - 10x^2}{x - 2} & x \ne 2 \\
k & x = 2
\end{cases}
$$
Seja contínua, para todo valor de x, qual deverá ser o valor de k?

a) 2
b) 10
c) 20
d) 40
e) 50
###### Resposta
c) 20

Resolução:
$$
\lim_{x\ ->\ 2} f(x)
= \frac{5x^3 - 10x^2}{x-2}
= k
$$
$$
\lim_{x\ ->\ 2}(\frac{5x^3 - 10x^2}{x-2})
= \lim_{x\ ->\ 2}(\frac{5x^2 . (x - 2)}{x-2})
= \lim_{x\ ->\ 2}(5x^2)
= 5.2^2
= 5.4
= 20
$$

##### Exercício 5 (Escola Naval)
Considere $a$ o menor arco no sentido trigonométrico positivo, para o qual a função real $f$, definida por
$$
f(x) = \begin{cases}
\frac{\tan{x} \sqrt{1 + \cos{x}}}{\sin{(2x)}} & x \ne 0 \\
\cos{a} & x = 0
\end{cases}
$$
Seja contínua em $x = 0$. Sendo assim, pode-se dizer que $a$ vale:

a) $\frac{3\pi}{4}$
b) $\frac{\pi}{12}$
c) $\frac{5\pi}{4}$
d) $\frac{\pi}{8}$
e) $\frac{\pi}{4}$
###### Resposta
e) $\frac{\pi}{4}$

Resolução:
$$
\lim_{x\ ->\ 0} f(x)
= \frac{\tan{x}\ .\ \sqrt{1 + \cos{x}}}{\sin{(2x)}}
= \cos{a}
$$
$$
\lim_{x\ ->\ 0} (\frac{\tan{x}\ .\ \sqrt{1 + \cos{x}}}{\sin{2x}})
= \lim_{x\ ->\ 0} (\frac{\frac{\sin{x}}{\cos{x}}\ .\ \sqrt{1 + \cos{x}}}{2 . \sin{x} . \cos{x}})
= \lim_{x\ ->\ 0} (\frac{\frac{\sin{x} . \sqrt{1 + \cos{x}}}{\cos{x}}}{\frac{2 . \sin{x} . \cos{x}}{1}})
$$
$$
= \lim_{x\ ->\ 0} (\frac{\sin{x}\ .\ \sqrt{1 + \cos{x}}}{2 . \sin{x} . \cos^2{x}})
= \lim_{x\ ->\ 0} (\frac{\sqrt{1 + \cos{x}}}{2 \cos^2{x}})
= \frac{\sqrt{1 + \cos{0}}}{2 \cos^2{0}}
= \frac{\sqrt{2}}{2}
= \cos{45º}
= \frac{\pi}{4}
$$

##### Exercício 6 (Escola Naval)
Sendo
$$ k = \lim_{x\ ->\ +\infty} (\frac{x^2 + 5x + 4}{x^2 - 3x + 7})^x $$
Então $\ln{2k} + \log{5}$ vale
a) $(1 - \frac{1}{\ln{10}}) \ln2 + 9$
b) $(1 + \frac{1}{\ln{10}}) \ln2 + 7$
c) $(1 - \frac{1}{\ln{10}}) \ln2 - 9$
d) $(1 + \frac{1}{\ln{10}}) \ln2 + 9$
e) $(1 + \frac{1}{\ln{10}}) \ln2 - 7$
###### Resposta
x) $x$

Resolução:
$$x$$

##### Exercício 7 (UESPI)
Qual o valor do limite
$$ \lim_{x\ ->\ 0} (\frac{\sqrt{x + 25} - 5}{\sqrt{x + 16}{-4}}) $$
a) 0
b) 1/5
c) 2/5
d) 3/5
e) 4/5
###### Resposta
e) $4/5$

Resolução:

Ao substituir diretamente $x$, o resultado é indeterminado.
$$
\lim_{x\ ->\ 0} (\frac {\sqrt{x + 25} - 5} {\sqrt{x + 16} - 4})
= \frac {\sqrt{0 + 25} - 5} {\sqrt{0 + 16} - 4}
= \frac {5 - 5} {4 - 4}
= \frac {0} {0}
$$

Fazendo a racionalização do denominador multiplicando pelo seu conjugado, o resultado continuaria indeterminado, então é necessário também fazer a racionalização pelo numerador.

$$
\lim_{x\ ->\ 0} (\frac {\sqrt{x + 25} - 5} {\sqrt{x + 16} - 4})
= \frac {\sqrt{x + 25} - 5} {\sqrt{x + 16} - 4}
	. \frac {\sqrt{x + 16} + 4} {\sqrt{x + 16} + 4}
	. \frac {\sqrt{x + 25} + 5} {\sqrt{x + 25} + 5}
= \frac {(x + 25 - 25) . (\sqrt{x + 16} + 4)} {(x + 16 - 16) . (\sqrt{x + 25} + 5)}
$$
$$
= \frac {x . \sqrt{x + 16} + 4} {x . \sqrt{x + 25} + 5}
= \frac {\sqrt{x + 16} + 4} {\sqrt{x + 25} + 5}
$$
Agora é possível substituir o x.
$$
\lim_{x\ ->\ 0} (\frac {\sqrt{x + 16} + 4} {\sqrt{x + 25} + 5})
= \frac {\sqrt{0 + 16} + 4} {\sqrt{0 + 25} + 5}
= \frac {4 + 4} {5 + 5}
= \frac {8} {10}
= \frac {4} {5}
$$