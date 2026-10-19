---
tipo: teorema
tags: [teorema, enteros, divisibilidad, complemento]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Complemento: no está en el libro; usa la inducción completa (cap. 2) y el teorema de Gauss (Teorema 5.52)"
aliases: [TFA, Factorización en primos, Factorización única, Descomposición en factores primos]
---
# Teorema fundamental de la aritmética

> [!warning] Complemento
> No aparece en el libro, pero se demuestra con lo que ya tienes: inducción completa y el [[Lema de Euclides]].

> [!important] Teorema
> Todo $n\ge2$ se escribe como producto de primos
> $$n=p_1^{e_1}p_2^{e_2}\cdots p_k^{e_k},$$
> y esa descomposición es **única** salvo el orden de los factores.

> [!tip] En palabras sencillas
> Los primos son los "átomos" de la multiplicación: todo número se construye con ellos y de **una sola** manera.

> [!abstract] Demostración (idea y pasos)
> **Existencia** ([[Principio de inducción|inducción completa]]): si $n$ es primo, ya está. Si no, $n=rs$ con $1<r,s<n$; por hipótesis de inducción $r$ y $s$ son productos de primos, luego $n$ también.
> **Unicidad:** si $p_1\cdots p_k=q_1\cdots q_l$, entonces $p_1$ divide al producto de los $q_j$; por el [[Lema de Euclides]], $p_1\mid q_j$ para algún $j$, y como $q_j$ es primo, $p_1=q_j$. Simplifica y repite (inducción en $k$).

> [!example] Usos
> - $4704=2^5\cdot3\cdot7^2$ y $903=3\cdot7\cdot43$, así $\operatorname{mcd}=3\cdot7=21$ (**mínimo** exponente de cada primo) y $\operatorname{mcm}=2^5\cdot3\cdot7^2\cdot43$ (**máximo** exponente).
> - $(n,m)\mapsto2^n3^m$ es inyectiva por la unicidad: se usa en [[Conjunto numerable]].
> - Todo $n\ge2$ tiene un factor primo: se usa en [[Infinitud de los números primos]].

## Conexiones
- **Necesitas antes:** [[Números primos]], [[Lema de Euclides]], [[Principio de inducción]]
- **Se usa en:** [[Infinitud de los números primos]], [[Máximo común divisor]], [[Mínimo común múltiplo]], [[Conjunto numerable]]
