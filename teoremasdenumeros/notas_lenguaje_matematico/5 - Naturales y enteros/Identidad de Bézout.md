---
tipo: teorema
tags: [teorema, enteros, divisibilidad]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "§5.5 · p. 197; Teorema 5.51; Ejemplo 5.49"
aliases: [Bézout, Teorema de Bézout, Identidad de Bezout]
---
# Identidad de Bézout

> [!important] Identidad de Bézout
> Si $d=\operatorname{mcd}(a,b)$, existen $u,v\in\mathbb Z$ con
> $$d=au+bv.$$
> Además, $d$ es el **menor** número positivo de la forma $am+bn$ ($m,n\in\mathbb Z$).

> [!important] Teorema de Bézout (5.51)
> $a$ y $b$ son **primos entre sí** $\iff$ existen $u,v\in\mathbb Z$ con $au+bv=1$.

> [!tip] En palabras sencillas
> Con dos jarras de $a$ y $b$ litros (llenando y vaciando) puedes medir exactamente $\operatorname{mcd}(a,b)$ litros, y nada más pequeño.

> [!abstract] Por qué es cierta
> Sale de la prueba del [[Máximo común divisor]]: $d\mathbb Z=a\mathbb Z+b\mathbb Z\ni d$.
> El recíproco del teorema: si $au+bv=1$, todo divisor común de $a,b$ divide a 1.

> [!example] Cómo encontrar $u,v$: Euclides "hacia atrás" (Ejemplo 5.49)
> $\operatorname{mcd}(4704,903)=21$ ([[Algoritmo de Euclides]]). Despeja los restos de abajo arriba:
> - $21=147-3\cdot42$
> - $42=189-147\ \Rightarrow\ 21=4\cdot147-3\cdot189$
> - $147=903-4\cdot189\ \Rightarrow\ 21=4\cdot903-19\cdot189$
> - $189=4704-5\cdot903\ \Rightarrow\ \boxed{21=99\cdot903-19\cdot4704}$

> [!warning] Errores típicos
> - $u,v$ **no son únicos**: $(u+bk/d,\ v-ak/d)$ también vale.
> - $au+bv=d$ **no** implica que $d$ sea el mcd (solo que el mcd divide a $d$), salvo si $d=1$.

## Conexiones
- **Necesitas antes:** [[Máximo común divisor]]
- **Lleva a:** [[Lema de Euclides]], [[Ecuaciones diofánticas lineales]]
- **Se usa en:** inversos en $\mathbb Z/n$ ([[Congruencia módulo n]]; $\mathbb Z/p$ es cuerpo)
