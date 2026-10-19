---
tipo: teorema
tags: [teorema, cardinales]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Comentarios cap. 2 (paradoja de Cantor) y cap. 3; Ejercicio 19"
aliases: [Argumento diagonal de Cantor, card A < card P(A), Diagonal de Cantor]
---
# Teorema de Cantor  ($\operatorname{card}A<\operatorname{card}\mathcal P(A)$)

> [!important] Enunciado
> Para todo conjunto $A$, **no existe ninguna aplicación sobreyectiva** $f:A\to\mathcal P(A)$. Como $x\mapsto\{x\}$ es inyectiva, se tiene
> $$\operatorname{card}A<\operatorname{card}\mathcal P(A).$$

> [!tip] En palabras sencillas
> El conjunto de los subconjuntos de $A$ es **siempre más grande** que $A$, incluso si $A$ es infinito. Por tanto **hay infinitos de distintos tamaños**, y no hay un "infinito máximo".

> [!abstract] Demostración (idea y pasos) · [[Reducción al absurdo]] + argumento diagonal
> 1. Supón que $f:A\to\mathcal P(A)$ es sobreyectiva.
> 2. Define el conjunto "diagonal" $D=\{x\in A\mid x\notin f(x)\}\subseteq A$.
> 3. Como $f$ es sobreyectiva, $D=f(d)$ para algún $d\in A$.
> 4. ¿Es $d\in D$? Si $d\in D$, por definición $d\notin f(d)=D$. Si $d\notin D=f(d)$, entonces cumple la condición y $d\in D$.
> 5. **Contradicción** en ambos casos. ∎
>
> Es el mismo truco que la [[Paradoja de Russell]].

> [!note] Ojo con el nombre
> El libro llama "teorema de Cantor" a otro resultado: que dos cardinales siempre son comparables (equivalente al [[Axioma de elección]]). El nombre más habitual es el de esta nota.

> [!example] Consecuencias
> - $\aleph_0=\operatorname{card}\mathbb N<\operatorname{card}\mathcal P(\mathbb N)=\mathfrak c=\operatorname{card}\mathbb R$: **$\mathbb R$ no es numerable**.
> - No existe el "conjunto de todos los conjuntos" (paradoja de Cantor).

## Conexiones
- **Necesitas antes:** [[Conjunto de las partes]], [[Aplicación sobreyectiva]], [[Reducción al absurdo]]
- **Lleva a:** [[Cardinal]], [[Conjunto numerable]], [[Paradoja de Russell]]
