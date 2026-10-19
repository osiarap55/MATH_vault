---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2 · p. 6"
aliases: [No lógico, ¬, Doble negación, Ley de la doble negación]
---
# Negación  $\neg p$

> [!tip] En palabras sencillas
> Negar es darle la vuelta al valor de verdad: lo verdadero pasa a falso y lo falso a verdadero.

> [!note] Definición
> La negación de $p$ es la proposición $\neg p$ ("no $p$"), que es **verdadera si $p$ es falsa** y **falsa si $p$ es verdadera**.
> Otras notaciones: $\sim p$, $\bar p$, $p'$.
>
> | $p$ | $\neg p$ |
> |:-:|:-:|
> | 0 | 1 |
> | 1 | 0 |

> [!important] Ley de la doble negación
> $$\neg\neg p \iff p$$
> "Una doble negación afirma". Con una sola proposición y $\neg$ solo se obtienen dos cosas distintas: $p$ y $\neg p$.

> [!example] Ejemplos
> - $p$: "4 es par" ($1$) → $\neg p$: "4 no es par" ($0$).
> - $p$: "$f(x)=1/x$ está definida en $x=0$" ($0$) → $\neg p$ es verdadera.

> [!warning] Errores típicos
> - **Negar no es decir lo contrario extremo.** La negación de "todos aprueban" es "**alguno** suspende", no "todos suspenden". Ver [[Cuantificadores]].
> - La negación de "$x>3$" es "$x\le 3$", **no** "$x<3$".
> - Negar una conjunción o disyunción requiere [[Leyes de De Morgan]]: $\neg(p\land q)\iff \neg p\lor\neg q$.

## Conexiones
- **Necesitas antes:** [[Proposición]]
- **Lleva a:** [[Leyes de De Morgan]], [[Tercio excluso y no contradicción]], [[Reducción al absurdo]]
- **En conjuntos:** el complementario $A^c$ es la negación de "$x\in A$" (ver [[Diferencia y complementario]]).
