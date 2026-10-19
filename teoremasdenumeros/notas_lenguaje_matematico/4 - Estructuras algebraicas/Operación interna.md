---
tipo: definición
tags: [definicion, algebra]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "§4.1 · pp. 122-124"
aliases: [Operación, Ley de composición interna, Propiedad asociativa, Propiedad conmutativa, Asociativa, Conmutativa, Operaciones internas]
---
# Operación interna

> [!tip] En palabras sencillas
> Una operación interna en $E$ toma **dos** elementos de $E$ y devuelve **uno** que también está en $E$ (no "se sale"). La suma de naturales lo es; la resta de naturales no ($3-5\notin\mathbb N$).

> [!note] Definición
> Una **operación interna** en $E$ es una [[Aplicación]] $*:E\times E\to E$, $(a,b)\mapsto a*b$.
> - **Asociativa:** $(a*b)*c=a*(b*c)$. Permite quitar paréntesis: $a_1*\cdots*a_n$.
> - **Conmutativa:** $a*b=b*a$. Permite reordenar.
> - Si es asociativa y conmutativa se usan $\sum a_i$, $na$ (notación aditiva) o $\prod a_i$, $a^n$ (multiplicativa).

> [!example] Ejemplos
> | Operación | Conjunto | Asoc. | Conm. |
> |---|---|:-:|:-:|
> | $+$, $\cdot$ | $\mathbb N,\mathbb Z,\mathbb Q,\mathbb R$ | ✓ | ✓ |
> | $-$ | $\mathbb Z$ | ✗ $(9-5)-1\neq9-(5-1)$ | ✗ |
> | $/$ | $\mathbb Q^*$ | ✗ | ✗ |
> | $\cup$, $\cap$, $\triangle$ | $\mathcal P(\Omega)$ | ✓ | ✓ |
> | $\circ$ | $\mathcal F(\Omega)$ | ✓ | ✗ |
> | producto de matrices | $M_n$ | ✓ | ✗ |
> | $\land$, $\lor$ | proposiciones | ✓ | ✓ |
> | mcd, mcm | $\mathbb N^*$ | ✓ | ✓ |
> | producto vectorial $\times$ | $\mathbb R^3$ | ✗ | ✗ |
>
> **No** son internas: la resta en $\mathbb N$, el producto escalar en $\mathbb R^3$ (da un número, no un vector).

> [!warning] Errores típicos
> - En una operación **no conmutativa** (matrices), de $A=B$ se deduce $CA=CB$ o $AC=BC$, **pero no** $AC=CB$. Hay que multiplicar los dos lados **por el mismo lado**.
> - Por eso, con matrices **no** valen $(A+B)^2=A^2+2AB+B^2$ ni el binomio de Newton.

## Conexiones
- **Necesitas antes:** [[Aplicación]], [[Producto cartesiano]]
- **Lleva a:** [[Elemento neutro y simétrico]], [[Grupo]], [[Anillo]]
