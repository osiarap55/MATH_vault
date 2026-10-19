---
tipo: definición
tags: [definicion, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.2 · pp. 45-50"
aliases: [Unión, Intersección, Unión de conjuntos, Intersección de conjuntos, Conjuntos disjuntos, Disjuntos, ∪, ∩]
---
# Unión e intersección

> [!tip] En palabras sencillas
> - **Unión** $A\cup B$: juntar todo lo que hay en $A$ **o** en $B$.
> - **Intersección** $A\cap B$: quedarse con lo que está en $A$ **y** en $B$ a la vez.

> [!note] Definición
> $$A\cup B=\{x\mid x\in A\lor x\in B\}\qquad\qquad A\cap B=\{x\mid x\in A\land x\in B\}$$
> Si $A=\{x\mid P_x\}$ y $B=\{x\mid Q_x\}$: $A\cup B=\{x\mid P_x\lor Q_x\}$ y $A\cap B=\{x\mid P_x\land Q_x\}$.
> $A$ y $B$ son **disjuntos** si $A\cap B=\emptyset$.

> [!abstract] Propiedades (se deducen de las de $\lor$ y $\land$)
> | Unión | Intersección |
> |---|---|
> | $A\subseteq A\cup B$, $B\subseteq A\cup B$ | $A\cap B\subseteq A$, $A\cap B\subseteq B$ |
> | Conmutativa, asociativa | Conmutativa, asociativa |
> | $A\cup\emptyset=A$ | $A\cap\emptyset=\emptyset$ |
> | $A\cup A=A$ | $A\cap A=A$ |
> | $A\cup B=B\iff A\subseteq B$ | $A\cap B=A\iff A\subseteq B$ |
>
> **Distributivas:** $A\cap(B\cup C)=(A\cap B)\cup(A\cap C)$ y $A\cup(B\cap C)=(A\cup B)\cap(A\cup C)$.

> [!abstract] Demostración de $A\cup B=B\iff A\subseteq B$ (Ejercicio 2.18)
> - **(⇒)** Si $x\in A$, entonces $x\in A\cup B=B$. Luego $A\subseteq B$.
> - **(⇐)** $B\subseteq A\cup B$ siempre. Para la otra inclusión: si $x\in A\cup B$, o $x\in B$ (bien), o $x\in A\subseteq B$ (bien). ∎

> [!example] Ejemplos
> - $\{x\in\mathbb N\mid 2\mid x\}\cap\{x\in\mathbb N\mid 3\mid x\}=\{x\in\mathbb N\mid 6\mid x\}$.
> - Dominio de $\sqrt{x^2-1}$: $\{x\mid x^2\ge 1\}=(-\infty,-1]\cup[1,\infty)$.
> - $\{(x,y)\mid x^2-y^2=0\}$ = recta $x-y=0$ $\cup$ recta $x+y=0$ (porque $ab=0\iff a=0\lor b=0$).
> - Dos planos paralelos $2x+3y-5z=-2$ y $2x+3y-5z=-7$ son disjuntos (sistema incompatible).

> [!warning] Errores típicos
> - Pensar que $A\cup B$ "duplica" los elementos comunes: un conjunto no tiene repeticiones.
> - Resolver inecuaciones con productos/cocientes y olvidar alguno de los casos de signo (cada caso es una intersección y luego se unen).

## Conexiones
- **Necesitas antes:** [[Conjunto]], [[Disyunción]], [[Conjunción]]
- **Lleva a:** [[Diferencia y complementario]], [[Familias de conjuntos]], [[Álgebra de conjuntos]], [[Partición de un conjunto]]
