---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "Comentarios cap. 1 · p. 30"
aliases: [Condición necesaria, Condición suficiente, Condición necesaria y suficiente, Teorema de caracterización]
---
# Condición necesaria y condición suficiente

> [!tip] En palabras sencillas
> En $P\Rightarrow Q$:
> - $P$ es **suficiente** para $Q$: *basta* con tener $P$ para tener $Q$.
> - $Q$ es **necesaria** para $P$: *sin* $Q$ no puede haber $P$.
>
> "Ser madrileño es suficiente para ser español; ser español es necesario para ser madrileño."

> [!note] Definición
> Si $P\Rightarrow Q$ es un teorema:
> - $P$ es **condición suficiente** de $Q$ (se usa para *asegurar* $Q$).
> - $Q$ es **condición necesaria** de $P$ (se usa para *descartar* $P$: si falla $Q$, falla $P$).
>
> Si $P\Leftrightarrow Q$: $P$ es **condición necesaria y suficiente** de $Q$. Estos teoremas se llaman **de caracterización**.

> [!example] Ejemplos
> - "$f$ derivable $\Rightarrow$ $f$ continua": derivable es **suficiente** para continua; continua es **necesaria** para derivable.
> - "Si $f$ tiene un máximo local en $x_0$ (y es derivable), entonces $f'(x_0)=0$": $f'(x_0)=0$ es **necesaria** pero no suficiente ($f(x)=x^3$ en $0$).
> - "$n$ es par $\Leftrightarrow$ $n^2$ es par": caracterización.

> [!warning] Errores típicos
> - Usar una condición **necesaria** como si fuera suficiente: "$f'(x_0)=0$, luego hay un máximo" ✗.
> - Decir "necesario" al revés. Truco: lo **necesario** está a la **derecha** de la flecha ($P\Rightarrow$ **Q**).

## Conexiones
- **Necesitas antes:** [[Implicación y equivalencia lógica]], [[Recíproco y contrarrecíproco]]
- **Lleva a:** [[Definición, teorema, lema y corolario]], [[Métodos de demostración]]
