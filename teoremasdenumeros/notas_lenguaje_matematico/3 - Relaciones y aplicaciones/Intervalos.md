---
tipo: definición
tags: [definicion, orden, reales]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.18 y 3.20 · pp. 84-85; §6.5"
aliases: [Intervalo, Intervalo abierto, Intervalo cerrado, Semirrecta, Intervalos en R]
---
# Intervalos

> [!tip] En palabras sencillas
> Un intervalo es "todo lo que hay entre $a$ y $b$" según un orden. Con corchete $[\ ]$ incluyes el extremo; con paréntesis $(\ )$, no.

> [!note] Definición (en cualquier conjunto ordenado $(U,\preceq)$, con $a\preceq b$)
> | Nombre | Notación | Conjunto |
> |---|---|---|
> | Abierto | $(a,b)$ | $\{x\mid a\prec x\prec b\}$ |
> | Cerrado | $[a,b]$ | $\{x\mid a\preceq x\preceq b\}$ |
> | Semiabiertos | $(a,b]$, $[a,b)$ | uno de los extremos incluido |
> | Inicial | $(\leftarrow,a)$, $(\leftarrow,a]$ | $\{x\mid x\prec a\}$, $\{x\mid x\preceq a\}$ |
> | Final | $(a,\rightarrow)$, $[a,\rightarrow)$ | $\{x\mid a\prec x\}$, $\{x\mid a\preceq x\}$ |
>
> En $\mathbb R$ los iniciales/finales son las **semirrectas** $(-\infty,a)$, $[a,+\infty)$, etc.

> [!example] El mismo intervalo en conjuntos distintos
> - $[3,6]_{\mathbb N}=\{3,4,5,6\}$; $(1,2)_{\mathbb N}=\emptyset$.
> - $(-3,5]_{\mathbb Z}=\{-2,-1,0,\dots,5\}$.
> - $(-3,4]_{\mathbb Q}=(-3,4]\cap\mathbb Q$.
> - En $\mathbb R$, $[a,b]$ es un segmento "sin huecos" (eso es lo especial de $\mathbb R$, ver [[Axioma del supremo]]).

> [!important] Caracterización en $\mathbb R$ (cap. 6)
> Un subconjunto $I\subseteq\mathbb R$ es un intervalo si y sólo si: $x,y\in I$ y $x<z<y$ ⇒ $z\in I$ ("si contiene dos puntos, contiene todo lo de en medio").

> [!warning] Errores típicos
> - $(a,a)=\emptyset$ pero $[a,a]=\{a\}$.
> - $\infty$ no es un número: nunca se pone corchete en $\infty$.

## Conexiones
- **Necesitas antes:** [[Relación de orden]]
- **Se usa en:** [[Cotas de un conjunto]], [[Familias de conjuntos]] (intervalos encajados), [[Números reales]], [[Valor absoluto]] ($|x-a|<r\iff x\in(a-r,a+r)$)
