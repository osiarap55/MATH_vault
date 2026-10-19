---
tipo: teorema
tags: [teorema, reales, racionales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Prop. 6.6 · p. 215; Prop. 6.14 · p. 224"
aliases: [Densidad, Q es denso en R, Los irracionales son densos, Orden divisible, Orden denso]
---
# Densidad de $\mathbb Q$ (y de los irracionales) en $\mathbb R$

> [!important] Proposición 6.14
> Para todo $a<b$ en $\mathbb R$:
> $$(a,b)\cap\mathbb Q\neq\emptyset\qquad\text{y}\qquad(a,b)\cap(\mathbb R\setminus\mathbb Q)\neq\emptyset.$$
> Es decir, **en cualquier intervalo, por pequeño que sea, hay racionales e irracionales** (de hecho, infinitos de cada).

> [!tip] En palabras sencillas
> Los racionales y los irracionales están "mezclados por todas partes" en la recta, como la sal y la pimienta: no hay ningún trocito de recta que sea solo de uno de ellos.

> [!abstract] Demostración (idea y pasos)
> **Un racional entre $x<y$:**
> 1. Por la [[Propiedad arquimediana]], existe $n$ con $\frac1n<y-x$.
> 2. Sea $m=E(nx)$ ([[Parte entera]]): $m\le nx<m+1$.
> 3. Entonces $x<\frac{m+1}n\le x+\frac1n<y$. ✓
>
> **Un irracional entre dos racionales $x<y$:** $z=x+\frac{y-x}{\sqrt2}$ (es irracional porque si no, $\sqrt2$ sería racional).

> [!note] Proposición 6.6 (orden divisible de $\mathbb Q$)
> Entre dos racionales siempre hay otro: $\frac{\alpha+\beta}2$. En $\mathbb Z$ no ($(n,n+1)_{\mathbb Z}=\emptyset$).

> [!important] Consecuencia: aproximar por racionales
> Todo real $x$ es **límite de una sucesión de racionales** (y de una de irracionales): elige $a_n\in\left(x-\frac1n,x+\frac1n\right)\cap\mathbb Q$; entonces $|x-a_n|<\frac1n$.

> [!warning] Denso no es "grande"
> $\mathbb Q$ es denso pero **numerable**; los irracionales también son densos y **no** numerables ([[R no es numerable]]).

## Conexiones
- **Usa:** [[Propiedad arquimediana]], [[Parte entera]], [[Irracionalidad de raíz de 2]]
- **Se usa en:** [[Cortaduras de Dedekind]], análisis real (límites)
