---
tipo: definición
tags: [definicion, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.48 · pp. 99-100"
aliases: [Composición, Aplicación compuesta, g∘f, Función compuesta]
---
# Composición de aplicaciones  $g\circ f$

> [!tip] En palabras sencillas
> Encadenar máquinas: primero aplicas $f$ y al resultado le aplicas $g$. Se escribe $g\circ f$ ("$g$ después de $f$"): **se lee de derecha a izquierda**.

> [!note] Definición
> Si $f:A\to B$ y $g:B\to C$, la composición es $g\circ f:A\to C$,
> $$(g\circ f)(x)=g(f(x)).$$

> [!important] Propiedades
> 1. **Asociativa:** $(h\circ g)\circ f=h\circ(g\circ f)$. Por eso se escribe $h\circ g\circ f$ sin paréntesis.
> 2. **Neutro:** $f\circ I_A=f$ y $I_B\circ f=f$.
> 3. **NO conmutativa:** en general $g\circ f\neq f\circ g$ (¡y a veces una de ellas ni existe!).
>
> En $\mathcal F(A)$ (aplicaciones de $A$ en $A$), $\circ$ es una [[Operación interna]] asociativa con neutro $I_A$. Se escribe $f^n=f\circ\cdots\circ f$.

> [!abstract] Demostración de la asociativa
> Para todo $x$: $[h\circ(g\circ f)](x)=h(g(f(x)))=[(h\circ g)\circ f](x)$. ∎

> [!example] Ejemplo de no conmutatividad
> $f(x)=x+1$, $g(x)=x^2$: $(g\circ f)(x)=(x+1)^2$ pero $(f\circ g)(x)=x^2+1$.
> Con constantes $f\equiv a$, $g\equiv b$ ($a\neq b$): $g\circ f\equiv b$ y $f\circ g\equiv a$.

> [!warning] Errores típicos
> - Leer $g\circ f$ de izquierda a derecha (aplicar $g$ primero).
> - Componer sin comprobar que la imagen de $f$ cae dentro del dominio de $g$.

## Conexiones
- **Necesitas antes:** [[Aplicación]]
- **Lleva a:** [[Aplicación inversa]], [[Inversas laterales]]
- **Se usa en:** [[Aplicación inyectiva]] y [[Aplicación sobreyectiva]] (la composición conserva ambas), [[Grupo]] (las biyecciones de un conjunto forman un grupo con $\circ$)
- **Generaliza:** [[Relación binaria|composición de relaciones]]
