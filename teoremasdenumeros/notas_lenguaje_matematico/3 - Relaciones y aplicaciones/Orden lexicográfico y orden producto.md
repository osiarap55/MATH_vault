---
tipo: definición
tags: [definicion, relaciones, orden]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Ejemplos 3.22-3.23 · pp. 85-86"
aliases: [Orden lexicográfico, Orden producto, Orden de Pareto, Orden del diccionario]
---
# Orden lexicográfico y orden producto en $\mathbb R^2$

> [!tip] En palabras sencillas
> Dos maneras de ordenar puntos del plano:
> - **Lexicográfico** (como un diccionario): compara primero la primera coordenada; solo si empatan, mira la segunda. **Siempre** puedes comparar.
> - **Producto** (Pareto): $(a,b)$ va antes que $(c,d)$ si es **menor o igual en las dos** coordenadas. A veces **no** puedes comparar.

> [!note] Definición
> - **Lexicográfico:** $(a,b)\preceq_L(c,d)\iff a<c$ **o** $(a=c$ y $b\le d)$. Es un **orden total**.
> - **Producto:** $(a,b)\preceq_P(c,d)\iff a\le c$ **y** $b\le d$. Es un **orden parcial**.

> [!example] Comparar
> | Puntos | Lexicográfico | Producto |
> |---|---|---|
> | $(1,5)$ y $(2,0)$ | $(1,5)\prec_L(2,0)$ | no comparables |
> | $(1,2)$ y $(1,3)$ | $(1,2)\prec_L(1,3)$ | $(1,2)\prec_P(1,3)$ |
> | $(a,b)$ y $(b,a)$ con $a\neq b$ | comparables | **no** comparables |

> [!example] Dibujo mental
> - $\preceq_L$: los puntos "mayores" que $(a,b)$ son el semiplano $x>a$ más la semirrecta vertical $\{(a,y)\mid y\ge b\}$.
> - $\preceq_P$: los puntos mayores que $(a,b)$ son el **cuadrante** $[a,\infty)\times[b,\infty)$.

> [!warning] Ojo con los supremos
> En $\preceq_L$ un conjunto acotado **puede no tener supremo**. La franja $A=\{(x,y)\mid1\le x\le2\}$ está acotada superiormente por $(3,0)$. Sus cotas superiores son exactamente los puntos con $x>2$ (un punto $(2,b)$ no sirve, porque $(2,b+1)\in A$ es mayor). Y entre los puntos con $x>2$ no hay uno mínimo. Luego $A$ **no tiene supremo**: $(\mathbb R^2,\preceq_L)$ **no cumple la propiedad del supremo**, aunque $\mathbb R$ sí ([[Axioma del supremo]]).

## Conexiones
- **Necesitas antes:** [[Relación de orden]], [[Producto cartesiano]]
- **Lleva a:** [[Supremo e ínfimo]], [[Elementos maximales y minimales]]
- **Practica:** [[LM Ejercicios Cap 3#Ejercicio 3 · Cotas en el plano]]
