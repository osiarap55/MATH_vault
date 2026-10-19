---
tipo: teorema
tags: [definicion, teorema, reales, cardinales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Ejercicio 20 · p. 239"
aliases: [Número algebraico, Número trascendente, Algebraicos, Trascendentes]
---
# Números algebraicos y trascendentes

> [!note] Definición
> Un real es **algebraico** si es raíz de algún polinomio no nulo con coeficientes **enteros**. Si no, es **trascendente**.

> [!example] Ejemplos
> - Algebraicos: todo racional $\frac ab$ (raíz de $bx-a$), $\sqrt2$ ($x^2-2$), $\sqrt[3]5$, $\frac{1+\sqrt5}2$ ($x^2-x-1$).
> - Trascendentes: $e$ y $\pi$ (demostrarlo es difícil: Hermite 1873, Lindemann 1882).

> [!important] Teorema (Ejercicio 20)
> 1. El conjunto de los números algebraicos es **numerable**.
> 2. Por tanto, el de los trascendentes **no es numerable**: "casi todos" los reales son trascendentes.

> [!abstract] Demostración (idea y pasos)
> 1. Un polinomio de grado $\le n$ con coeficientes enteros es una $(n+1)$-upla de $\mathbb Z^{n+1}$: hay una cantidad numerable ([[Conjunto numerable|Prop. 5.32]]). Unión sobre $n$: los polinomios forman un conjunto numerable.
> 2. Cada polinomio no nulo tiene un número **finito** de raíces.
> 3. Los algebraicos son una unión numerable de conjuntos finitos: numerable (es infinito porque contiene a $\mathbb Q$).
> 4. Si los trascendentes fueran numerables, $\mathbb R$ = algebraicos ∪ trascendentes lo sería. Contradice [[R no es numerable]].

> [!tip] Lo curioso
> Cantor probó así que existen trascendentes **sin exhibir ninguno**: una demostración de existencia no constructiva.

## Conexiones
- **Usa:** [[Conjunto numerable]], [[R no es numerable]]
- **Relacionado:** [[Número e]], [[Teorema fundamental del álgebra]]
