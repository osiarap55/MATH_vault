---
tipo: definición
tags: [definicion, conjuntos, logica]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.1 · pp. 36-38"
aliases: [Predicados, Función proposicional, Universo, Lógica de predicados, Propiedad característica, Relación lógica]
---
# Predicado

> [!tip] En palabras sencillas
> Un predicado es una **proposición con un hueco**: "$x$ es par". No es ni verdadera ni falsa hasta que rellenas el hueco ($x=4$ → verdadera, $x=3$ → falsa). Cada predicado "recorta" un subconjunto: los $x$ que lo cumplen.

> [!note] Definición
> Dado un conjunto $C$ (el **universo**), un **predicado** sobre $C$ es una propiedad $P_x$ de un elemento genérico $x\in C$ que se convierte en una [[Proposición]] para cada valor concreto $x=c$.
> Su **extensión** es el subconjunto
> $$C_P=\{x\in C\mid P_x\}$$
> y se dice que $P$ es una **propiedad característica** de $C_P$.

> [!important] Predicados ↔ subconjuntos
> - Todo predicado sobre $C$ define un subconjunto de $C$.
> - Todo subconjunto $A\subseteq C$ viene de un predicado: "$x\in A$".
> - Dos predicados son **equivalentes** sobre $C$ si definen el mismo subconjunto.
> - Con predicados se pueden usar todos los conectores: $\neg P_x$, $P_x\land Q_x$, $P_x\to Q_x$… y cada uno define un subconjunto (ver [[Álgebra de conjuntos]]).
> - Un **predicado de dos argumentos** $R_{xy}$ ("$x<y$") define un subconjunto de $A\times B$: es una [[Relación binaria]].

> [!example] Ejemplos
> - $C=\{1,2,3,5,6,7\}$, $P_x$: "$x$ es par". $P_1$ falsa, $P_2$ verdadera. $C_P=\{2,6\}$.
> - $\{x\in\mathbb Z\mid x\text{ par}\land x\text{ múltiplo de }3\}=\{x\in\mathbb Z\mid x\text{ múltiplo de }6\}$.
> - $\{x\in C\mid P_x\land\neg P_x\}=\emptyset$ (no contradicción).

> [!warning] Errores típicos
> - Tratar "$x>3$" como si fuera verdadera o falsa. Hasta que no sepas $x$ o lo **cuantifiques**, no lo es.
> - Muchos enunciados llevan un "para todo" **escondido**: "un número primo es impar" significa "**todo** primo es impar" (falsa: el 2).

## Conexiones
- **Necesitas antes:** [[Proposición]], [[Conjunto]]
- **Lleva a:** [[Cuantificadores]], [[Relación binaria]], [[Álgebra de conjuntos]]
