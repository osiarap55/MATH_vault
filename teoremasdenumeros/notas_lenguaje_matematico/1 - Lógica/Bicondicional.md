---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2 · p. 9; §1.4 · p. 17"
aliases: [Si y sólo si, ↔, sii, iff, Ley del bicondicional, Doble implicación]
---
# Bicondicional  $p\leftrightarrow q$

> [!tip] En palabras sencillas
> "$p$ **si y sólo si** $q$" dice que $p$ y $q$ **van juntas**: o las dos son verdad o las dos son mentira.

> [!note] Definición
> $p\leftrightarrow q$ es verdadera **solo cuando $p$ y $q$ toman el mismo valor**.
>
> | $p$ | $q$ | $p\leftrightarrow q$ |
> |:-:|:-:|:-:|
> | 0 | 0 | **1** |
> | 0 | 1 | 0 |
> | 1 | 0 | 0 |
> | 1 | 1 | **1** |

> [!important] Ley del bicondicional
> $$p\leftrightarrow q \iff (p\to q)\land(q\to p)$$
> Un "si y sólo si" son **dos condicionales**: la ida ($\Rightarrow$) y la vuelta ($\Leftarrow$).

> [!abstract] Por qué importa: cómo se demuestra un "si y sólo si"
> Casi siempre se hace en dos partes:
> 1. **($\Rightarrow$)** Supón $p$ y demuestra $q$.
> 2. **($\Leftarrow$)** Supón $q$ y demuestra $p$.
>
> Es lo mismo que se hace para probar que dos conjuntos son iguales por **doble inclusión** ([[Inclusión de conjuntos]]).

> [!example] Ejemplos
> - "8 es par si y sólo si 8 es divisible por 2" → $1\leftrightarrow 1=1$.
> - "$\dim \mathbb R^2 = 2$ si y sólo si $\{(1,0),(0,1)\}$ es una base de $\mathbb R^2$".
> - Dos proposiciones **falsas** cualesquiera dan un bicondicional verdadero: "$2=3 \leftrightarrow 5$ es par" es verdadera.

> [!warning] Errores típicos
> - Demostrar solo una dirección y creer que ya está probado el "si y sólo si".
> - Usar "si y sólo si" en una **definición** cuando basta "si": en las definiciones, el "si" ya se entiende como "si y sólo si".

## Conexiones
- **Necesitas antes:** [[Condicional]]
- **Lleva a:** [[Implicación y equivalencia lógica]], [[Condición necesaria y condición suficiente]]
- **Se usa en:** [[Inclusión de conjuntos]] (igualdad por doble inclusión), teoremas de caracterización.
