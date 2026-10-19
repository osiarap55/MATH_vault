---
tipo: teorema
tags: [teorema, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Teoremas 3.59 y 3.60 · pp. 104-105"
aliases: [Inversa, Función inversa, f^-1, Inversa de la composición]
---
# Aplicación inversa

> [!tip] En palabras sencillas
> La inversa $f^{-1}$ "deshace" lo que hace $f$: si $f$ lleva $x$ a $y$, $f^{-1}$ lleva $y$ a $x$. **Solo existe si $f$ es biyectiva.**

> [!important] Teorema 3.59 (caracterización)
> $f:A\to B$ es biyectiva $\iff$ existe $g:B\to A$ tal que
> $$g\circ f=I_A\qquad\text{y}\qquad f\circ g=I_B.$$
> Esa $g$ es **única**, se llama $f^{-1}$ y también es biyectiva.

> [!abstract] Demostración (idea y pasos)
> **(⇒)** Si $f$ es biyectiva, la relación inversa $f^{-1}=\{(y,x)\mid f(x)=y\}$ es una aplicación (cada $y$ tiene un único $x$). Cumple las dos igualdades.
> **(⇐)** *Inyectiva:* si $f(x)=f(x')$, aplicando $g$: $x=g(f(x))=g(f(x'))=x'$. *Sobreyectiva:* dado $y$, el elemento $x=g(y)$ cumple $f(x)=f(g(y))=y$.

> [!important] Teorema 3.60 (inversa de una composición)
> Si $f:A\to B$ y $g:B\to C$ son biyectivas, $g\circ f$ es biyectiva y
> $$(g\circ f)^{-1}=f^{-1}\circ g^{-1}.$$
> **¡Se invierte el orden!** (Como ponerse calcetines y zapatos: para quitártelos, primero los zapatos.)

> [!abstract] Demostración
> Basta comprobar las dos composiciones con el Teorema 3.59, usando la asociatividad:
> $(g\circ f)\circ(f^{-1}\circ g^{-1})=g\circ(f\circ f^{-1})\circ g^{-1}=g\circ g^{-1}=I_C$, y análogo al revés.

> [!warning] Errores típicos
> - Confundir $f^{-1}(x)$ (inversa) con $\frac1{f(x)}$ (inverso multiplicativo). $\sin^{-1}x=\arcsin x\neq\frac1{\sin x}$.
> - Escribir $(g\circ f)^{-1}=g^{-1}\circ f^{-1}$ (orden equivocado).
> - Comprobar solo **una** de las dos composiciones. Hacen falta las dos (si no, solo tienes una [[Inversas laterales|inversa lateral]]).

## Conexiones
- **Necesitas antes:** [[Aplicación biyectiva]], [[Composición de aplicaciones]]
- **Lleva a:** [[Inversas laterales]], [[Conjuntos equipotentes]]
- **Misma estructura que:** el elemento simétrico en un [[Grupo]] ($(ab)^{-1}=b^{-1}a^{-1}$)
