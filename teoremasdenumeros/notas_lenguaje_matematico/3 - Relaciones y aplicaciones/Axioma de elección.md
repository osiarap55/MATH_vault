---
tipo: definición
tags: [definicion, conjuntos, fundamentos]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Comentarios cap. 3 · pp. 111-113"
aliases: [AC, Función de elección, ZFC, Axioma de Zermelo]
---
# Axioma de elección

> [!tip] En palabras sencillas
> Si tienes una colección (quizá infinita) de cajas **no vacías**, puedes **elegir un objeto de cada caja a la vez**. Parece obvio, pero no se puede deducir de los demás axiomas.

> [!note] Enunciados
> - **Función de elección:** dada una familia $\{F_i\mid i\in I\}$ de conjuntos no vacíos, una función $f$ con $f(F_i)\in F_i$ para todo $i$.
> - **Zermelo:** toda familia no vacía de conjuntos no vacíos tiene una función de elección.
> - **Russell:** el producto cartesiano $\prod_{i\in I}F_i$ de una familia de conjuntos no vacíos es no vacío.

> [!important] Equivalencias (en ZF)
> Axioma de elección $\iff$ [[Lema de Zorn]] $\iff$ teorema de [[Buen orden|buena ordenación]] (todo conjunto se puede bien ordenar) $\iff$ dos cardinales cualesquiera son comparables $\iff$ todo espacio vectorial tiene base.

> [!example] Dónde ya lo has usado
> En el [[Inversas laterales|Teorema 3.61]]: para construir $h$ con $f\circ h=I_B$ se **elige** un $c_y\in f^{-1}(y)$ para cada $y\in B$, a la vez.

> [!note] Estatus
> - Es **independiente** de ZF: Gödel probó que añadirlo no produce contradicciones; Cohen que su negación tampoco. ZF + elección = **ZFC**.
> - Problemas: las pruebas que lo usan **no son constructivas** (dicen que algo existe sin construirlo), y permite resultados antiintuitivos (paradoja de Banach-Tarski).
> - La mayoría de matemáticos lo acepta.

## Conexiones
- **Necesitas antes:** [[Familias de conjuntos]], [[Aplicación]]
- **Equivalentes:** [[Lema de Zorn]], [[Buen orden]]
- **Se usa en:** [[Inversas laterales]], [[Cardinal]]
- **Contexto:** [[Axiomas de Zermelo-Fraenkel]]
