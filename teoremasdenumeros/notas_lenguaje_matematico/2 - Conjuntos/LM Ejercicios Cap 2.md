---
tipo: ejercicios
tags: [ejercicios, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "Ejercicios propuestos · pp. 70-73"
---
# Ejercicios · Cap 2 · Conjuntos

> [!tip] Cómo usar esta nota
> Intenta cada ejercicio en papel antes de desplegar la solución. Entre paréntesis, el número del ejercicio en el libro.

## Ejercicio 1 · Pasar a cuantificadores
> [!question] Enunciado (1)
> Escribe con cuantificadores:
> a) Existen números naturales que son múltiplos de cinco y cuyo último dígito no es cinco.
> b) Una función polinómica es continua, derivable e integrable.

> [!success]- Solución
> a) $(\exists x\in\mathbb N)\,(5\mid x\ \land\ x\not\equiv 5 \pmod{10})$. Verdadera: $x=10$.
> b) Hay un "para todo" escondido. Con $F$ = funciones reales: $(\forall f\in F)\,[\,f\text{ polinómica}\to(f\text{ continua}\land f\text{ derivable}\land f\text{ integrable})\,]$.

Repasa: [[Cuantificadores]], [[Predicado]]

## Ejercicio 2 · Cuantificadores y conectores
> [!question] Enunciado (2)
> ¿Son ciertas?
> a) $\forall x P_x\land\forall x Q_x\iff\forall x(P_x\land Q_x)$
> b) $\exists x P_x\lor\exists x Q_x\iff\exists x(P_x\lor Q_x)$
> c) $\forall x P_x\lor\forall x Q_x\Rightarrow\forall x(P_x\lor Q_x)$
> d) $\exists x(P_x\land Q_x)\Rightarrow\exists x P_x\land\exists x Q_x$
> e) Prueba que los recíprocos de c) y d) son falsos.

> [!success]- Solución
> a) y b) **Sí**: $\forall$ "se reparte" sobre $\land$ y $\exists$ sobre $\lor$ (piensa en $\forall$ como un "y" gigante y $\exists$ como un "o" gigante).
> c) **Sí**: si todos cumplen $P$, cada uno cumple $P\lor Q$.
> d) **Sí**: el mismo $x$ que cumple ambas sirve de testigo para cada una.
> e) Contraejemplo para los dos: $U=\{1,2\}$, $P$ cierto solo en 1, $Q$ cierto solo en 2.
> - $\forall x(P_x\lor Q_x)$ es verdadera, pero $\forall xP_x\lor\forall xQ_x$ es falsa.
> - $\exists xP_x\land\exists xQ_x$ es verdadera, pero $\exists x(P_x\land Q_x)$ es falsa.
>
> **Moraleja:** $\forall$ no se reparte sobre $\lor$, ni $\exists$ sobre $\land$.

Repasa: [[Cuantificadores]]

## Ejercicio 3 · Evaluar en un universo finito
> [!question] Enunciado (3 y 20)
> a) $U=\{1,2,3\}$; $P$ cierto en $\{1,2\}$, $Q$ en $\{1,2\}$, $R$ en $\{2,3\}$. Evalúa $\forall x(P_x\to Q_x)$, $\neg\forall x(\neg P_x\lor\neg R_x)$, $\forall x(\neg R_x\to P_x)$.
> b) $U=\{1,2,3,4,5\}$. ¿Dónde son verdaderos los predicados $\exists x\,(x+2y<7)$ (en $y$) y $\forall y\,(x+2y<7)$ (en $x$)?

> [!success]- Solución
> a)
> - $\forall x(P_x\to Q_x)$: el conjunto de $P$ está contenido en el de $Q$ → **verdadera**.
> - $\neg\forall x(\neg P_x\lor\neg R_x)\iff\exists x(P_x\land R_x)$: $x=2$ → **verdadera**.
> - $\forall x(\neg R_x\to P_x)$: $\neg R$ solo en $x=1$, y $P_1$ es cierta → **verdadera**.
>
> b)
> - $\exists x(x+2y<7)$: lo más fácil es $x=1$: $1+2y<7\iff y<3$. Verdadero en $\{1,2\}$.
> - $\forall y(x+2y<7)$: debe valer para $y=5$: $x+10<7$, imposible. Verdadero en $\emptyset$.

