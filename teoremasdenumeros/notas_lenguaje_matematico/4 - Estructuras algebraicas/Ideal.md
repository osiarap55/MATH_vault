---
tipo: definición
tags: [definicion, algebra, anillos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Def. 4.27 y 4.29 · pp. 137-138; Ejercicios 9, 10, 14"
aliases: [Ideales, Ideal principal, Anillo cociente]
---
# Ideal

> [!tip] En palabras sencillas
> Un ideal es un subconjunto que, además de ser cerrado para restar, **"se traga" los productos**: si multiplicas un elemento del ideal por **cualquier** cosa del anillo, sigues dentro. Ejemplo: los múltiplos de 5 en $\mathbb Z$ (múltiplo de 5 por lo que sea = múltiplo de 5).

> [!note] Definición (anillo conmutativo $A$)
> $\emptyset\neq I\subseteq A$ es un **ideal** si:
> 1. $a-b\in I$ para todo $a,b\in I$;
> 2. $ac\in I$ para todo $a\in I$ y **todo** $c\in A$.
>
> **Ideal principal** generado por $a$: $(a)=aA=\{ak\mid k\in A\}$.

> [!example] Ejemplos
> - $n\mathbb Z=(n)$ es un ideal de $\mathbb Z$. **Todos** los ideales de $\mathbb Z$ son de esta forma (cap. 5, ver [[Máximo común divisor]]).
> - $\{0\}$ y $A$ son ideales siempre.
> - $\mathbb Z[\sqrt2]$ **no** es ideal de $\mathbb R$: $1\cdot\pi\notin\mathbb Z[\sqrt2]$.
> - La intersección y la suma $I+J$ de ideales son ideales; la unión, en general, no.

> [!important] Por qué importan: el anillo cociente
> Si $I$ es un ideal, la congruencia $a\equiv b\iff a-b\in I$ es compatible con $+$ **y con $\cdot$**, así que $A/I$ es un anillo con $[a]+[b]=[a+b]$, $[a][b]=[ab]$.
> Ejemplo: $\mathbb Z/n\mathbb Z$ ([[Congruencia módulo n]]).

> [!warning] Diferencia con subanillo
> Un subanillo es cerrado para productos **entre sus elementos**; un ideal, para productos **con cualquier elemento del anillo**. Un ideal propio **no contiene al 1** (si $1\in I$, entonces $c=1\cdot c\in I$ para todo $c$, e $I=A$).

## Conexiones
- **Necesitas antes:** [[Anillo]], [[Subgrupo]]
- **Lleva a:** [[Congruencia módulo n]], [[Núcleo e imagen de un homomorfismo]] (el núcleo de un homomorfismo de anillos es un ideal)
- **Profundiza:** [[resumen_cuerposanillosyteoriadegalois]] (ideales primos y maximales)
