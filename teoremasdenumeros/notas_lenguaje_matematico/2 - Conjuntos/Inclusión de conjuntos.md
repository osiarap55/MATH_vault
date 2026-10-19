---
tipo: definición
tags: [definicion, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.1 · pp. 35-36"
aliases: [Subconjunto, Inclusión, Doble inclusión, ⊆, Contenido]
---
# Inclusión de conjuntos  $B\subseteq A$

> [!tip] En palabras sencillas
> $B\subseteq A$ significa que **todo lo que está en $B$ está también en $A$**: $B$ es un "trozo" de $A$.

> [!note] Definición
> $$B\subseteq A\iff(\forall x)\,(x\in B\to x\in A)$$
> Se lee "$B$ está incluido en $A$", "$B$ es subconjunto de $A$" o "$A$ contiene a $B$" ($A\supseteq B$).
> El libro escribe $B\subset A$ para lo mismo (inclusión, no necesariamente estricta).

> [!important] Igualdad por doble inclusión
> $$A=B\iff A\subseteq B\ \text{ y }\ B\subseteq A$$
> **Método para demostrar $A=B$:**
> 1. Toma $x\in A$ **arbitrario** y demuestra $x\in B$.
> 2. Toma $x\in B$ **arbitrario** y demuestra $x\in A$.
>
> Es la versión para conjuntos de la [[Bicondicional|ley del bicondicional]].

> [!example] Ejemplos
> - $\{\text{sábado},\text{domingo}\}\subseteq\{\text{días de la semana}\}$.
> - Potencias de 2 (mayores que 1) $\subseteq$ números pares.
> - $\emptyset\subseteq A$ para todo $A$ (la implicación "$x\in\emptyset\to x\in A$" es verdadera porque el antecedente es siempre falso).
> - $A\subseteq A$.

> [!abstract] Propiedades
> - Reflexiva: $A\subseteq A$. Antisimétrica: $A\subseteq B$ y $B\subseteq A$ ⇒ $A=B$. Transitiva: $A\subseteq B\subseteq C$ ⇒ $A\subseteq C$.
> - Es decir, $\subseteq$ es una [[Relación de orden]] en $\mathcal P(U)$ (no total).
> - $A\subseteq B\iff A\cup B=B\iff A\cap B=A$ (ver [[Unión e intersección]]).

> [!warning] Errores típicos
> - Confundir $\in$ con $\subseteq$: $\{1\}\subseteq\{1,2\}$ pero $\{1\}\notin\{1,2\}$.
> - Demostrar solo **una** inclusión y decir que son iguales.
> - Probar la inclusión con un ejemplo concreto de $x$: hay que tomar $x$ **arbitrario**.

## Conexiones
- **Necesitas antes:** [[Conjunto]], [[Condicional]], [[Cuantificadores]]
- **Lleva a:** [[Conjunto de las partes]], [[Álgebra de conjuntos]], [[Relación de orden]]
- **Se usa en:** casi todas las demostraciones del capítulo ([[Producto cartesiano]], [[Diferencia y complementario]])