## Ejercicio 4 · Dominio de una función
> [!question] Enunciado (Ejercicio 2.23 del texto)
> Halla el dominio de $f(x)=\sqrt{\dfrac{x^2-4}{x-1}}$.

> [!success]- Solución
> Hay que resolver $\frac{x^2-4}{x-1}\ge 0$. Un cociente es $\ge0$ si (num $\ge0$ **y** den $>0$) **o** (num $\le0$ **y** den $<0$):
> - $\{x^2-4\ge0\}\cap\{x>1\}=[(-\infty,-2]\cup[2,\infty)]\cap(1,\infty)=[2,\infty)$
> - $\{x^2-4\le0\}\cap\{x<1\}=[-2,2]\cap(-\infty,1)=[-2,1)$
>
> Dominio: $[-2,1)\cup[2,\infty)$. Cada "y" es una intersección y el "o" una unión.

Repasa: [[Unión e intersección]]

## Ejercicio 5 · Negar con cuantificadores
> [!question] Enunciado (21)
> Niega: a) $\forall x\,(P_x\to\exists y\,R_{xy})$  b) $\forall x\,\exists y\,(R_{yx}\lor R_{xy})$

> [!success]- Solución
> a) $\exists x\,\neg(P_x\to\exists y R_{xy})\iff\exists x\,(P_x\land\neg\exists yR_{xy})\iff\exists x\,(P_x\land\forall y\,\neg R_{xy})$.
> b) $\exists x\,\forall y\,\neg(R_{yx}\lor R_{xy})\iff\exists x\,\forall y\,(\neg R_{yx}\land\neg R_{xy})$.
>
> Receta: cambia $\forall\leftrightarrow\exists$, y niega lo de dentro con De Morgan y $\neg(p\to q)\iff p\land\neg q$.

Repasa: [[Cuantificadores]], [[Leyes del condicional]]

## Ejercicio 6 · Demostrar inclusiones
> [!question] Enunciado (9)
> Demuestra: a) $A\subseteq B\Rightarrow\bar B\subseteq\bar A$  b) $A\subseteq B$, $C\subseteq D\Rightarrow A\cup C\subseteq B\cup D$

> [!success]- Solución
> a) Sea $x\in\bar B$, es decir, $x\notin B$. Si fuera $x\in A$, como $A\subseteq B$, sería $x\in B$: contradicción. Luego $x\notin A$, o sea $x\in\bar A$. (Es el **contrarrecíproco** de $x\in A\to x\in B$.)
> b) Sea $x\in A\cup C$. Si $x\in A$, entonces $x\in B\subseteq B\cup D$. Si $x\in C$, entonces $x\in D\subseteq B\cup D$. En los dos casos $x\in B\cup D$.

Repasa: [[Inclusión de conjuntos]], [[Recíproco y contrarrecíproco]]

## Ejercicio 7 · Simplificar y deducir inclusiones
> [!question] Enunciado (7 y 8)
> a) Si $A\cup B\subseteq A\cup C$, ¿es $B\subseteq C$?
> b) Si $A\cap B\subseteq A\cap C$, ¿es $B\subseteq C$?
> c) Si se cumplen las dos, ¿es $B\subseteq C$?
> d) Simplifica $A\cap(B\cup A)$ y $(A\cup B)\cap(A\cup\bar B)$.

> [!success]- Solución
> a) **No.** $A=B=\{1\}$, $C=\emptyset$: $A\cup B=\{1\}\subseteq\{1\}=A\cup C$, pero $B\not\subseteq C$.
> b) **No.** $A=\emptyset$, $B=\{1\}$, $C=\emptyset$: ambas intersecciones son vacías.
> c) **Sí.** Sea $x\in B$. Caso $x\in A$: $x\in A\cap B\subseteq A\cap C$, luego $x\in C$. Caso $x\notin A$: $x\in A\cup B\subseteq A\cup C$, y como $x\notin A$, $x\in C$.
> d) $A\cap(B\cup A)=A$ (absorción). $(A\cup B)\cap(A\cup\bar B)=A\cup(B\cap\bar B)=A\cup\emptyset=A$ (distributiva).

