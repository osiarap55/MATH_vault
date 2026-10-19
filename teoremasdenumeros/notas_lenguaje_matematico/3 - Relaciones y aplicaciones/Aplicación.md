---
tipo: definición
tags: [definicion, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.37 · pp. 94-99"
aliases: [Función, Aplicaciones, Dominio, Conjunto imagen, Recorrido, Aplicación identidad, Aplicación constante, Restricción, Extensión, Sucesión, Función característica]
---
# Aplicación (función)

> [!tip] En palabras sencillas
> Una aplicación $f:A\to B$ es una **máquina** que a cada elemento de $A$ le asigna **uno y solo uno** de $B$. Ningún elemento de $A$ se queda sin imagen y ninguno tiene dos.

> [!note] Definición
> Una **aplicación** de $A$ en $B$ es una [[Relación binaria|relación]] $f\subseteq A\times B$ tal que
> $$\forall x\in A\ \ \exists!\,y\in B:\ (x,y)\in f.$$
> Se escribe $f(x)=y$.
> - $A$ = **dominio** (conjunto inicial). $B$ = **conjunto final**.
> - $f(A)=\{f(x)\mid x\in A\}$ = **imagen** o recorrido, $\operatorname{Im}(f)$.
> - $\mathcal F(A,B)=B^A$ = conjunto de todas las aplicaciones de $A$ en $B$.
> - **Igualdad:** $f=g$ si tienen el **mismo dominio, mismo conjunto final** y $f(x)=g(x)$ para todo $x$.

> [!example] Ejemplos
> - **Identidad** $I_A(x)=x$. **Constante** $f(x)=c$.
> - **Proyección canónica** $p:A\to A/\!\sim$, $p(x)=[x]$ ([[Conjunto cociente]]).
> - **Sucesión** = aplicación $\mathbb N\to A$: $n\mapsto a_n$.
> - **Función característica** de $A\subseteq U$: $\chi_A(x)=1$ si $x\in A$, $0$ si no.
> - Una **tabla de verdad** con 3 variables es una aplicación $\{0,1\}^3\to\{0,1\}$.
> - **Restricción:** $g=f|_{[0,\infty)}$ es una función **distinta** de $f$ aunque tenga la misma fórmula (cambia el dominio).

> [!failure] No son aplicaciones
> - $x=y^2$ en $\mathbb R$: a $x=4$ le corresponden $y=\pm2$ y a $x=-1$ ninguno.
> - $\mathcal P(U)\to U$, "$A\mapsto$ un elemento de $A$": a $\emptyset$ no le corresponde nada.
> - Si $A\neq\emptyset$, **no hay aplicaciones** $A\to\emptyset$. Pero hay exactamente una $\emptyset\to B$ (la vacía).

> [!warning] Errores típicos
> - Dar una fórmula sin decir dominio: por convenio, se toma el **mayor** subconjunto de $\mathbb R$ donde la fórmula tiene sentido (campo de existencia).
> - Confundir **conjunto final** $B$ con **imagen** $f(A)$. Si coinciden, $f$ es [[Aplicación sobreyectiva|sobreyectiva]].
> - La relación inversa $f^{-1}$ de una aplicación **no tiene por qué ser una aplicación** (ver [[Aplicación inversa]]).

## Conexiones
- **Necesitas antes:** [[Relación binaria]], [[Cuantificadores]]
- **Lleva a:** [[Imagen y antiimagen]], [[Composición de aplicaciones]], [[Aplicación inyectiva]], [[Aplicación sobreyectiva]], [[Aplicación biyectiva]]
- **Se usa en:** [[Operación interna]] (es una aplicación $A\times A\to A$), [[Homomorfismo]]
