---
tipo: teorema
tags: [teorema, enteros, divisibilidad]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Teorema 5.52 (teorema de Gauss) y Ejercicios 5.53-5.54 · pp. 199-200"
aliases: [Teorema de Gauss, Teorema de Gauss (divisibilidad), Lema de Gauss]
---
# Lema de Euclides (teorema de Gauss)

> [!important] Teorema 5.52 (el libro lo llama *teorema de Gauss*)
> Si $a\mid bc$ y $\operatorname{mcd}(a,b)=1$, entonces $a\mid c$.
>
> **Caso particular (lema de Euclides):** si $p$ es [[Números primos|primo]] y $p\mid bc$, entonces $p\mid b$ o $p\mid c$.

> [!tip] En palabras sencillas
> Si $a$ divide a un producto pero no comparte nada con uno de los factores, tiene que "caber" entero en el otro.

> [!abstract] Demostración (idea y pasos) · usa [[Identidad de Bézout|Bézout]]
> 1. Como $\operatorname{mcd}(a,b)=1$: $au+bv=1$.
> 2. Multiplica por $c$: $acu+bcv=c$.
> 3. $a\mid acu$ y $a\mid bc$, luego $a$ divide a la suma: $a\mid c$. ∎

> [!important] Consecuencias (ejercicios 5.53 y 5.54)
> - Si $a\mid k$, $b\mid k$ y $\operatorname{mcd}(a,b)=1$, entonces $ab\mid k$.
> - Si $\operatorname{mcd}(a,b)=\operatorname{mcd}(a,c)=1$, entonces $\operatorname{mcd}(a,bc)=1$.

> [!failure] Sin la hipótesis falla
> $6\mid4\cdot3$ pero $6\nmid4$ y $6\nmid3$ ($\operatorname{mcd}(6,4)=2\neq1$).

## Conexiones
- **Necesitas antes:** [[Identidad de Bézout]], [[Divisibilidad]]
- **Lleva a:** [[Teorema fundamental de la aritmética]] (unicidad), [[Ecuaciones diofánticas lineales]], [[Irracionalidad de raíz de 2]] (generalización a $\sqrt p$)
- **Se usa en:** $\mathbb Z/p$ es íntegro ⇒ es cuerpo ([[LM Ejercicios Cap 4#Ejercicio 5 · Z-n es cuerpo si y sólo si n es primo|ejercicio]])
