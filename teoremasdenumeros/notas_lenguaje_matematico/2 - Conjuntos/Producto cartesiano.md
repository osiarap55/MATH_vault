---
tipo: definición
tags: [definicion, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.4 · pp. 55-59"
aliases: [Producto de conjuntos, Par ordenado, Pares ordenados, n-upla, Terna ordenada, A × B]
---
# Producto cartesiano  $A\times B$

> [!tip] En palabras sencillas
> $A\times B$ es el conjunto de **todas las parejas** $(a,b)$ con $a$ de $A$ y $b$ de $B$. Aquí **el orden sí importa**: $(1,2)\neq(2,1)$. Es lo que hace Descartes con el plano: cada punto es una pareja $(x,y)$.

> [!note] Definición
> - **Par ordenado** $(x,y)$: dos elementos con un orden. $(x,y)=(z,t)\iff x=z\ \text{y}\ y=t$.
> - $$A\times B=\{(x,y)\mid x\in A,\ y\in B\}$$ y $A^2=A\times A$.
> - **$n$-uplas:** $A_1\times\cdots\times A_n=\{(x_1,\dots,x_n)\mid x_i\in A_i\}$; $A^n=A\times\cdots\times A$.

> [!abstract] Propiedades
> 1. $A'\subseteq A$, $B'\subseteq B$ ⇒ $A'\times B'\subseteq A\times B$.
> 2. $(A\cup B)\times C=(A\times C)\cup(B\times C)$ y $A\times(B\cup C)=(A\times B)\cup(A\times C)$.
> 3. $(A\cap B)\times C=(A\times C)\cap(B\times C)$ y $A\times(B\cap C)=(A\times B)\cap(A\times C)$.
> 4. $A\times B=\emptyset\iff A=\emptyset$ o $B=\emptyset$.
> 5. **No es conmutativo:** $A\times B\neq B\times A$ si $A\neq B$ (y ambos no vacíos).
> 6. Si $A$ tiene $m$ elementos y $B$ tiene $n$, $A\times B$ tiene $m\cdot n$.

> [!abstract] Demostración de $A\times(B\cap C)=(A\times B)\cap(A\times C)$ (Ejercicio 2.33)
> $(x,y)\in A\times(B\cap C)\iff x\in A\land(y\in B\land y\in C)\iff(x\in A\land y\in B)\land(x\in A\land y\in C)\iff(x,y)\in(A\times B)\cap(A\times C)$. ∎
> (Usa idempotencia $x\in A\iff x\in A\land x\in A$ y asociativa/conmutativa de $\land$.)

> [!example] Ejemplos
> - $\mathbb R^2=\mathbb R\times\mathbb R$: el plano. $\mathbb R^3$: el espacio.
> - Jugadores $J=\{A,B,C\}$ × premios $P$ (4 premios) = 12 parejas posibles jugador-premio.

> [!failure] Lo que no es
> $\{x,y\}$ no es $(x,y)$: $\{1,2\}=\{2,1\}$ pero $(1,2)\neq(2,1)$; y $(1,1)$ es un par válido mientras que $\{1,1\}=\{1\}$.

## Conexiones
- **Necesitas antes:** [[Conjunto]]
- **Lleva a:** [[Relación binaria]] (una relación es un subconjunto de $A\times B$), [[Aplicación]], [[Operación interna]] ($A\times A\to A$)
- **Se usa en:** [[Números enteros]] (pares de naturales), [[Números racionales]] (pares de enteros), [[Números complejos]] (pares de reales)
