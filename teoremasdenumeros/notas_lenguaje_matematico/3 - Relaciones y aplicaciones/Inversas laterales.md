---
tipo: teorema
tags: [teorema, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Teorema 3.61 · pp. 105-106"
aliases: [Inversa por la izquierda, Inversa por la derecha, Sección, Retracción]
---
# Inversas laterales

> [!tip] En palabras sencillas
> - Si $f$ es **inyectiva**, la puedes "deshacer" **después** de aplicarla: hay una $g$ con $g\circ f=I_A$.
> - Si $f$ es **sobreyectiva**, la puedes "deshacer" **antes**: hay una $h$ con $f\circ h=I_B$.
> - Si tiene las dos, es biyectiva y ambas coinciden con $f^{-1}$.

> [!important] Teorema 3.61
> Sea $f:A\to B$ (con $A\neq\emptyset$).
> 1. $f$ es **sobreyectiva** $\iff$ existe $h:B\to A$ con $f\circ h=I_B$ (*inversa por la derecha*).
> 2. $f$ es **inyectiva** $\iff$ existe $g:B\to A$ con $g\circ f=I_A$ (*inversa por la izquierda*).

> [!abstract] Demostración (idea y pasos)
> **1. (⇒)** Como $f$ es sobreyectiva, cada $f^{-1}(y)$ es no vacío. **Elige** un $c_y\in f^{-1}(y)$ para cada $y$ y define $h(y)=c_y$. Entonces $f(h(y))=y$. *(Elegir a la vez un elemento de cada conjunto, posiblemente infinitos, es usar el [[Axioma de elección]].)*
> **1. (⇐)** Dado $y$, el elemento $h(y)$ cumple $f(h(y))=y$.
> **2. (⇒)** Si $y\in f(A)$, su antiimagen tiene un único elemento $a_y$: define $g(y)=a_y$. Si $y\notin f(A)$, define $g(y)=x_0$ (un elemento fijo cualquiera). Entonces $g(f(x))=x$.
> **2. (⇐)** Si $f(x_1)=f(x_2)$, aplica $g$: $x_1=x_2$.

> [!note] Consecuencias
> - La $h$ del apartado 1 es inyectiva; la $g$ del 2 es sobreyectiva.
> - Toda inyectiva $f:A\to B$ es una **biyección** $A\to f(A)$. Así se "**sumerge**" $A$ en $B$: por ejemplo $\mathbb N\hookrightarrow\mathbb Z$ o $\mathbb Z\hookrightarrow\mathbb Q$ ($z\mapsto\frac z1$).

> [!example] Ejemplo
> $f:\mathbb N\to\mathbb N$, $f(n)=n+1$ es inyectiva no sobreyectiva. Una inversa por la izquierda: $g(m)=m-1$ si $m\ge1$, $g(0)=0$. Pero $f\circ g\neq I$ ($f(g(0))=1$).

## Conexiones
- **Necesitas antes:** [[Aplicación inyectiva]], [[Aplicación sobreyectiva]], [[Composición de aplicaciones]]
- **Usa:** [[Axioma de elección]]
- **Relacionado:** [[Aplicación inversa]]
