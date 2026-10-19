---
tipo: definición
tags: [definicion, orden]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.25 y Prop. 3.26 · pp. 87-88"
aliases: [Máximo, Mínimo, Elemento máximo, Elemento mínimo, Primer elemento]
---
# Máximo y mínimo

> [!tip] En palabras sencillas
> El **máximo** de $A$ es una cota superior **que además está dentro de $A$**: el "más grande de todos". El **mínimo**, igual por abajo.

> [!note] Definición
> - $M=\max(A)$ si $M\in A$ y $\forall x\in A:\ x\preceq M$.
> - $m=\min(A)$ si $m\in A$ y $\forall x\in A:\ m\preceq x$.

> [!important] Proposición 3.26 (unicidad)
> Si existe el máximo (o el mínimo) de $A$, es **único**.

> [!abstract] Demostración (idea)
> Si $M$ y $M'$ fueran máximos: $M'\preceq M$ (porque $M$ es máximo y $M'\in A$) y $M\preceq M'$ (al revés). Por la **antisimétrica**, $M=M'$. ∎

> [!example] Ejemplos
> - $[0,1]$: $\max=1$, $\min=0$. $(0,1)$: **ni máximo ni mínimo**.
> - $\mathbb N$: $\min=0$, sin máximo.
> - En $(\mathbb N^*,\mid)$, $A=\{2,4,6\}$: $\min=2$ (2 divide a todos), **no hay máximo** (ni 4 ni 6 son múltiplos de todos).

> [!warning] Errores típicos
> - Creer que todo conjunto acotado tiene máximo: $(0,1)$ no lo tiene. Lo que sí puede tener es **supremo** ([[Supremo e ínfimo]]).
> - Confundir máximo con **maximal** en órdenes parciales ([[Elementos maximales y minimales]]).

## Conexiones
- **Necesitas antes:** [[Cotas de un conjunto]]
- **Lleva a:** [[Supremo e ínfimo]], [[Buen orden]], [[Elementos maximales y minimales]]
