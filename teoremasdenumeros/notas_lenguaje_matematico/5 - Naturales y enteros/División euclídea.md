---
tipo: teorema
tags: [teorema, enteros, divisibilidad]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Teorema 5.43 · p. 194"
aliases: [División entera, Cociente y resto, Algoritmo de la división, Resto]
---
# División euclídea (división entera)

> [!tip] En palabras sencillas
> La división "con resto" del colegio: $14=4\cdot3+2$. Lo importante es que **cociente y resto existen y son únicos** si exiges $0\le r<b$.

> [!important] Teorema 5.43
> Sean $a,b\in\mathbb Z$ con $b>0$. Existen $q,r\in\mathbb Z$ **únicos** tales que
> $$a=qb+r,\qquad0\le r<b.$$
> $q$ es el **cociente** y $r$ el **resto**. (Si $b<0$: $0\le r<|b|$.)

> [!abstract] Demostración (idea y pasos)
> **Existencia:** el conjunto $\{nb\mid nb\le a\}$ está acotado superiormente, así que tiene **máximo** $qb$ ([[Orden en los enteros|Prop. 5.41]]). Entonces $qb\le a<(q+1)b$, y $r=a-qb$ cumple $0\le r<b$.
> **Unicidad:** si $qb+r=q'b+r'$, entonces $b(q-q')=r'-r$ con $-b<r'-r<b$. El único múltiplo de $b$ en ese intervalo es 0: $r=r'$ y luego $q=q'$.

> [!example] Con negativos (¡cuidado con el resto!)
> | $a$ | $b$ | Cociente | Resto | Comprobación |
> |---|---|---|---|---|
> | 14 | 3 | 4 | 2 | $14=4\cdot3+2$ |
> | 14 | −3 | −4 | 2 | $14=(-4)(-3)+2$ |
> | −14 | 3 | **−5** | **1** | $-14=(-5)\cdot3+1$ |
> | −14 | −3 | 5 | 1 | $-14=5\cdot(-3)+1$ |
> Truco: divide los valores absolutos y luego ajusta para que **el resto sea $\ge0$**.

> [!warning] Error típico
> Decir que el resto de $-14$ entre $3$ es $-2$. El resto **nunca es negativo**.

## Conexiones
- **Necesitas antes:** [[Orden en los enteros]], [[Buen orden]]
- **Lleva a:** [[Ideales de Z]], [[Algoritmo de Euclides]], [[Congruencia módulo n]] ($a\equiv b\pmod n\iff$ mismo resto)
- **Se usa en:** [[Infinitud de los números primos]]
