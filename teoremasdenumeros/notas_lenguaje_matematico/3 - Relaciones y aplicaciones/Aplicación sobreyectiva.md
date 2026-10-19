---
tipo: definición
tags: [definicion, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.52 y Prop. 3.56 · pp. 101-103"
aliases: [Sobreyectiva, Sobreyección, Suprayectiva, Exhaustiva, Epiyectiva]
---
# Aplicación sobreyectiva

> [!tip] En palabras sencillas
> **Todo el conjunto final se alcanza**: a cada elemento de $B$ le llega al menos una flecha. En una gráfica de $\mathbb R$: toda recta horizontal la corta **al menos una vez**.

> [!note] Definición
> $f:A\to B$ es **sobreyectiva** si $f(A)=B$, es decir,
> $$\forall y\in B\ \ \exists x\in A:\ f(x)=y.$$

> [!tip] Cómo se demuestra
> Toma $y\in B$ **arbitrario** y **resuelve** la ecuación $f(x)=y$ (basta encontrar una solución).
> Ejemplo: $f(x)=x^3-x$ es sobreyectiva en $\mathbb R$ porque $x^3-x-y=0$ es un polinomio de grado impar y siempre tiene una raíz real.
>
> **Cómo se refuta:** encuentra un $y$ que no se alcance. $x^2$ no es sobreyectiva en $\mathbb R$: $-1$ no es un cuadrado.

> [!important] Proposición 3.56
> Si $f$ y $g$ son sobreyectivas, $g\circ f$ es sobreyectiva: $g(f(A))=g(B)=C$.
> Además: si $g\circ f$ es sobreyectiva, entonces **$g$** es sobreyectiva (la de "fuera").

> [!example] Ejemplos
> - ✓ $x^3-x$, $ax+b$ ($a\neq0$), la proyección canónica $p:A\to A/\!\sim$.
> - ✗ $x^2$ y $2^x$ en $\mathbb R$ (no alcanzan los negativos), $n\mapsto n+1$ en $\mathbb N$ (no alcanza el 0).
> - Toda aplicación es sobreyectiva **sobre su imagen**: $f:A\to f(A)$.

> [!warning] Errores típicos
> - Olvidar que depende del **conjunto final**: $x^2:\mathbb R\to[0,\infty)$ sí es sobreyectiva.

## Conexiones
- **Necesitas antes:** [[Aplicación]], [[Cuantificadores]]
- **Lleva a:** [[Aplicación biyectiva]], [[Inversas laterales]] (sobreyectiva ⇔ tiene inversa por la derecha, usando el [[Axioma de elección]])
