---
tipo: método
tags: [metodo, logica, indice]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "Comentarios cap. 1 · pp. 30-31"
aliases: [Tipos de demostración, Cómo demostrar]
---
# Métodos de demostración

> [!tip] En palabras sencillas
> Para demostrar "si $H$ entonces $C$" hay básicamente cuatro caminos. Cada uno se apoya en una ley lógica distinta.

| Método | Qué haces | Ley lógica que lo justifica |
|---|---|---|
| [[Demostración directa]] | De $H$ vas paso a paso hasta $C$ | [[Silogismo hipotético]], [[Modus ponens]] |
| [[Demostración por contrarrecíproco]] | Supones $\neg C$ y llegas a $\neg H$ | [[Recíproco y contrarrecíproco\|Transposición]] |
| [[Reducción al absurdo]] | Supones $H$ y $\neg C$ y llegas a una contradicción | [[Tercio excluso y no contradicción]] |
| [[Principio de inducción\|Inducción]] | Para afirmaciones sobre todos los $n\in\mathbb N$: caso base + paso | [[Axiomas de Peano]] (cap. 2 y 5) |

> [!tip] ¿Cuál elijo?
> - Si $C$ es "algo **existe** / **se cumple**" y tienes fórmulas → **directa**.
> - Si $C$ es una **negación** ("no es racional", "no existe", "es único") → **absurdo**.
> - Si $\neg C$ da más información que $C$ ("si $n^2$ es par, $n$ es par") → **contrarrecíproco**.
> - Si la afirmación depende de $n\in\mathbb N$ → **inducción**.

> [!warning] Errores típicos
> - Demostrar el **recíproco** en vez del enunciado.
> - En reducción al absurdo, no usar nunca la hipótesis supuesta (entonces el absurdo no viene de ahí).
> - Demostrar con ejemplos: **un ejemplo no demuestra un "para todo"**, pero **un contraejemplo sí lo refuta**.

## Conexiones
- **Necesitas antes:** [[Leyes lógicas]], [[Definición, teorema, lema y corolario]]
- **Ejemplos resueltos:** [[Irracionalidad de raíz de 2]], [[Infinitud de los números primos]], [[Unicidad del límite de una sucesión]]
