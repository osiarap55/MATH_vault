---
tipo: definición
tags: [definicion, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.1 · p. 44; §2.2 · pp. 52-53"
aliases: [Diferencia de conjuntos, Complementario, Complemento, A menos B, A \ B]
---
# Diferencia y complementario

> [!tip] En palabras sencillas
> - $A\setminus B$: lo que está en $A$ **pero no** en $B$ ("$A$ menos $B$").
> - $\bar A$ (o $A^c$, $A'$): todo lo del universo $U$ que **no** está en $A$.

> [!note] Definición
> $$A\setminus B=\{x\mid x\in A\land x\notin B\}\qquad\qquad \bar A=U\setminus A=\{x\in U\mid x\notin A\}$$
> Si $A=\{x\in U\mid P_x\}$, entonces $\bar A=\{x\in U\mid\neg P_x\}$.

> [!important] Propiedades clave
> - $A\setminus B=A\setminus(A\cap B)$
> - $A\setminus B=A\cap\bar B$ ← convierte diferencias en intersecciones
> - $U\setminus B=\bar B$, $\ \bar{\bar A}=A$, $\ \bar U=\emptyset$, $\ \bar\emptyset=U$
> - [[Álgebra de conjuntos|De Morgan]]: $\overline{A\cup B}=\bar A\cap\bar B$, $\ \overline{A\cap B}=\bar A\cup\bar B$

> [!abstract] Demostración de $A\setminus B=A\cap\bar B$ (Ejercicio 2.26) · doble inclusión
> - $x\in A\setminus B\iff x\in A\land x\notin B\iff x\in A\land x\in\bar B\iff x\in A\cap\bar B$.
> Cada paso es una definición, así que las dos inclusiones salen a la vez. ∎

> [!example] Ejemplos
> - $U=\{a,b,c,d,1,\dots,6\}$, $A=\{a,b,c,d\}$ ⇒ $\bar A=\{1,\dots,6\}$.
> - $\mathbb N^*=\mathbb N\setminus\{0\}$, $\mathbb R^*=\mathbb R\setminus\{0\}$.
> - En $\mathbb N^*$, el complementario de los pares es el conjunto de los impares.

> [!warning] Errores típicos
> - El complementario **depende del universo**: el complementario de los pares es "los impares" en $\mathbb N$, pero en $\mathbb R$ incluiría $\pi$.
> - $A\setminus B\neq B\setminus A$ en general (no es conmutativa).

## Conexiones
- **Necesitas antes:** [[Unión e intersección]], [[Negación]]
- **Lleva a:** [[Diferencia simétrica]], [[Álgebra de conjuntos]]
