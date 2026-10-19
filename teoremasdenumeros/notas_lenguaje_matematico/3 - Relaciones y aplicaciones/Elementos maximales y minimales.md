---
tipo: definición
tags: [definicion, orden]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.33 · pp. 91-94"
aliases: [Maximal, Minimal, Elemento maximal, Elemento minimal, Maximales, Minimales]
---
# Elementos maximales y minimales

> [!tip] En palabras sencillas
> - **Máximo:** está por encima de **todos**.
> - **Maximal:** **nadie** está por encima de él (pero puede haber elementos con los que ni siquiera se compara).
>
> En un orden total son lo mismo. En un orden parcial, puede haber **muchos maximales** y ningún máximo.

> [!note] Definición
> - $M\in A$ es **maximal** si no existe $x\in A$, $x\neq M$, con $M\preceq x$.
> - $m\in A$ es **minimal** si no existe $x\in A$, $x\neq m$, con $x\preceq m$.

> [!important] Relación con máximo/mínimo
> - Si $A$ tiene máximo, éste es el **único** maximal.
> - Si el orden es total, maximal ⇔ máximo.

> [!example] Ejemplos
> - $(\mathbb N^*,\mid)$, $A=\{2,3,\dots,10\}$: **minimales** $2,3,5,7$ (los primos: nadie de $A$ los divide); **maximales** $6,7,8,9,10$ (no dividen a nadie más de $A$). Ni máximo ni mínimo.
> - Triángulo $\{x,y\ge0,\ x+y\le1\}$ con el orden producto: **todos** los puntos de la hipotenusa $x+y=1$ son maximales; no hay máximo; $\min=(0,0)$.
> - En un grafo dirigido, los vértices sin flechas que salen son maximales.

## Conexiones
- **Necesitas antes:** [[Máximo y mínimo]], [[Relación de orden]]
- **Lleva a:** [[Lema de Zorn]] (garantiza que existen maximales)
