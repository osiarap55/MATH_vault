---
tipo: definición
tags: [definicion, combinatoria, naturales]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Prop. 4.21 · p. 134; §3.4 · pp. 109-110; cap. 5"
aliases: [Coeficiente binomial, Combinaciones, n sobre k, Fórmula de Pascal, Triángulo de Pascal, Variaciones, Permutaciones]
---
# Número combinatorio  $\binom nk$

> [!tip] En palabras sencillas
> $\binom nk$ ("$n$ sobre $k$") es el número de formas de **elegir $k$ cosas de entre $n$** sin importar el orden. Es el número de subconjuntos de $k$ elementos de un conjunto de $n$.

> [!note] Definición
> $$\binom nk=\frac{n!}{k!\,(n-k)!},\qquad0\le k\le n$$
> con $0!=1$ ([[Definición por recurrencia|factorial]]).

> [!important] Propiedades
> - $\binom n0=\binom nn=1$, $\ \binom n1=n$.
> - **Simetría:** $\binom nk=\binom n{n-k}$ (elegir los que entran = elegir los que quedan fuera).
> - **Fórmula de Pascal:** $\binom n{k-1}+\binom nk=\binom{n+1}k$.
> - $\sum_k\binom nk=2^n$.

> [!abstract] Demostración de Pascal (idea combinatoria)
> Para elegir $k$ de entre $n+1$ objetos, fija uno, $x$. O lo eliges (y te quedan $k-1$ de los otros $n$: $\binom n{k-1}$), o no (y eliges $k$ de los otros $n$: $\binom nk$). Es la misma idea que en [[Conjunto de las partes]].

> [!note] Otros conteos (aparecen en el cap. 3)
> | Qué cuentas | Fórmula |
> |---|---|
> | Permutaciones de $n$ (biyecciones) | $n!$ |
> | Variaciones sin repetición de $m$ tomados de $n$ en $n$ (inyecciones) | $m(m-1)\cdots(m-n+1)$ |
> | Variaciones con repetición (todas las aplicaciones) | $m^n$ |
> | Combinaciones de $n$ tomados de $k$ en $k$ (subconjuntos) | $\binom nk$ |

> [!example] Triángulo de Pascal
> ```
>         1
>        1 1
>       1 2 1
>      1 3 3 1
>     1 4 6 4 1
> ```
> Cada número es la suma de los dos de encima (fórmula de Pascal).

## Conexiones
- **Necesitas antes:** [[Definición por recurrencia]], [[Conjunto finito]]
- **Se usa en:** [[Binomio de Newton]], [[Cardinal]] (contar aplicaciones)
