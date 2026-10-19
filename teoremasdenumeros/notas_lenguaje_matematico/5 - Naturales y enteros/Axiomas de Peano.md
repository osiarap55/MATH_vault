---
tipo: definición
tags: [definicion, naturales, fundamentos]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Ejemplo 2.5 · p. 38; §5.1 · pp. 160-161"
aliases: [Peano, Axioma de inducción, Sucesor, Función sucesor]
---
# Axiomas de Peano

> [!tip] En palabras sencillas
> Cinco reglas que capturan la idea de **contar**: hay un primer número (0), cada número tiene un siguiente, contando nunca vuelves atrás, y "todo lo que puedas alcanzar desde 0 dando pasos" son todos los naturales.

> [!note] Los axiomas
> - **A1.** $0$ es un número natural.
> - **A2.** Todo natural $n$ tiene un único **sucesor** $s(n)$, que es natural.
> - **A3.** $0$ no es sucesor de ningún natural.
> - **A4.** Si $s(m)=s(n)$, entonces $m=n$.
> - **A5 (inducción).** Si $M\subseteq\mathbb N$ contiene a $0$ y al sucesor de cada uno de sus elementos, entonces $M=\mathbb N$.

> [!important] Qué significa cada uno
> - A2 + A4: existe $s:\mathbb N\to\mathbb N$ **inyectiva**.
> - A3: $0\notin\operatorname{Im}(s)$, así que $s$ **no es sobreyectiva**: $\mathbb N$ es infinito.
> - A5: es el [[Principio de inducción]].
> - Consecuencias: todo $n\neq0$ es sucesor de alguno; $n\neq s(n)$ para todo $n$ (contando nunca te quedas quieto).
> - $\mathbb N=\{0,s(0),s(s(0)),\dots\}$, que llamamos $\{0,1,2,\dots\}$.

> [!abstract] Ejemplo de prueba con A5: "$n\neq s(n)$ para todo $n$"
> Sea $A=\{n\mid n\neq s(n)\}$.
> - $0\in A$: $0$ no es sucesor de nadie (A3), luego $0\neq s(0)$.
> - Si $n\in A$ y $s(n)\notin A$, entonces $s(n)=s(s(n))$ y por A4 $n=s(n)$, contradicción. Luego $s(n)\in A$.
> - Por A5, $A=\mathbb N$.

> [!note] ¿El 0 es natural?
> Es un convenio. El libro incluye el 0 (como en teoría de conjuntos y lógica) y escribe $\mathbb N^*=\{1,2,3,\dots\}$.

## Conexiones
- **Necesitas antes:** [[Sistema axiomático]]
- **Lleva a:** [[Principio de inducción]], [[Definición por recurrencia]], [[Suma y producto de naturales]], [[Números naturales]]
- **Modelo en teoría de conjuntos:** [[Axiomas de Zermelo-Fraenkel]] (axioma de infinitud), y los naturales como cardinales finitos ([[Números naturales]])
