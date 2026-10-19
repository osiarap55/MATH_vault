---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2 · pp. 6-7, 12"
aliases: [O lógico, ∨, Disyunción excluyente, O exclusivo, XOR]
---
# Disyunción  $p\lor q$

> [!tip] En palabras sencillas
> "$p$ **o** $q$" es verdad si **al menos una** de las dos es verdad, **incluido el caso de que lo sean las dos**. Es el "o" de "el medicamento sirve para el dolor de cabeza o la fiebre".

> [!note] Definición (disyunción inclusiva)
> $p\lor q$ es **falsa solo cuando $p$ y $q$ son falsas**. Otras notaciones: $p+q$.
>
> | $p$ | $q$ | $p\lor q$ |
> |:-:|:-:|:-:|
> | 0 | 0 | **0** |
> | 0 | 1 | 1 |
> | 1 | 0 | 1 |
> | 1 | 1 | 1 |

> [!note] Disyunción excluyente $p\oplus q$
> Verdadera cuando **exactamente una** es verdadera ("bebo agua o horchata, pero no las dos").
>
> | $p$ | $q$ | $p\oplus q$ |
> |:-:|:-:|:-:|
> | 0 | 0 | 0 |
> | 0 | 1 | 1 |
> | 1 | 0 | 1 |
> | 1 | 1 | **0** |
>
> Se puede escribir como $(p\land\neg q)\lor(\neg p\land q)$, o como $\neg(p\leftrightarrow q)$.

> [!example] Ejemplos
> - "4 es par **o** 4 es impar" → $1\lor 0 = 1$.
> - "El punto $(1,1)$ cumple $x^2+y^2\le 4$" es una disyunción: "$x^2+y^2<4$ **o** $x^2+y^2=4$" → $1\lor 0=1$.

> [!warning] Errores típicos
> - En matemáticas **"o" siempre es inclusivo** salvo que se diga "o bien… o bien…" / "exclusivamente".
> - "Compraré el regalo hoy o mañana" suena excluyente en castellano; en lógica sería $\lor$ igualmente salvo que se use $\oplus$.

## Conexiones
- **Necesitas antes:** [[Proposición]], [[Conectores lógicos]]
- **Lleva a:** [[Leyes de De Morgan]], [[Tercio excluso y no contradicción]], [[Silogismo disyuntivo]], [[Forma clausulada]]
- **En conjuntos:** $x\in A\cup B \iff (x\in A)\lor(x\in B)$; el $\oplus$ corresponde a la [[Diferencia simétrica]].