Repasa: [[Álgebra de conjuntos]]

## Ejercicio 8 · Igualdades de conjuntos
> [!question] Enunciado (10)
> Demuestra: a) $(A\cup B)\setminus C=(A\setminus C)\cup(B\setminus C)$  b) $(A\setminus B)\setminus C=A\setminus(B\cup C)$  c) $A\setminus(B\setminus C)=(A\setminus B)\cup(A\cap C)$

> [!success]- Solución
> Usa $X\setminus Y=X\cap\bar Y$ y las leyes:
> a) $(A\cup B)\cap\bar C=(A\cap\bar C)\cup(B\cap\bar C)$ (distributiva).
> b) $(A\cap\bar B)\cap\bar C=A\cap(\bar B\cap\bar C)=A\cap\overline{B\cup C}$ (De Morgan).
> c) $A\cap\overline{B\cap\bar C}=A\cap(\bar B\cup C)=(A\cap\bar B)\cup(A\cap C)$ (De Morgan + distributiva).

Repasa: [[Diferencia y complementario]], [[Álgebra de conjuntos]]

## Ejercicio 9 · Partes de un conjunto
> [!question] Enunciado (Ejercicio 2.13 del texto)
> Si $A=\{a,b\}$, ¿cuántos elementos tiene $\mathcal P(\mathcal P(A))$? Escribe tres de ellos.

> [!success]- Solución
> $\mathcal P(A)=\{\emptyset,\{a\},\{b\},A\}$ tiene 4 elementos, así que $\mathcal P(\mathcal P(A))$ tiene $2^4=16$.
> Por ejemplo: $\emptyset$, $\{\emptyset\}$, $\{\{a\},A\}$. (¡Cuidado con las llaves!)

Repasa: [[Conjunto de las partes]]

## Ejercicio 10 · Uniones e intersecciones infinitas
> [!question] Enunciado (13 y 14)
> a) $B_n=[n,n+1]$. Halla $B_4\cup B_5$, $B_5\cap B_6$ y $\bigcup_{n\in\mathbb N}B_n$.
> b) Para $n\ge1$: $B_n=[0,\frac1n)$, $C_n=(0,\frac1n)$. Halla $\bigcup$ y $\bigcap$ de cada familia.

> [!success]- Solución
> a) $B_4\cup B_5=[4,6]$; $B_5\cap B_6=\{6\}$; $\bigcup B_n=[0,\infty)$.
> b) $\bigcup B_n=[0,1)$, $\bigcap B_n=\{0\}$. $\bigcup C_n=(0,1)$, $\bigcap C_n=\emptyset$.
> Para la intersección de $C_n$: si $x>0$, por la [[Propiedad arquimediana]] hay $n$ con $\frac1n<x$, así que $x\notin C_n$.

Repasa: [[Familias de conjuntos]]

## Ejercicio 11 · Relaciones y composición
> [!question] Enunciado (inspirado en el 24)
> $A=\{1,2,3\}$, $B=\{a,b,c\}$, $C=\{\alpha,\beta,\gamma,\delta\}$.
> $\mathcal R=\{(1,a),(1,b),(2,b),(3,c)\}\subseteq A\times B$, $\ \mathcal S=\{(a,\alpha),(a,\beta),(b,\beta),(b,\delta),(c,\gamma)\}\subseteq B\times C$.
> Halla $\mathcal R^{-1}$, $\mathcal R(1)$, $\mathcal S^{-1}(\beta)$ y $\mathcal S\circ\mathcal R$.

> [!success]- Solución
> - $\mathcal R^{-1}=\{(a,1),(b,1),(b,2),(c,3)\}$.
> - $\mathcal R(1)=\{a,b\}$; $\mathcal S^{-1}(\beta)=\{a,b\}$.
> - $\mathcal S\circ\mathcal R$: sigue las flechas $A\to B\to C$.
>   $1\to a\to\alpha,\beta$; $1\to b\to\beta,\delta$; $2\to b\to\beta,\delta$; $3\to c\to\gamma$.
>   $\mathcal S\circ\mathcal R=\{(1,\alpha),(1,\beta),(1,\delta),(2,\beta),(2,\delta),(3,\gamma)\}$.

Repasa: [[Relación binaria]]
