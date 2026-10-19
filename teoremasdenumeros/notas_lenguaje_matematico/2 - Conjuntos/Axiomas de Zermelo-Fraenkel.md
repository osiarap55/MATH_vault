---
tipo: definición
tags: [definicion, conjuntos, fundamentos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "Comentarios cap. 2 · pp. 67-68"
aliases: [ZF, ZFC, Teoría axiomática de conjuntos, Axioma de extensión, Axioma de especificación, Axioma de infinitud]
---
# Axiomas de Zermelo-Fraenkel (ZF)

> [!tip] En palabras sencillas
> Como "conjunto" no se puede definir sin dar vueltas (colección, familia… son sinónimos), se dan **reglas del juego** que dicen qué conjuntos existen y cómo se comportan. El libro los muestra solo para que veas la dificultad: **no hace falta memorizarlos**.

> [!note] Los axiomas (versión informal)
> | # | Axioma | Qué dice |
> |---|---|---|
> | 1 | Extensión | Dos conjuntos con los mismos elementos son iguales |
> | 2 | Vacío | Existe un conjunto sin elementos, $\emptyset$ |
> | 3 | Pares | Dados $A,B$ existe $\{A,B\}$ |
> | 4 | Unión | Dado un conjunto de conjuntos, existe la unión de todos ellos |
> | 5 | Partes | Dado $A$, existe $\mathcal P(A)$ |
> | 6 | **Especificación** | Dado $A$ y una propiedad $\varphi$, existe $\{x\in A\mid\varphi(x)\}$ ← evita [[Paradoja de Russell\|Russell]] |
> | 7 | Sustitución | La imagen de un conjunto por una "función definible" es un conjunto |
> | 8 | **Infinitud** | Existe un conjunto que contiene $\emptyset$ y, con cada $x$, contiene $x\cup\{x\}$ ← da los [[Números naturales]] |
> | 9 | Regularidad | Todo conjunto no vacío tiene un elemento disjunto con él (impide $x\in x$) |
>
> **ZFC** = ZF + [[Axioma de elección]].

> [!example] Los naturales dentro de ZF
> $0=\emptyset$, $1=\{\emptyset\}$, $2=\{\emptyset,\{\emptyset\}\}$, … y el sucesor de $n$ es $n\cup\{n\}$. El axioma de infinitud garantiza que todos juntos forman un conjunto: $\mathbb N$.

## Conexiones
- **Necesitas antes:** [[Sistema axiomático]], [[Paradoja de Russell]]
- **Lleva a:** [[Axiomas de Peano]], [[Axioma de elección]]
