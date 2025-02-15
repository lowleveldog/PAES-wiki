---
title: Propiedades de la potenciación
---

Las propiedades de la [[potenciación]] son igualdades que se pueden aplicar a operaciones de multiplicación o división entre elementos con exponentes.

Las propiedades son las siguientes:
$$
a^b \times a^c = a^{b + c} 
$$
$$
\frac{a^b}{a^c} = a^{b-c}
$$

$$
(a \times b)^c = a^c \times b^c
$$
$$
(\frac{a}{b})^c = \frac{a^c}{b^c}
$$
$$
(a^b)^c = a^{b\times c}
$$
$$
a^{-b} = \frac{1}{a^b}
$$
$$
a^0 = 1, a \neq 0
$$
# Explicación
## Multiplicación de bases iguales con distinto exponente
Usemos como ejemplo el número $4$ como base y los exponentes $2$ y $3$.
$$
4^2 \times 4^3
$$
Como la potenciación de un número usando un exponente entero $n$ se puede describir como ese número multiplicándose a sí mismo $n$ veces, simplemente podemos expandir la operación a esta forma más básica.
$$
\begin{aligned}
(4 \times 4)\times (4\times 4 \times 4) \\
= 4 \times 4 \times 4 \times 4 \times 4
\end{aligned}
$$
Y así podemos ver que la misma operación también se puede describir como el $4$ multiplicándose a sí mismo seis veces, es decir, $2+3$ veces. Resultando en $4^6$. Por lo tanto:
$$
4^2 \times 4^3 = 4^{2+3}= 4^6 = 4096
$$
## División de bases iguales con distinto exponente
Usemos como ejemplo el número $8$ como base y los exponentes $6$ y $4$.
$$
\frac{8^6}{8^4}
$$
Haciendo lo mismo que la vez anterior, podemos descomponer la operación en forma de multiplicación:
$$
\frac{8 \times 8 \times 8 \times 8 \times 8 \times 8}{8 \times 8 \times 8 \times 8}
$$
Al haber factores en común se pueden [[cancelar]].
$$
\frac{\cancel{8 \times 8 \times 8 \times 8 }\times 8 \times 8}{\cancel{8 \times 8 \times 8 \times 8}}
$$
$$
= 8 \times 8
$$
Y como resultado tenemos $8^2$, lo cual es equivalente a usar la propiedad: $8^{6-4}$ . 
## Exponenciación de factores en paréntesis
Usemos como ejemplo los números $3$ y $5$ como base y el exponente $2$.
$$
(3 \times 5) ^2
$$
De nuevo podemos descomponer la potencia en multiplicación:
$$
(3 \times 5) (3 \times 5)
$$
$$
= 3 \times 5 \times 3 \times 5
$$
$$
= 3 \times 3 \times 5 \times 5
$$
Como el tres y el cinco se están multiplicando a sí mismos los podemos transformar a potencias de manera distinta.
$$
3^2 \times 5^2
$$
Por lo tanto, $(3 \times 5)^2 = 3^2 \times 5^2$.

La propiedad se puede aplicar al revés, siendo una **multiplicación de factores con el mismo exponente.** 
## Potencia de una fracción
Usando las fracción $\frac{3}{4}$ y el exponente $2$:
$$
(\frac{3}{4})^2
$$
Descomponiendo:
$$
= \frac{3}{4} \times \frac{3}{4}
$$
Usando la propiedad de la multiplicación de las fracciones, de numerador-numerador y denominador-denominador, nos queda
$$
\frac{3\times 3}{4\times 4}
$$
$$
= \frac{3^2}{4^2}
$$
Por lo tanto, $(\frac{3}{4})^2$ es lo mismo que $\frac{3^2}{4^2}$.
## Potencia de una potencia
Usemos de ejemplo el número 7 de base y los números $2$ y $3$ de exponentes.
$$
(7^2) ^3
$$
Descomponer:
$$
7^2 \times 7 ^2 \times 7^2
$$
Podemos usar la propiedad de potencias con misma base:
$$
7^{2+2+2}
$$
Lo cual es igual a $7{^2\times 3}$. Por lo tanto:
$$
(7^2)^3 = 7^{2\times 3}
$$
Se puede jugar descomponiendo y transformando estas operaciones de cualquier manera que sea permitida y se llegaría a la misma igualdad.

Nótese que $(7^2) ^3$ no es lo mismo que $7^{2^3}$ . En el segundo caso el $3$ es exponente solamente del $2$, y esta operación se computa, por así decirlo, "de arriba hacia abajo", por lo que equivaldría a $7^8$. 
## Exponente negativo
Base $2$, exponente $-3$.
$$
2^{-3}
$$No tendría sentido intuitivamente el multiplicar una base por sí misma una cantidad negativa de veces, por lo que podemos intentar llegar a este valor de manera práctica usando la propiedad de división misma base distinto exponente, haciendo que, con la resta, el exponente se vuelva negativo:
$$
\frac{2^3}{2^{2\times 3}}= \frac{2^3}{2^{6}} = 2^{3-6} = 2^{-3}
$$
Podemos *descomponer* la operación transformada como ya se ha mostrado múltiples veces:
$$
= \frac{2 \times 2 \times 2}{2 \times 2 \times 2 \times 2 \times 2 \times 2}
$$
y cancelar:
$$
\frac{\cancel{2 \times 2 \times 2}}{\cancel{2 \times 2 \times 2 }\times 2 \times 2 \times 2}
$$
$$
= \frac{1}{2 \times 2 \times 2}
$$
Finalmente terminamos con el número $\frac{1}{2^3}$ o $(\frac{1}{2})^3$. Por lo tanto:
$$
2^{-3} = \frac {1}{2^3}.
$$
## Exponente 0
Podemos usar el mismo truco que usamos para el exponente negativo para ver qué pasa con un exponente cero.
$$
\frac{2^3}{2^3} = 2^{3-3} = 2^0
$$
$$
= \frac{\cancel{2\times 2 \times 2}}{\cancel{2\times 2\times 2}} = 1
$$
Por lo tanto resulta que $2^0 = 1$. 

Con cualquier otra base funcionaría, excepto con el cero, que resultaría en $0\over 0$, que es indeterminado, por eso mismo se excluye al cero en la definición del inicio. Aún así, usar la propiedad de división de bases iguales no es un determinante definitivo de que esta operación no puede dar uno, y hay bandos que defienden que si puede, como también funciones o modelos que dejan pasarlo como 1 por conveniencia.  