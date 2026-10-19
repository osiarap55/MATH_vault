---
tipo: teorema
tags: [teorema, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · p. 15"
aliases: [Tercio excluso, Ley del tercio excluso, No contradicción, Ley de contradicción, Ley de no contradicción]
---
# Tercio excluso y no contradicción

> [!tip] En palabras sencillas
> - **Tercio excluso:** o pasa algo o no pasa; no hay una tercera opción.
> - **No contradicción:** algo no puede pasar y no pasar a la vez.

> [!important] Enunciado
> $$p\lor\neg p\iff\mathbf 1 \quad(\text{tercio excluso})\qquad\qquad p\land\neg p\iff\mathbf 0\quad(\text{no contradicción})$$

> [!abstract] Demostración (idea)
> Tabla de dos filas: si $p=0$, $\neg p=1$; si $p=1$, $\neg p=0$. En cada fila exactamente una de las dos es verdadera, así que $\lor$ da siempre 1 y $\land$ siempre 0.

> [!example] Ejemplos
> - "$\pi$ es racional o irracional" → siempre verdadera (tercio excluso).
> - "3 es primo y compuesto" → siempre falsa (no contradicción).

> [!warning] Por qué importan tanto
> - El **tercio excluso** justifica la [[Reducción al absurdo]]: si $\neg p$ es imposible, la única opción que queda es $p$.
> - También justifica las demostraciones **por casos**: "o $n$ es par o $n$ es impar".

## Conexiones
- **Necesitas antes:** [[Negación]], [[Tautología y contradicción]]
- **Se usa en:** [[Reducción al absurdo]], [[Forma clausulada]] (para eliminar cláusulas $p\lor\neg p\lor\dots$)
- **En conjuntos:** $A\cup A^c=U$ y $A\cap A^c=\emptyset$ ([[Álgebra de conjuntos]])
