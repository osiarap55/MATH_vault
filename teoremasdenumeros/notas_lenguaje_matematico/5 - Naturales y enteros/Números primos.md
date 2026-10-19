---
tipo: definición
tags: [definicion, enteros, divisibilidad, complemento]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Complemento: el libro no tiene sección de primos (aparecen en Ej. 1.10, 4.31 y Ejercicio 11 del cap. 4)"
aliases: [Primo, Número primo, Primos, Número compuesto]
---
# Números primos

> [!warning] Complemento
> El libro no tiene un apartado de primos, pero los usa (infinitud de primos, $\mathbb Z/p$ cuerpo). Esta nota reúne lo básico usando las herramientas del cap. 5.

> [!note] Definición
> $p\in\mathbb N$, $p\ge2$, es **primo** si sus únicos divisores positivos son $1$ y $p$. Si $n\ge2$ no es primo, es **compuesto**: $n=rs$ con $1<r,s<n$.

> [!important] Propiedades básicas
> 1. **Todo $n\ge2$ tiene al menos un divisor primo.** (El menor divisor $>1$ de $n$ es primo; existe por el [[Buen orden]].)
> 2. Si $p$ es primo y $p\nmid a$, entonces $\operatorname{mcd}(p,a)=1$.
> 3. **[[Lema de Euclides]]:** $p\mid ab\Rightarrow p\mid a$ o $p\mid b$.
> 4. **Hay infinitos primos:** [[Infinitud de los números primos]].
> 5. $\mathbb Z/p$ es un [[Cuerpo]] $\iff p$ es primo.
> 6. Si $n$ es compuesto, tiene un divisor primo $\le\sqrt n$ (útil para comprobar primalidad).

> [!abstract] Demostración de 1 (idea)
> Sea $m$ el menor divisor de $n$ mayor que 1. Si $m$ no fuera primo, $m=rs$ con $1<r<m$, y $r$ dividiría a $n$, contradiciendo que $m$ es el menor.

> [!example] Ejemplos
> - Primos: $2,3,5,7,11,13,17,19,23,\dots$ El 2 es el **único primo par**.
> - $1$ **no** es primo (por convenio, para que la factorización sea única).

## Conexiones
- **Necesitas antes:** [[Divisibilidad]], [[Máximo común divisor]]
- **Lleva a:** [[Teorema fundamental de la aritmética]], [[Infinitud de los números primos]]
- **Más allá:** [[ramas_matematicas]] (teoría de números)
