---
tipo: definición
tags: [definicion, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.54 y Prop. 3.56 · pp. 102-103"
aliases: [Inyectiva, Inyección, Aplicación inyectiva, Uno a uno, Inmersión]
---
# Aplicación inyectiva

> [!tip] En palabras sencillas
> **No hay dos elementos que vayan al mismo sitio.** Cada flecha llega a un destino distinto. En una gráfica de $\mathbb R$: toda recta horizontal la corta **como mucho una vez**.

> [!note] Definición
> $f:A\to B$ es **inyectiva** si
> $$\forall x,x'\in A:\quad f(x)=f(x')\ \Rightarrow\ x=x'$$
> o, equivalentemente ([[Recíproco y contrarrecíproco|contrarrecíproco]]), $x\neq x'\Rightarrow f(x)\neq f(x')$.

> [!tip] Cómo se demuestra
> **Supón $f(x)=f(x')$ y llega a $x=x'$.** Es más fácil que la forma "$x\neq x'\Rightarrow\dots$".
> Ejemplo: $f(x)=2^x$. Si $2^x=2^{x'}$, entonces $2^{x-x'}=1$, luego $x-x'=0$. ✓
>
> **Cómo se refuta:** da dos elementos distintos con la misma imagen: $x^2$ no es inyectiva en $\mathbb R$ porque $f(-1)=f(1)$.

> [!important] Proposición 3.56
> Si $f$ y $g$ son inyectivas, $g\circ f$ es inyectiva.
> *Pasos:* $g(f(x))=g(f(y))\overset{g\text{ iny.}}\Rightarrow f(x)=f(y)\overset{f\text{ iny.}}\Rightarrow x=y$.
>
> Además: si $g\circ f$ es inyectiva, entonces **$f$** es inyectiva (la de "dentro").

> [!example] Ejemplos
> - ✓ $2^x$, $x^3$, $ax+b$ ($a\neq0$), $n\mapsto n+1$ en $\mathbb N$, $x\mapsto\{x\}$ de $U$ en $\mathcal P(U)$.
> - ✗ $x^2$ en $\mathbb R$, $\sin x$, cualquier constante (si $A$ tiene ≥2 elementos).
> - Si $A$ y $B$ son finitos con $n$ y $m$ elementos: hay inyecciones $A\to B$ solo si $n\le m$, y hay $m(m-1)\cdots(m-n+1)$ ([[Cardinal]]).

> [!warning] Errores típicos
> - Confundir con la definición de aplicación: "a cada $x$ una sola imagen" es ser **aplicación**; "a cada imagen un solo $x$" es ser **inyectiva**.
> - La inyectividad depende del dominio: $x^2$ es inyectiva en $[0,\infty)$.

## Conexiones
- **Necesitas antes:** [[Aplicación]], [[Recíproco y contrarrecíproco]]
- **Lleva a:** [[Aplicación biyectiva]], [[Inversas laterales]] (inyectiva ⇔ tiene inversa por la izquierda)
- **Se usa en:** [[Cardinal]] (orden entre cardinales), [[Teorema de Cantor-Bernstein]], [[Homomorfismo]] (monomorfismos)
