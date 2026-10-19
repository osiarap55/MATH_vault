---
tipo: definición
tags: [definicion, teorema, orden, naturales]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "§3.3 · p. 89; cap. 5"
aliases: [Conjunto bien ordenado, Principio de buena ordenación, Buena ordenación, Teorema de buena ordenación]
---
# Buen orden

> [!tip] En palabras sencillas
> Un conjunto está **bien ordenado** si **cualquier** trozo no vacío suyo tiene un "primero". $\mathbb N$ lo cumple; $\mathbb Z$, $\mathbb Q$ y $\mathbb R$ (con el orden usual) no.

> [!note] Definición
> $(U,\preceq)$ está **bien ordenado** si todo subconjunto no vacío de $U$ tiene **mínimo** (llamado su *primer elemento*).

> [!important] Principio de buena ordenación de $\mathbb N$
> **Todo subconjunto no vacío de $\mathbb N$ tiene mínimo.**
> Es equivalente al [[Principio de inducción]].

> [!abstract] Por qué equivale a la inducción (idea)
> - **Inducción ⇒ buen orden:** si $A\subseteq\mathbb N$ no tuviera mínimo, demuestra por inducción (completa) que "$0,1,\dots,n\notin A$" para todo $n$. Entonces $A=\emptyset$.
> - **Buen orden ⇒ inducción:** si $P(0)$ y $P(n)\Rightarrow P(n+1)$ pero $P$ falla en algún sitio, toma el **mínimo** $m$ donde falla. $m\neq0$ y $P(m-1)$ es cierta, luego $P(m)$ también. Contradicción.

> [!example] Ejemplos y contraejemplos
> - ✓ $\mathbb N$, cualquier subconjunto de $\mathbb N$, $\{1,2,\dots,n\}$.
> - ✗ $\mathbb Z$: el propio $\mathbb Z$ no tiene mínimo.
> - ✗ $[0,1]\subseteq\mathbb R$: tiene mínimo, pero su subconjunto $(0,1]$ no.

> [!important] Teorema de buena ordenación (Zermelo)
> **Todo conjunto** se puede bien ordenar (con algún orden, no el usual). Es equivalente al [[Axioma de elección]].

## Conexiones
- **Necesitas antes:** [[Máximo y mínimo]]
- **Equivale a:** [[Principio de inducción]]
- **Se usa en:** [[División euclídea]] (el resto es el mínimo de un conjunto), [[Máximo común divisor]] (Bézout: el mcd es el menor positivo de la forma $ax+by$)
