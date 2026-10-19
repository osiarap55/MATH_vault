---
tipo: definición
tags: [definicion, cardinales]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.63-3.64 · pp. 109-110; Comentarios cap. 3 · pp. 113-114; cap. 4 y 5"
aliases: [Número cardinal, Cardinales, card, Aleph cero, Potencia del continuo, Hipótesis del continuo, Orden entre cardinales]
---
# Cardinal (número cardinal)

> [!tip] En palabras sencillas
> El cardinal de $A$ es su "**tamaño**": lo que tiene en común con todos los conjuntos que se pueden emparejar con él. Para conjuntos finitos es simplemente el número de elementos.

> [!note] Definición
> $\operatorname{card}(A)$ es la colección de todos los conjuntos [[Conjuntos equipotentes|equipotentes]] a $A$.
> - $\operatorname{card}(A)=0\iff A=\emptyset$.
> - $\operatorname{card}(A)=n\iff A\simeq\{1,\dots,n\}$ ("$A$ tiene $n$ elementos").
> - $\aleph_0=\operatorname{card}(\mathbb N)$ (**numerable**). $\mathfrak c=\operatorname{card}(\mathbb R)$ (**potencia del continuo**).

> [!important] Contar aplicaciones entre conjuntos finitos
> Si $\operatorname{card}A=n$ y $\operatorname{card}B=m$:
> | Tipo | Cuántas | Existen si… |
> |---|---|---|
> | Todas | $m^n$ (variaciones con repetición) | siempre |
> | Inyectivas | $m(m-1)\cdots(m-n+1)$ | $n\le m$ |
> | Biyectivas | $n!$ (permutaciones) | $n=m$ |
> | Sobreyectivas | — | $n\ge m$ |
> De ahí la notación $B^A$ para $\mathcal F(A,B)$: tiene $m^n$ elementos.

> [!important] Orden entre cardinales (comentarios)
> $\operatorname{card}A\le\operatorname{card}B$ si existe una **inyección** $A\to B$. Es:
> - reflexivo y transitivo (composición de inyectivas);
> - **antisimétrico** por el [[Teorema de Cantor-Bernstein]];
> - **total** (dos cardinales siempre se pueden comparar), resultado equivalente al [[Axioma de elección]].
>
> Además $\aleph_0<\mathfrak c$ y $\operatorname{card}A<\operatorname{card}\mathcal P(A)$ ([[Teorema de Cantor]]).

> [!note] Hipótesis del continuo (HC)
> ¿Hay algún conjunto de tamaño estrictamente entre $\mathbb N$ y $\mathbb R$? La HC dice que **no** ($\aleph_1=\mathfrak c$). Gödel y Cohen probaron que **no se puede demostrar ni refutar** en ZFC: es **indecidible**.

## Conexiones
- **Necesitas antes:** [[Conjuntos equipotentes]], [[Aplicación inyectiva]]
- **Lleva a:** [[Conjunto finito]], [[Conjunto infinito]], [[Conjunto numerable]], [[Suma y producto de cardinales]]
