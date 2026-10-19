---
tipo: definición
tags: [definicion, aplicaciones, cardinales]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "§3.4 · p. 108"
aliases: [Equipotencia, Equipotentes, Conjuntos coordinables]
---
# Conjuntos equipotentes

> [!tip] En palabras sencillas
> Dos conjuntos son equipotentes si se pueden **emparejar uno a uno** (con una biyección). Es la forma de decir "tienen el mismo número de elementos" **sin contar**, y funciona también para conjuntos infinitos.

> [!note] Definición
> $A$ y $B$ son **equipotentes**, $A\simeq B$, si existe una [[Aplicación biyectiva|biyección]] $f:A\to B$.

> [!important] Se comporta como una equivalencia
> - Reflexiva: $I_A$ es biyectiva.
> - Simétrica: si $f$ es biyectiva, $f^{-1}$ también ([[Aplicación inversa]]).
> - Transitiva: la composición de biyecciones es biyección.
>
> (Se dice "relación" entre comillas porque la colección de todos los conjuntos **no es un conjunto**: [[Paradoja de Russell]].)

> [!example] Ejemplos sorprendentes con infinitos
> - $\mathbb N\simeq2\mathbb N$ (los pares) con $n\mapsto2n$: ¡un conjunto es equipotente a una parte propia suya!
> - $\mathbb N\simeq\mathbb Z$: $0,1,-1,2,-2,\dots$
> - $(0,1)\simeq\mathbb R$.
> - $\mathbb N\not\simeq\mathbb R$ y $A\not\simeq\mathcal P(A)$ ([[Teorema de Cantor]]).

## Conexiones
- **Necesitas antes:** [[Aplicación biyectiva]]
- **Lleva a:** [[Cardinal]], [[Conjunto finito]], [[Conjunto infinito]], [[Conjunto numerable]]
