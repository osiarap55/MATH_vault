---
tipo: teorema
tags: [definicion, teorema, algebra]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "§4.1 · pp. 124-125; Prop. 4.5 y 4.7"
aliases: [Elemento neutro, Elemento simétrico, Neutro, Simétrico, Opuesto, Inverso, Unicidad del neutro, Unicidad del simétrico]
---
# Elemento neutro y elemento simétrico

> [!tip] En palabras sencillas
> - **Neutro** $e$: el que "no hace nada" ($a*e=a$). Como el 0 en la suma o el 1 en el producto.
> - **Simétrico** de $a$: el que "deshace" $a$ ($a*a'=e$). Como $-a$ en la suma o $\frac1a$ en el producto.

> [!note] Definición
> - $e\in E$ es **neutro** si $a*e=e*a=a$ para todo $a$.
> - Si hay neutro, $a'$ es **simétrico** de $a$ si $a*a'=a'*a=e$. (Entonces $a$ es simétrico de $a'$.)
> - En notación aditiva: neutro $0$, simétrico $-a$ (**opuesto**). En multiplicativa: neutro $1$, simétrico $a^{-1}$ (**inverso**).

> [!important] Proposición 4.5: el neutro, si existe, es único
> Si $e,e'$ son neutros: $e*e'=e$ (porque $e'$ es neutro) y $e*e'=e'$ (porque $e$ es neutro). Luego $e=e'$.

> [!important] Proposición 4.7: si $*$ es asociativa, el simétrico, si existe, es único
> Si $a'$ y $a''$ son simétricos de $a$, calcula $a'*a*a''$ de dos maneras:
> $(a'*a)*a''=e*a''=a''$ y $a'*(a*a'')=a'*e=a'$. Luego $a'=a''$. **(Aquí se usa la asociativa.)**

> [!example] Ejemplos
> - $\mathbb N$: con $+$ solo el 0 tiene simétrico; con $\cdot$ solo el 1.
> - $\mathbb Z$: con $\cdot$ solo $\pm1$ tienen inverso.
> - $\mathcal F(\Omega)$ con $\circ$: neutro $I_\Omega$; tienen simétrico solo las **biyecciones** ([[Aplicación inversa]]).
> - Matrices con producto: neutro $I$; tienen inversa solo las de $\det\neq0$.
> - $\mathcal P(\Omega)$: neutro de $\cap$ es $\Omega$, de $\cup$ es $\emptyset$. Con $\triangle$, cada $A$ es su propio simétrico.
> - mcd en $\mathbb N^*$ no tiene neutro.

> [!warning] Ojo con la cuantificación
> - Neutro: $\exists e\ \forall a$ (**el mismo** para todos).
> - Simétrico: $\forall a\ \exists a'$ (**cada uno el suyo**). Ver [[Cuantificadores]].

## Conexiones
- **Necesitas antes:** [[Operación interna]], [[Cuantificadores]]
- **Lleva a:** [[Grupo]], [[Anillo]], [[Cuerpo]]
