---
tipo: definición
tags: [definicion, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.2 · pp. 50-52"
aliases: [Familia de conjuntos, Unión de una familia, Intersección de una familia, Conjunto de índices, Intervalos encajados]
---
# Familias de conjuntos

> [!tip] En palabras sencillas
> A veces no unes dos conjuntos sino **muchos** (incluso infinitos): uno por cada índice $i$. La unión es "estar en **alguno**" y la intersección "estar en **todos**".

> [!note] Definición
> Una **familia** es $\mathcal F=\{F_i\mid i\in I\}$, donde $I\neq\emptyset$ es el **conjunto de índices**.
> $$\bigcup_{i\in I}F_i=\{x\mid\exists i\in I,\ x\in F_i\}\qquad\qquad\bigcap_{i\in I}F_i=\{x\mid\forall i\in I,\ x\in F_i\}$$
> Fíjate: **unión ↔ $\exists$**, **intersección ↔ $\forall$** ([[Cuantificadores]]).

> [!example] Intervalos encajados (Ejercicio 2.24)
> Sea $I_n=[a-\tfrac1n,a+\tfrac1n]$, $n\ge1$. Entonces
> $$\bigcap_{n\ge1}I_n=\{a\}\qquad\qquad\bigcup_{n\ge1}I_n=[a-1,a+1].$$
> **Idea de la intersección:** $a$ está en todos. Si $b\neq a$ estuviera en todos, toma $n$ con $\frac1n<|b-a|$ ([[Propiedad arquimediana]]): entonces $b\notin I_n$. Contradicción.
> **Unión:** los intervalos van encogiendo, $I_1\supseteq I_2\supseteq\cdots$, así que la unión es el mayor, $I_1$.

> [!example] Más ejemplos ($n\ge1$)
> | Familia | $\bigcup$ | $\bigcap$ |
> |---|---|---|
> | $[0,\frac1n]$ | $[0,1]$ | $\{0\}$ |
> | $(0,\frac1n)$ | $(0,1)$ | $\emptyset$ ← ¡vacía! |
> | $(-\frac1n,\frac1n)$ | $(-1,1)$ | $\{0\}$ |

> [!warning] Errores típicos
> - Pensar que una intersección infinita de conjuntos no vacíos encajados es no vacía. $\bigcap(0,\frac1n)=\emptyset$.
> - Las leyes de De Morgan y distributivas valen también aquí: $\overline{\bigcup F_i}=\bigcap\overline{F_i}$, $A\cap\bigcup F_i=\bigcup(A\cap F_i)$.

## Conexiones
- **Necesitas antes:** [[Unión e intersección]], [[Cuantificadores]]
- **Se usa en:** [[Partición de un conjunto]], [[Intervalos]], [[Propiedad arquimediana]]
- **Practica:** [[LM Ejercicios Cap 2#Ejercicio 10 · Uniones e intersecciones infinitas]]
