---
tipo: teorema
tags: [definicion, teorema, reales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Prop. 6.11 · pp. 221-222"
aliases: [Función parte entera, E(x), Suelo, floor, [x]]
---
# Parte entera

> [!important] Proposición 6.11
> Para cada $x\in\mathbb R$ existe un **único** $z\in\mathbb Z$ con
> $$z\le x<z+1.$$
> Se llama **parte entera** de $x$: $E(x)$ o $\lfloor x\rfloor$.

> [!tip] En palabras sencillas
> Es "el entero que queda justo a la izquierda (o encima) de $x$" en la recta. **Para negativos, se va hacia abajo.**

> [!example] Ejemplos
> $E(2)=2$, $E(2{,}5)=2$, $E(-2)=-2$, **$E(-2{,}5)=-3$** (no $-2$).

> [!abstract] Demostración (idea)
> Para $x\ge0$: $A=\{n\in\mathbb N\mid n\le x\}$ es no vacío y acotado; su supremo es en realidad un **máximo** $p\in A$ (si $z=\sup A$, hay $p\in A$ con $z-1<p$, y entonces ningún natural mayor que $p$ está en $A$). Ese $p$ cumple $p\le x<p+1$. Para $x<0$ se usa $-x$. Unicidad: dos enteros distintos distan al menos 1.

> [!important] Usos
> - **Truncamiento decimal:** $\frac{E(10^nx)}{10^n}\le x<\frac{E(10^nx)+1}{10^n}$ ([[Expresión decimal]]).
> - **Propiedad arquimediana:** $n=E(y/x)+1$ cumple $nx>y$ ([[Propiedad arquimediana]]).
> - "Tener la misma parte entera" es la relación de equivalencia de la partición $\{[i-1,i)\}$ ([[Partición de un conjunto]]).

## Conexiones
- **Usa:** [[Axioma del supremo]], [[Orden en los naturales]]
- **Se usa en:** [[Propiedad arquimediana]], [[Densidad de Q en R]], [[Expresión decimal]]
