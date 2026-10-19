---
tipo: teorema
tags: [teorema, conteo, cardinales]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "§5.2 · pp. 170-171"
aliases: [Palomar, Principio de Dirichlet, Principio de las cajas]
---
# Principio del palomar

> [!important] Enunciado (forma del libro)
> Si existe una aplicación **inyectiva** $[1,n]\to[1,m]$, entonces $n\le m$.
> Equivalentemente: si $n>m$, **toda** aplicación de un conjunto de $n$ elementos en uno de $m$ **repite alguna imagen**.

> [!tip] En palabras sencillas
> Si metes 10 palomas en 9 palomares, algún palomar tiene al menos 2 palomas. Parece obvio, pero es lo que garantiza que **contar** tiene sentido (que el cardinal de un conjunto finito es único).

> [!abstract] Demostración (idea y pasos) · inducción en $n$
> 1. **$n=1$:** obvio, $m\ge1$.
> 2. **Paso:** sea $f:[1,n+1]\to[1,m]$ inyectiva y $p=f(n+1)$.
> 3. Restringe $f$ a $[1,n]$: es inyectiva y no toma el valor $p$, así que va a $[1,m]\setminus\{p\}$.
> 4. "Cierra el hueco" con la biyección $h:[1,m]\setminus\{p\}\to[1,m-1]$ que deja fijo lo que está antes de $p$ y baja una unidad lo que está después.
> 5. $h\circ f|_{[1,n]}:[1,n]\to[1,m-1]$ es inyectiva; por hipótesis de inducción $n\le m-1$, o sea $n+1\le m$. ∎

> [!example] Aplicaciones
> - Entre 13 personas, dos cumplen años el mismo mes.
> - Si $n>m$ no hay aplicaciones inyectivas de un conjunto de $n$ elementos en uno de $m$; si $n<m$ no hay sobreyectivas.
> - Consecuencia: en conjuntos finitos del mismo tamaño, inyectiva ⇔ biyectiva ([[Conjunto finito|Teorema 5.14]]).

## Conexiones
- **Necesitas antes:** [[Aplicación inyectiva]], [[Principio de inducción]]
- **Se usa en:** [[Conjunto finito]] (cardinal bien definido), [[Cardinal]]
