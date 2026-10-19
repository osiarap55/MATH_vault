---
tipo: método
tags: [metodo, enteros, divisibilidad]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Ejercicio 5.55 · p. 200"
aliases: [Ecuación diofántica, ax+by=c, Diofánticas]
---
# Ecuaciones diofánticas lineales  $ax+by=c$

> [!tip] En palabras sencillas
> Buscar soluciones **enteras** de $ax+by=c$. Tiene solución exactamente cuando el mcd divide a $c$, y entonces hay **infinitas**, todas de la forma "una particular + múltiplos de un paso fijo".

> [!important] Resultado
> Sea $d=\operatorname{mcd}(a,b)$.
> - $ax+by=c$ tiene solución entera $\iff d\mid c$.
> - Si $(x_p,y_p)$ es una solución, **todas** son
> $$x=x_p+\frac bd\,k,\qquad y=y_p-\frac ad\,k,\qquad k\in\mathbb Z.$$

> [!abstract] Método (idea y pasos)
> 1. Calcula $d$ con [[Algoritmo de Euclides]]. Si $d\nmid c$, no hay solución.
> 2. **Solución particular:** con [[Identidad de Bézout|Bézout]] $au+bv=d$; multiplica por $c/d$.
> 3. **Ecuación homogénea** $ax+by=0$: dividiendo por $d$, $a'x=-b'y$ con $\operatorname{mcd}(a',b')=1$; por el [[Lema de Euclides]], $b'\mid x$, así $x=b'k$, $y=-a'k$.
> 4. **General = particular + homogénea** (la diferencia de dos soluciones resuelve la homogénea).

> [!example] Ejemplo 5.55: $-5x+3y=1$
> - $\operatorname{mcd}(5,3)=1$ ✓. Solución particular: $x_p=1$, $y_p=2$ ($-5+6=1$).
> - Homogénea $5x=3y$: $3\mid5x$ y $\operatorname{mcd}(3,5)=1$ ⇒ $3\mid x$: $x=3k$, $y=5k$.
> - **Todas:** $(x,y)=(1+3k,\ 2+5k)$, $k\in\mathbb Z$.

> [!note] La misma estructura "particular + homogénea"
> aparece en sistemas lineales ([[resumen_algebralineal]]) y en ecuaciones diferenciales lineales.

## Conexiones
- **Necesitas antes:** [[Identidad de Bézout]], [[Lema de Euclides]], [[Algoritmo de Euclides]]
