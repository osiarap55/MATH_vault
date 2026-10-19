---
tipo: definición
tags: [definicion, cardinales]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "§5.3 · pp. 180-182; Def. 5.56 (comentarios)"
aliases: [Conjuntos infinitos, Infinito, Número transfinito, Cardinal infinito]
---
# Conjunto infinito

> [!tip] En palabras sencillas
> Un conjunto es infinito si **no se acaba de contar**. Lo sorprendente: un conjunto infinito puede tener **el mismo tamaño que una parte suya** (los cuadrados perfectos "son tantos como" los naturales).

> [!note] Definición
> $A$ es **infinito** si no es [[Conjunto finito|finito]].
> Caracterización equivalente (comentarios): un cardinal $a$ es infinito si $a+1=a$. En la práctica: **$A$ es infinito $\iff$ es equipotente a una parte propia suya** (definición de Dedekind).

> [!example] Ejemplos
> - $\mathbb N$ es infinito (no está acotado; o: $s:\mathbb N\to\mathbb N\setminus\{0\}$ es biyectiva).
> - Todo subconjunto no acotado de $\mathbb N$ es infinito.
> - $\{0,1,4,9,\dots\}\simeq\mathbb N$ con $n\mapsto n^2$: ¡tantos cuadrados como naturales!

> [!important] Hay infinitos de distintos tamaños
> Por el [[Teorema de Cantor]] (Teorema 5.26), $A$ y $\mathcal P(A)$ nunca son equipotentes. Así se obtiene una cadena sin fin:
> $$\operatorname{card}\mathbb N<\operatorname{card}\mathcal P(\mathbb N)<\operatorname{card}\mathcal P(\mathcal P(\mathbb N))<\cdots$$
> Los cardinales infinitos se llaman **números transfinitos**. El menor es $\aleph_0$ ([[Conjunto numerable]]).

> [!warning] Errores típicos
> - Pensar que "parte propia ⇒ menos elementos" también en infinitos. Solo es cierto para finitos (Prop. 5.11).
> - Pensar que todos los infinitos son iguales: $\mathbb R$ es "más grande" que $\mathbb N$.

## Conexiones
- **Necesitas antes:** [[Conjunto finito]], [[Conjuntos equipotentes]]
- **Lleva a:** [[Conjunto numerable]], [[Teorema de Cantor]], [[Cardinal]]
