---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2 · p. 7"
aliases: [Y lógico, ∧]
---
# Conjunción  $p\land q$

> [!tip] En palabras sencillas
> "$p$ **y** $q$" solo es verdad si **las dos** cosas son verdad. Basta que una falle para que todo falle.

> [!note] Definición
> La conjunción $p\land q$ es verdadera **solo cuando $p$ y $q$ son verdaderas**. Otras notaciones: $p\cdot q$, $p\times q$.
>
> | $p$ | $q$ | $p\land q$ |
> |:-:|:-:|:-:|
> | 0 | 0 | 0 |
> | 0 | 1 | 0 |
> | 1 | 0 | 0 |
> | 1 | 1 | **1** |

> [!example] Ejemplos
> - "4 es par **y** 9 es impar" → $1\land 1 = 1$.
> - "$f(x)=x^2$ es continua en $[0,1]$ **y** derivable en $(0,1)$" → verdadera.
> - "3 es primo **y** 3 es par" → $1\land 0 = 0$.

> [!warning] Errores típicos
> - En castellano "pero", "aunque" o "además" también son conjunciones lógicas: "es pequeño **pero** caro" es $p\land q$.
> - $p\land\neg p$ es **siempre falsa**: es la [[Tercio excluso y no contradicción|ley de no contradicción]].

## Conexiones
- **Necesitas antes:** [[Proposición]], [[Conectores lógicos]]
- **Lleva a:** [[Leyes de De Morgan]], [[Forma clausulada]]
- **En conjuntos:** $x\in A\cap B \iff (x\in A)\land(x\in B)$ → [[Unión e intersección]].
