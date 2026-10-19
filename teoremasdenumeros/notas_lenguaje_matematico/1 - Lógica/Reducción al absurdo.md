---
tipo: método
tags: [metodo, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · p. 17; Comentarios · p. 30"
aliases: [Ley de reducción al absurdo, Demostración por contradicción, Absurdo]
---
# Reducción al absurdo

> [!tip] En palabras sencillas
> Quieres probar $p$. Supones que es **falsa** y razonas hasta llegar a algo **imposible** (una cosa y su contraria). Como lo imposible no puede pasar, tu suposición era errónea: $p$ es verdadera.

> [!important] Ley lógica
> $$\neg p\to(q\land\neg q)\iff p$$
> Si de $\neg p$ se deduce una contradicción, entonces $p$.

> [!abstract] Por qué funciona
> $q\land\neg q$ es siempre falsa ([[Tercio excluso y no contradicción|no contradicción]]). Un condicional con consecuente falso solo es verdadero si el antecedente es falso: $\neg p=0$, es decir, $p=1$.

> [!note] Esquema para demostrar $H\Rightarrow C$
> 1. Supón $H$ **y** $\neg C$.
> 2. Deduce cosas hasta obtener una contradicción (algo que contradiga $H$, una propiedad conocida, o una suposición propia).
> 3. Concluye $C$.

> [!example] Ejemplos clásicos
> - [[Irracionalidad de raíz de 2]]
> - [[Infinitud de los números primos]]
> - [[Unicidad del límite de una sucesión]]

> [!warning] Errores típicos
> - Negar mal lo que quieres probar. Negar "existe un único $x$" es "no existe ninguno **o** existen al menos dos".
> - Llegar a una contradicción **sin usar** la suposición $\neg C$: entonces el error está en otro sitio.
> - Abusar: si al final tu prueba es "supongo $\neg C$… [prueba directa de $C$]… contradicción", mejor escríbela directa.

## Conexiones
- **Necesitas antes:** [[Tercio excluso y no contradicción]], [[Tautología y contradicción]]
- **Lleva a:** [[Validación por refutación]]
- **Se usa en:** [[Irracionalidad de raíz de 2]], [[Infinitud de los números primos]], [[Unicidad del límite de una sucesión]], [[Teorema de Cantor]], [[Insuficiencia de los racionales]]
