---
tipo: teorema
tags: [definicion, teorema, cardinales]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Def. 5.27 y Prop. 5.29-5.32, Ejemplos 5.31-5.34 · pp. 181-186; §6"
aliases: [Numerable, Conjuntos numerables, Aleph cero, ℵ0, Q es numerable, Z es numerable, N×N es numerable, R no es numerable, Diagonal de Cantor para N×N]
---
# Conjunto numerable

> [!tip] En palabras sencillas
> Un conjunto es numerable si puedes poner **todos** sus elementos en una **lista infinita** $x_0,x_1,x_2,\dots$ (sin que falte ninguno). Es el "infinito más pequeño".

> [!note] Definición 5.27
> $A$ es **numerable** si es equipotente a $\mathbb N$: $\operatorname{card}A=\aleph_0$ ("alef cero").
> (Algunos autores llaman numerables también a los finitos; aquí no.)

> [!important] Resultados
> 1. **Todo subconjunto de $\mathbb N$ es finito o numerable** (Prop. 5.29). ⇒ no hay infinitos "más pequeños" que $\aleph_0$.
> 2. **$\mathbb N\times\mathbb N$ es numerable** (Prop. 5.30).
> 3. Subconjuntos y productos (finitos) de numerables son finitos o numerables; la unión de dos numerables, y **la unión numerable de numerables**, es numerable (Prop. 5.32).
> 4. **$\mathbb Z$ y $\mathbb Q$ son numerables** (Ej. 5.33). Las partes finitas de $\mathbb N$ forman un conjunto numerable (Ej. 5.34).
> 5. $\mathcal P(\mathbb N)\simeq\{0,1\}^{\mathbb N}$ **no** es numerable ([[Teorema de Cantor]]); tampoco $\mathbb R$ (cap. 6).

> [!abstract] Ideas de las demostraciones
> - **(1)** Si $A\subseteq\mathbb N$ es infinito, lístalo **por orden**: $f(0)=\min A$, $f(n+1)=\min\big(A\setminus\{f(0),\dots,f(n)\}\big)$ (usa el [[Buen orden]]). $f$ es biyectiva.
> - **(2)** $(n,m)\mapsto2^n3^m$ es inyectiva (factorización única) y su imagen es un subconjunto infinito de $\mathbb N$; aplica (1).
>   O con la **biyección diagonal de Cantor**: recorre $\mathbb N^2$ por diagonales $n+m=0,1,2,\dots$:
>   $$f(n,m)=\frac{(n+m)(n+m+1)}{2}+m.$$
> - **(4)** $\mathbb Z=\{0,1,-1,2,-2,\dots\}$. $\ \mathbb Q^+\to\mathbb N^2$, $\frac pq\mapsto(p,q)$ (fracción irreducible) es inyectiva.

> [!warning] Errores típicos
> - Pensar que $\mathbb Q$ tiene "más" elementos que $\mathbb N$ porque es denso. Son igual de numerosos.
> - Pensar que una unión numerable de numerables puede no ser numerable (sí lo es, usando elección numerable).

## Conexiones
- **Necesitas antes:** [[Conjunto infinito]], [[Buen orden]], [[Conjuntos equipotentes]]
- **Lleva a:** [[Teorema de Cantor]], [[Números reales]] (no numerables)
- **Aritmética:** $\aleph_0+\aleph_0=\aleph_0\cdot\aleph_0=\aleph_0$ ([[Suma y producto de cardinales]])
