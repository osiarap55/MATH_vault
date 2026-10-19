---
tipo: teorema
tags: [teorema, algebra, combinatoria]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Prop. 4.21.3 · pp. 134-135; Ejercicio 19"
aliases: [Fórmula del binomio, Binomio, Newton]
---
# Binomio de Newton

> [!important] Teorema
> En un anillo **conmutativo**, para todo $n\in\mathbb N^*$:
> $$(a+b)^n=\sum_{k=0}^n\binom nk a^{n-k}b^k=\binom n0a^n+\binom n1a^{n-1}b+\cdots+\binom n{n-1}ab^{n-1}+\binom nnb^n$$

> [!tip] En palabras sencillas
> Al desarrollar $(a+b)(a+b)\cdots(a+b)$ ($n$ veces), cada término sale de elegir de cada paréntesis $a$ o $b$. El término $a^{n-k}b^k$ aparece tantas veces como formas hay de elegir **en qué $k$ paréntesis** coges la $b$: $\binom nk$ ([[Número combinatorio]]).

> [!abstract] Demostración (idea y pasos) · [[Principio de inducción|inducción]] en $n$
> 1. **Base** $n=1$: $(a+b)^1=a+b$ ✓.
> 2. **Paso:** supón la fórmula para $n$. Entonces $(a+b)^{n+1}=(a+b)^n(a+b)$. Multiplica cada término por $a$ y por $b$ (aquí se usa la **conmutatividad**).
> 3. Agrupa los términos con $a^{n+1-k}b^k$: su coeficiente es $\binom nk+\binom n{k-1}$.
> 4. Usa la **fórmula de Pascal** $\binom nk+\binom n{k-1}=\binom{n+1}k$ y que $\binom n0=\binom{n+1}0=1=\binom nn=\binom{n+1}{n+1}$. ∎

> [!example] Ejemplos y consecuencias (Ejercicio 19)
> - $(a+b)^3=a^3+3a^2b+3ab^2+b^3$.
> - Con $a=b=1$: $\displaystyle\sum_{k=0}^n\binom nk=2^n$ (número total de subconjuntos, ver [[Conjunto de las partes]]).
> - Con $a=1$, $b=-1$: $\displaystyle\sum_{k=0}^n(-1)^k\binom nk=0$.

> [!warning] Error típico
> **No vale para matrices** (ni en anillos no conmutativos): $(A+B)^2=A^2+AB+BA+B^2$.

## Conexiones
- **Necesitas antes:** [[Anillo]], [[Principio de inducción]], [[Número combinatorio]]
- **Se usa en:** [[Fórmula de De Moivre]] (para sacar fórmulas de $\cos n\theta$, $\sin n\theta$)
