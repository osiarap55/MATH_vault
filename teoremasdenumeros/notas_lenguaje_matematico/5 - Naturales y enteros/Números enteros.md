---
tipo: teorema
tags: [definicion, teorema, enteros]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Ejemplo 3.8; §5.4 · pp. 186-193; Teorema 5.38"
aliases: [Z, ℤ, Enteros, Construcción de Z, Construcción de los enteros, Representante canónico]
---
# Números enteros  $\mathbb Z$

> [!tip] En palabras sencillas
> En $\mathbb N$ no se puede restar siempre ($3-5$). La idea: **un entero es "una resta pendiente"** $a-b$, representada por el par $(a,b)$. Como $5-3=7-5=\dots$, varios pares representan el mismo entero: por eso se usa una **relación de equivalencia**.

> [!note] Construcción (Def. 5.35)
> En $\mathbb N\times\mathbb N$:
> $$(a,b)\sim(a',b')\iff a+b'=a'+b\qquad(\text{"}a-b=a'-b'\text{" sin restar})$$
> $\mathbb Z=(\mathbb N\times\mathbb N)/\!\sim$. Cada clase tiene un **representante canónico** con una componente nula: $(m,0)$ (el entero $m$) o $(0,n)$ (el entero $-n$).
> Dibujo: cada clase son los puntos de una recta paralela a la diagonal $y=x$.

> [!note] Operaciones (Def. 5.36)
> $$[(a,b)]+[(c,d)]=[(a+c,\,b+d)]\qquad[(a,b)]\cdot[(c,d)]=[(ac+bd,\,bc+ad)]$$
> (Piensa: $(a-b)(c-d)=ac+bd-(bc+ad)$.) Hay que comprobar que **no dependen de los representantes**.

> [!important] Teorema 5.38 y siguientes
> - $(\mathbb Z,+,\cdot)$ es un [[Anillo]] **conmutativo unitario**: neutro $0=[(0,0)]$, opuesto $-[(a,b)]=[(b,a)]$, unidad $1=[(1,0)]$.
> - **No tiene divisores de cero** ⇒ es un [[Dominio de integridad]].
> - Es un **anillo totalmente ordenado** (Teorema 5.40) → [[Orden en los enteros]].
> - **$\mathbb N\subset\mathbb Z$:** $n\mapsto[(n,0)]$ es un isomorfismo (de suma, producto y orden) entre $\mathbb N$ y $\mathbb Z^+$. Por eso escribimos $n$ en lugar de $[(n,0)]$ y $-n$ en lugar de $[(0,n)]$.

> [!abstract] Ejemplo de "bien definido": la suma
> Si $(a,b)\sim(a',b')$ y $(c,d)\sim(c',d')$: $a+b'=a'+b$ y $c+d'=c'+d$. Sumando, $(a+c)+(b'+d')=(a'+c')+(b+d)$, es decir, $(a+c,b+d)\sim(a'+c',b'+d')$. ✓

> [!warning] Errores típicos
> - Usar la resta en la definición de $\sim$: **todavía no existe** en $\mathbb N$. Por eso se escribe $a+b'=a'+b$.
> - Olvidar comprobar que las operaciones están bien definidas.

## Conexiones
- **Necesitas antes:** [[Conjunto cociente]], [[Suma y producto de naturales]], [[Anillo]]
- **Lleva a:** [[Orden en los enteros]], [[División euclídea]], [[Números racionales]]
- **Numerable:** [[Conjunto numerable]]
