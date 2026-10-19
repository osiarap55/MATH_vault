---
tipo: teorema
tags: [teorema, cardinales]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Teorema 3.67 · p. 114"
aliases: [Cantor-Schröder-Bernstein, Teorema de Cantor-Schröder-Bernstein, Schröder-Bernstein]
---
# Teorema de Cantor-Schröder-Bernstein

> [!important] Enunciado
> Si existen aplicaciones **inyectivas** $f:A\to B$ y $g:B\to A$, entonces existe una **biyección** entre $A$ y $B$.
> En cardinales: $\operatorname{card}A\le\operatorname{card}B$ y $\operatorname{card}B\le\operatorname{card}A$ $\Rightarrow$ $\operatorname{card}A=\operatorname{card}B$.

> [!tip] En palabras sencillas
> Si $A$ "cabe" dentro de $B$ y $B$ "cabe" dentro de $A$, tienen el mismo tamaño. Es la propiedad **antisimétrica** del orden entre cardinales. Para conjuntos finitos es obvio; para infinitos **no** lo es.

> [!abstract] Idea de la demostración (el libro no la hace)
> Para cada $a\in A$, sigue hacia atrás la "cadena de antecesores" alternando $g^{-1}$ y $f^{-1}$. Según dónde termine la cadena (en $A$, en $B$ o nunca), define $h(a)=f(a)$ o $h(a)=g^{-1}(a)$. Se comprueba que $h$ es biyectiva.

> [!example] Uso típico: probar que dos conjuntos son equipotentes sin construir la biyección
> $[0,1]\simeq(0,1)$: inyección $(0,1)\to[0,1]$ es la inclusión; inyección $[0,1]\to(0,1)$ es $x\mapsto\frac{x}{2}+\frac14$. Luego son equipotentes.

## Conexiones
- **Necesitas antes:** [[Aplicación inyectiva]], [[Cardinal]]
- **Se usa en:** orden entre cardinales ([[Cardinal]]), [[Conjunto numerable]] ($\mathbb N\times\mathbb N\simeq\mathbb N$, $\mathbb Q\simeq\mathbb N$)
