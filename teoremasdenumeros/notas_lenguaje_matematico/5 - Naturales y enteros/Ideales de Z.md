---
tipo: teorema
tags: [teorema, enteros, anillos]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Ejercicio 5.44 · pp. 194-195"
aliases: [Subgrupos de Z, Todo ideal de Z es principal, Z es un dominio de ideales principales]
---
# Ideales (y subgrupos) de $\mathbb Z$

> [!important] Teorema (Ejercicio 5.44)
> 1. **Todo [[Ideal]] de $\mathbb Z$ es principal:** es de la forma $n\mathbb Z=\{kn\mid k\in\mathbb Z\}$ con $n\in\mathbb N$.
> 2. **Todo [[Subgrupo]] de $(\mathbb Z,+)$ es de la forma $n\mathbb Z$.**

> [!tip] En palabras sencillas
> Los únicos subconjuntos de $\mathbb Z$ cerrados para sumar y restar son "los múltiplos de algún $n$". Y ese $n$ es **el menor positivo** del conjunto.

> [!abstract] Demostración (idea y pasos)
> 1. Si $I=\{0\}$, $I=0\mathbb Z$. Si no, sea $n$ el **menor elemento positivo** de $I$ (existe por [[Buen orden]]).
> 2. Sea $a\in I$. [[División euclídea|Divide]]: $a=qn+r$, $0\le r<n$.
> 3. $r=a-qn\in I$ (porque $I$ es ideal). Como $0\le r<n$ y $n$ era el menor positivo, $r=0$.
> 4. Luego $a=qn\in n\mathbb Z$. Y $n\mathbb Z\subseteq I$ es obvio. ∎
>
> Para subgrupos: se prueba por inducción que $pa\in G$ para $p\in\mathbb N$, luego (con opuestos) para $p\in\mathbb Z$. Así todo subgrupo es ideal, y se aplica 1.

> [!important] Por qué importa
> De aquí salen el [[Mínimo común múltiplo]] ($a\mathbb Z\cap b\mathbb Z=m\mathbb Z$) y el [[Máximo común divisor]] ($a\mathbb Z+b\mathbb Z=d\mathbb Z$), con la [[Identidad de Bézout]] gratis.

## Conexiones
- **Necesitas antes:** [[Ideal]], [[División euclídea]], [[Buen orden]]
- **Lleva a:** [[Máximo común divisor]], [[Mínimo común múltiplo]]
- **Profundiza:** [[resumen_cuerposanillosyteoriadegalois]] (dominios de ideales principales)
