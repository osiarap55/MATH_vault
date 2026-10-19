---
tipo: teorema
tags: [definicion, teorema, algebra, anillos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "§4.3 · pp. 136-137; Prop. 4.24"
aliases: [Subanillos, Criterio de subanillo]
---
# Subanillo

> [!note] Definición
> $\emptyset\neq H\subseteq A$ es **subanillo** de $(A,+,\cdot)$ si $(H,+,\cdot)$ es un anillo. Si $A$ es unitario, se exige además $1\in H$.

> [!important] Proposición 4.24 (criterio)
> $H\neq\emptyset$ es subanillo $\iff$ para todo $a,b\in H$:
> 1. $a-b\in H$ (subgrupo aditivo);
> 2. $ab\in H$ (producto interno);
> 3. si $A$ es unitario, $1\in H$.

> [!example] Ejemplos
> - $\mathbb Z\subseteq\mathbb Q\subseteq\mathbb R\subseteq\mathbb C$.
> - $\mathbb Z[\sqrt2]\subseteq\mathbb R$: $(a+b\sqrt2)(a'+b'\sqrt2)=(aa'+2bb')+(ab'+a'b)\sqrt2$.
> - $n\mathbb Z$ ($n\ge2$) **no** es subanillo de $\mathbb Z$ porque $1\notin n\mathbb Z$, aunque sí es un anillo (sin unidad) y un [[Ideal]].
> - La intersección de subanillos es un subanillo.

## Conexiones
- **Necesitas antes:** [[Anillo]], [[Subgrupo]]
- **Comparar con:** [[Ideal]]
