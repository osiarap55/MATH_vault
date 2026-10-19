---
tipo: teorema
tags: [teorema, conjuntos, fundamentos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "Comentarios cap. 2 · pp. 66-69"
aliases: [Paradoja del barbero, Paradoja de Cantor, Conjunto de todos los conjuntos]
---
# Paradoja de Russell

> [!tip] En palabras sencillas
> Si aceptas que **cualquier propiedad** define un conjunto, llegas a contradicciones. Por eso hizo falta **axiomatizar** la teoría de conjuntos.

> [!important] La paradoja
> Sea $M=\{X\mid X\notin X\}$ (los conjuntos que no se contienen a sí mismos). ¿Es $M\in M$?
> - Si $M\in M$, por definición de $M$, $M\notin M$.
> - Si $M\notin M$, entonces cumple la condición, luego $M\in M$.
>
> En ambos casos, **contradicción**. Conclusión: $M$ **no puede ser un conjunto**.

> [!example] Versión popular: el barbero
> En un pueblo, el barbero afeita a todos los que no se afeitan a sí mismos (y solo a ellos). ¿Quién afeita al barbero?

> [!note] Paradoja de Cantor
> Si existiera el conjunto $C$ de **todos** los conjuntos, $\mathcal P(C)$ sería un conjunto y por tanto $\mathcal P(C)\subseteq C$. Pero el [[Teorema de Cantor]] dice que $\mathcal P(C)$ es "estrictamente más grande" que $C$. Contradicción.
> Por eso: **la colección de todos los conjuntos no es un conjunto.**

> [!abstract] Cantor vs. la solución moderna
> Cantor aceptaba implícitamente: (1) toda propiedad define un conjunto; (2) un conjunto es un objeto que puede pertenecer a otro; (3) un conjunto está determinado por sus elementos.
> El fallo está en (1). La solución es la **axiomática** ([[Axiomas de Zermelo-Fraenkel]]): solo puedes formar $\{x\in A\mid P(x)\}$ **dentro de un conjunto $A$ ya existente** (axioma de especificación).

## Conexiones
- **Necesitas antes:** [[Conjunto]], [[Reducción al absurdo]]
- **Lleva a:** [[Axiomas de Zermelo-Fraenkel]], [[Sistema axiomático]]
- **Mismo truco diagonal:** [[Teorema de Cantor]]
