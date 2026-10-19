---
tipo: teorema
tags: [definicion, teorema, cardinales, conteo]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "§5.2 · pp. 170-180; Def. 5.8, Prop. 5.9-5.23, Teorema 5.14"
aliases: [Conjuntos finitos, Cardinal finito, Número de elementos, Cardinal de la unión, Cardinal del producto, Inclusión-exclusión]
---
# Conjunto finito

> [!tip] En palabras sencillas
> Un conjunto es finito si puedes **contar** sus elementos y terminar: numerarlos $1,2,\dots,n$. Ese $n$ (su cardinal) está bien definido: no puedes contar el mismo conjunto y obtener dos resultados distintos.

> [!note] Definición 5.8
> $A$ es **finito** si $A=\emptyset$ o existe una biyección $A\to[1,n]_{\mathbb N}=\{1,\dots,n\}$ para algún $n\ge1$. Entonces $\operatorname{card}A=n$. Si no, $A$ es **infinito**.

> [!important] Resultados clave
> 1. Si hay una inyección $[1,n]\to[1,m]$, entonces $n\le m$. ([[Principio del palomar]].) Por tanto **el cardinal está bien definido** (Prop. 5.9).
> 2. Un subconjunto de $\mathbb N$ es finito $\iff$ está **acotado** (Prop. 5.10). ⇒ **$\mathbb N$ es infinito.**
> 3. Si $A\subsetneq B$ con $B$ finito: $A$ es finito y $\operatorname{card}A<\operatorname{card}B$ (Prop. 5.11). *Una parte propia es estrictamente menor.*
> 4. $\operatorname{card}f(A)\le\operatorname{card}A$, con igualdad $\iff f$ inyectiva (Prop. 5.12).
> 5. **Teorema 5.14:** si $\operatorname{card}A=\operatorname{card}B$ (finitos) y $f:A\to B$: **inyectiva $\iff$ sobreyectiva $\iff$ biyectiva**.

> [!important] Fórmulas de conteo
> | Fórmula | Prop. |
> |---|---|
> | $\operatorname{card}(A\cup B)=\operatorname{card}A+\operatorname{card}B$ si $A\cap B=\emptyset$ | 5.15 |
> | $\operatorname{card}(A\cup B)+\operatorname{card}(A\cap B)=\operatorname{card}A+\operatorname{card}B$ (**inclusión-exclusión**) | 5.16 |
> | $\operatorname{card}(A\times B)=\operatorname{card}A\cdot\operatorname{card}B$ | 5.17 |
> | $\operatorname{card}(B^A)=b^a$ (aplicaciones) | 5.18 |
> | $\operatorname{card}\mathcal P(A)=2^{\operatorname{card}A}$ | 5.20 |
> | inyecciones: $m(m-1)\cdots(m-n+1)=V_{m,n}$ | 5.21 |
> | biyecciones: $n!$ | 5.22 |
> | subconjuntos de $n$ elementos: $\binom mn$ | 5.23 |
> Más en [[Número combinatorio]].

> [!abstract] Idea de la prueba de $|\mathcal P(A)|=2^n$ (otra vez)
> Cada subconjunto $B$ se corresponde con su **función característica** $\chi_B:A\to\{0,1\}$. Esa correspondencia es biyectiva, y hay $2^n$ aplicaciones $A\to\{0,1\}$.

> [!example] Ejemplos
> - Quinielas de 14 partidos con 1, X, 2: aplicaciones $\{1..14\}\to\{1,X,2\}$: $3^{14}$.
> - Diagonales de un polígono de $n$ lados: $\binom n2-n$ (pares de vértices menos los lados).

> [!failure] El Teorema 5.14 falla en infinitos
> $n\mapsto n+1$ y $n\mapsto2n$ son inyectivas $\mathbb N\to\mathbb N$ y no sobreyectivas. Ver [[Conjunto infinito]].

## Conexiones
- **Necesitas antes:** [[Cardinal]], [[Orden en los naturales]], [[Principio de inducción]]
- **Lleva a:** [[Principio del palomar]], [[Conjunto infinito]], [[Número combinatorio]]
- **Se usa en:** [[LM Ejercicios Cap 4#Ejercicio 6 · Íntegro y finito implica cuerpo|íntegro y finito ⇒ cuerpo]]
