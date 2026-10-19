---
tipo: teorema
tags: [teorema, logica, numeros]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "Ejercicio 1.10 · p. 17"
aliases: [Teorema de Euclides, Hay infinitos primos, Existen infinitos números primos]
---
# Hay infinitos números primos (Euclides)

> [!important] Teorema
> El conjunto de los números primos es infinito.

> [!tip] En palabras sencillas
> Dame cualquier lista finita de primos. Multiplícalos todos y suma 1. Ese número no es divisible por ninguno de tu lista, así que tiene un primo que **no estaba** en ella.

> [!abstract] Demostración (idea y pasos) · [[Reducción al absurdo]]
> 1. Supón que solo hay un número finito de primos: $p_1,p_2,\dots,p_n$.
> 2. Considera $N=p_1p_2\cdots p_n+1$.
> 3. Al dividir $N$ entre cualquier $p_i$ el resto es $1$, así que **ningún $p_i$ divide a $N$**.
> 4. Pero $N\ge 2$, y todo número $\ge 2$ tiene al menos un divisor primo ([[Teorema fundamental de la aritmética]]). Ese primo no está en la lista.
> 5. **Contradicción** con que la lista contenía todos los primos. ∎

> [!warning] Error típico (¡el libro lo dice un poco deprisa!)
> **No** se demuestra que $N$ sea primo. $2\cdot3\cdot5\cdot7\cdot11\cdot13+1=30031=59\cdot509$ no es primo. Lo que se demuestra es que $N$ tiene un factor primo **nuevo**.

## Conexiones
- **Usa:** [[Reducción al absurdo]], [[División euclídea]], [[Teorema fundamental de la aritmética]]
- **Relacionado:** [[Números primos]], [[Conjunto infinito]]
