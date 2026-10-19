---
tipo: definición
tags: [definicion, relaciones, orden]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.15 · pp. 82-84"
aliases: [Orden, Orden parcial, Orden total, Conjunto ordenado, Relaciones de orden]
---
# Relación de orden

> [!tip] En palabras sencillas
> Una relación de orden sirve para decir "**$x$ va antes que $y$**". Puede pasar que algunos pares **no se puedan comparar** (orden parcial) o que todos se puedan (orden total).

> [!note] Definición
> Una relación $\preceq$ en $U$ es **de orden** si es:
> 1. **Reflexiva:** $x\preceq x$
> 2. **Antisimétrica:** $x\preceq y$ y $y\preceq x$ $\Rightarrow x=y$
> 3. **Transitiva:** $x\preceq y$ y $y\preceq z$ $\Rightarrow x\preceq z$
>
> - Es **total** si dos elementos cualesquiera son comparables: $\forall x,y:\ x\preceq y$ o $y\preceq x$. Si no, es **parcial**.
> - $(U,\preceq)$ se llama **conjunto ordenado**. Se escribe $x\prec y$ si $x\preceq y$ y $x\neq y$.

> [!example] Ejemplos
> | Conjunto | Orden | ¿Total? |
> |---|---|---|
> | $\mathbb N,\mathbb Z,\mathbb Q,\mathbb R$ | $\le$ usual | ✓ |
> | $\mathcal P(U)$ | $\subseteq$ | ✗: $\{a\}$ y $\{b\}$ no son comparables |
> | $\mathbb N^*$ | $n\mid m$ (divide) | ✗: 2 y 3 no son comparables |
> | $\mathbb R^2$ | lexicográfico | ✓ → [[Orden lexicográfico y orden producto]] |
> | $\mathbb R^2$ | producto (Pareto) | ✗ |
> | Vértices de un grafo dirigido sin ciclos | "hay un camino de $x$ a $y$" | normalmente ✗ |

> [!warning] Errores típicos
> - $<$ (estricto) **no** es una relación de orden en este sentido: no es reflexiva (aunque sí transitiva).
> - Suponer que un orden es total sin comprobarlo. Muchos órdenes naturales ($\subseteq$, divide) son parciales.
> - En $\mathbb N^*$ con "divide", $1\mid n$ para todo $n$: el 1 es el **mínimo**, pero no hay máximo.

## Conexiones
- **Necesitas antes:** [[Propiedades de una relación]]
- **Lleva a:** [[Intervalos]], [[Cotas de un conjunto]], [[Máximo y mínimo]], [[Supremo e ínfimo]], [[Elementos maximales y minimales]], [[Buen orden]]
- **Se usa en:** [[Orden en los naturales]], [[Cuerpo ordenado]], [[Cardinal]] (orden entre cardinales)
