---
tipo: teorema
tags: [teorema, logica, inferencia]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.5 · p. 22; Ejercicio 4d"
aliases: [Ley del silogismo, Leyes transitivas, Transitividad de la implicación]
---
# Silogismo hipotético (transitividad)

> [!tip] En palabras sencillas
> Las implicaciones se pueden **encadenar**: si de $p$ sale $q$ y de $q$ sale $r$, entonces de $p$ sale $r$. Es lo que hace cualquier demostración larga.

> [!important] Enunciado
> $$(p\to q)\land(q\to r)\ \Rightarrow\ (p\to r)$$
> $$(p\leftrightarrow q)\land(q\leftrightarrow r)\ \Rightarrow\ (p\leftrightarrow r)$$

> [!abstract] Demostración (por refutación, ejemplo 1.16 del libro)
> 1. Supón que es falsa. Un condicional solo es falso si antecedente = 1 y consecuente = 0.
> 2. Entonces $p\to q=1$, $q\to r=1$ y $p\to r=0$.
> 3. $p\to r=0$ obliga a $p=1$, $r=0$.
> 4. De $p=1$ y $p\to q=1$: $q=1$ ([[Modus ponens]]).
> 5. De $q=1$ y $q\to r=1$: $r=1$. Pero $r=0$. **Contradicción**, luego es una tautología.

> [!example] Ejemplo
> "$n$ múltiplo de 4 ⇒ $n$ par" y "$n$ par ⇒ $n^2$ par". Luego "$n$ múltiplo de 4 ⇒ $n^2$ par".

## Conexiones
- **Necesitas antes:** [[Condicional]], [[Modus ponens]]
- **Se usa en:** [[Demostración directa]] (encadenar pasos intermedios)
- **Misma idea en relaciones:** la propiedad [[Propiedades de una relación|transitiva]]
