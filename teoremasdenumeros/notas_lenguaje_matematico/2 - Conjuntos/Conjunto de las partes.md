---
tipo: definición
tags: [definicion, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.1 · pp. 44-45"
aliases: [Partes de un conjunto, Conjunto potencia, P(A), Conjunto de partes]
---
# Conjunto de las partes  $\mathcal P(A)$

> [!tip] En palabras sencillas
> $\mathcal P(A)$ es el conjunto cuyos elementos son **todos los subconjuntos de $A$**. Es "un conjunto de conjuntos".

> [!note] Definición
> $$\mathcal P(A)=\{B\mid B\subseteq A\}$$
> Siempre $\emptyset\in\mathcal P(A)$ y $A\in\mathcal P(A)$. Por eso $\mathcal P(\emptyset)=\{\emptyset\}\neq\emptyset$.

> [!example] Ejemplos
> - $A=\{a,b\}$: $\mathcal P(A)=\{\emptyset,\{a\},\{b\},\{a,b\}\}$ (4 elementos).
> - $A=\{a,b,c,d\}$: 16 subconjuntos (1 vacío, 4 de un elemento, 6 de dos, 4 de tres, 1 el total).

> [!important] Proposición: si $A$ tiene $n$ elementos, $\mathcal P(A)$ tiene $2^n$
> **Idea:** para formar un subconjunto decides, para cada elemento, si entra o no: $2\cdot2\cdots2=2^n$ opciones.
>
> **Demostración por [[Principio de inducción|inducción]]** (Ejercicio 2.14):
> 1. **Base:** $n=0$: $\mathcal P(\emptyset)=\{\emptyset\}$ tiene $1=2^0$ elemento.
> 2. **Paso:** sea $A$ con $n$ elementos, $a\in A$, y $B=A\setminus\{a\}$ ($n-1$ elementos, por hipótesis $2^{n-1}$ subconjuntos).
> 3. Los subconjuntos de $A$ se parten en dos grupos: los que **no** contienen a $a$ (son exactamente los de $B$: $2^{n-1}$) y los que **sí** (cada uno es $S\cup\{a\}$ con $S\subseteq B$: otros $2^{n-1}$).
> 4. Total: $2^{n-1}+2^{n-1}=2^n$. ∎

> [!warning] Errores típicos
> - Olvidar $\emptyset$ o el propio $A$ al listar los subconjuntos.
> - Confundir $a\in A$ con $\{a\}\in\mathcal P(A)$: los elementos de $\mathcal P(A)$ son **conjuntos**.

## Conexiones
- **Necesitas antes:** [[Inclusión de conjuntos]], [[Principio de inducción]]
- **Lleva a:** [[Álgebra de conjuntos]] (se trabaja dentro de $\mathcal P(U)$), [[Teorema de Cantor]] ($A$ siempre tiene "menos" elementos que $\mathcal P(A)$), [[Número combinatorio]]
- **Relacionado:** [[Paradoja de Russell]] (la paradoja de Cantor usa $\mathcal P$)
