---
tipo: método
tags: [metodo, enteros, divisibilidad]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "§5.5 · pp. 197-199; Ejemplo 5.48"
aliases: [Euclides, Algoritmo de las divisiones sucesivas]
---
# Algoritmo de Euclides

> [!tip] En palabras sencillas
> Para hallar el mcd de dos números, **divide el grande entre el pequeño y quédate con el resto**; repite con el pequeño y el resto… **El último resto no nulo es el mcd.**

> [!important] La clave
> Si $a=qb+r$, entonces
> $$\operatorname{mcd}(a,b)=\operatorname{mcd}(b,r).$$
> *Por qué:* de $a=qb+r$, todo divisor de $b$ y $r$ divide a $a$; de $r=a-qb$, todo divisor de $a$ y $b$ divide a $r$. Los divisores comunes son los mismos.

> [!note] El algoritmo
> 1. $r_0=a$, $r_1=b$ (con $a>b$).
> 2. Divide: $r_{i-1}=q_ir_i+r_{i+1}$, $0\le r_{i+1}<r_i$.
> 3. Para cuando $r_{k+1}=0$. Entonces $\operatorname{mcd}(a,b)=r_k$.
>
> **Termina** porque $r_0>r_1>r_2>\cdots\ge0$ es una sucesión estrictamente decreciente de naturales ([[Buen orden]]).

> [!example] $\operatorname{mcd}(4704,903)$
> | División | Resto |
> |---|---|
> | $4704=5\cdot903+189$ | 189 |
> | $903=4\cdot189+147$ | 147 |
> | $189=1\cdot147+42$ | 42 |
> | $147=3\cdot42+21$ | **21** |
> | $42=2\cdot21+0$ | 0 |
> $\operatorname{mcd}(4704,903)=21$. Para los coeficientes de Bézout, ver [[Identidad de Bézout]].

## Conexiones
- **Necesitas antes:** [[División euclídea]], [[Máximo común divisor]]
- **Lleva a:** [[Identidad de Bézout]] (coeficientes), [[Ecuaciones diofánticas lineales]]
