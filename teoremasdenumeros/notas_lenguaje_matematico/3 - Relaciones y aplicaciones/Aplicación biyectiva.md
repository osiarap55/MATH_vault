---
tipo: definición
tags: [definicion, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.57 · p. 103"
aliases: [Biyectiva, Biyección, Correspondencia biunívoca, Biyecciones]
---
# Aplicación biyectiva

> [!tip] En palabras sencillas
> **Inyectiva + sobreyectiva**: empareja los elementos de $A$ y $B$ **uno a uno, sin que sobre ni falte nadie**. Por eso se puede "deshacer" (tiene inversa) y por eso $A$ y $B$ tienen "el mismo número de elementos".

> [!note] Definición
> $f:A\to B$ es **biyectiva** si es [[Aplicación inyectiva|inyectiva]] y [[Aplicación sobreyectiva|sobreyectiva]], es decir,
> $$\forall y\in B\ \ \exists!\,x\in A:\ f(x)=y.$$

> [!important] Caracterización (Teorema 3.59)
> $f$ es biyectiva $\iff$ existe $g:B\to A$ con $g\circ f=I_A$ y $f\circ g=I_B$.
> Esa $g$ es única: es la [[Aplicación inversa]] $f^{-1}$.

> [!tip] Cómo se demuestra
> - Opción 1: probar inyectiva y sobreyectiva por separado.
> - Opción 2: ver que $f(x)=y$ tiene **solución única** para cada $y$ (despejar $x$).
> - Opción 3: **encontrar la inversa** y comprobar las dos composiciones.
>
> Ejemplo: $x^3$ en $\mathbb R$: $x^3=y$ tiene la única solución $x=\sqrt[3]y$.

> [!example] Ejemplos
> - ✓ $ax+b$ ($a\neq0$), $x^3$, la identidad, $n\mapsto-n$ en $\mathbb Z$.
> - Si $f^n=I_A$ para algún $n\ge1$, $f$ es biyectiva (su inversa es $f^{n-1}$).
> - Entre conjuntos finitos de $n$ elementos hay $n!$ biyecciones (permutaciones).
> - Identificaciones útiles: $\mathbb R^2\times\mathbb R\cong\mathbb R^3$, matrices $2\times2\cong\mathbb R^4$.

## Conexiones
- **Necesitas antes:** [[Aplicación inyectiva]], [[Aplicación sobreyectiva]]
- **Lleva a:** [[Aplicación inversa]], [[Conjuntos equipotentes]], [[Cardinal]]
- **Se usa en:** [[Factorización canónica de una aplicación]], [[Homomorfismo]] (isomorfismos), [[Conjunto numerable]]
