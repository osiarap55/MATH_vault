---
tipo: teorema
tags: [teorema, logica, analisis]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "Ejemplo 1.11 · p. 18"
aliases: [El límite es único, Unicidad del límite]
---
# El límite de una sucesión, si existe, es único

> [!note] Recordatorio: definición de límite
> $(x_n)$ converge a $r$ si para cada $\varepsilon>0$ existe $n_\varepsilon\in\mathbb N$ tal que
> $$|x_n-r|<\varepsilon\quad\text{para todo } n\ge n_\varepsilon.$$
> *"A partir de un momento, todos los términos están tan cerca de $r$ como quieras."*

> [!important] Teorema
> Si $x_n\to r$ y $x_n\to s$, entonces $r=s$.

> [!tip] En palabras sencillas
> Una sucesión no puede estar "cada vez más cerca" de dos sitios distintos a la vez: si $r$ y $s$ están separados, a partir de cierto momento los términos tendrían que estar en dos bolitas disjuntas al mismo tiempo.

> [!abstract] Demostración (idea y pasos) · [[Reducción al absurdo]]
> 1. Supón $r\neq s$ y toma $\varepsilon=\dfrac{|r-s|}{2}>0$.
> 2. Como $x_n\to r$: existe $n_1$ con $|x_n-r|<\varepsilon$ si $n\ge n_1$.
> 3. Como $x_n\to s$: existe $n_2$ con $|x_n-s|<\varepsilon$ si $n\ge n_2$.
> 4. Para $n\ge\max(n_1,n_2)$, por la [[Valor absoluto|desigualdad triangular]]:
> $$|r-s|\le|r-x_n|+|x_n-s|<\varepsilon+\varepsilon=|r-s|.$$
> 5. $|r-s|<|r-s|$: **contradicción**. ∎

> [!warning] Errores típicos
> - Elegir un $\varepsilon$ cualquiera: el truco es $\varepsilon=|r-s|/2$, la mitad de la distancia, para que las dos "bolitas" no se toquen.
> - Olvidar tomar $n\ge\max(n_1,n_2)$ para que se cumplan las dos condiciones a la vez.

## Conexiones
- **Usa:** [[Reducción al absurdo]], [[Cuantificadores]], [[Valor absoluto]]
- **Lo verás de nuevo en:** análisis real (límites de funciones, espacios métricos).
