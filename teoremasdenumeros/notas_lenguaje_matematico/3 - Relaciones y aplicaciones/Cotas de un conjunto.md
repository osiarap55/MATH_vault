---
tipo: definición
tags: [definicion, orden]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.24 · p. 87"
aliases: [Cota superior, Cota inferior, Conjunto acotado, Acotado superiormente, Acotado inferiormente, Cotas]
---
# Cotas de un conjunto

> [!tip] En palabras sencillas
> Una **cota superior** de $A$ es un "techo": algo que está por encima de **todos** los elementos de $A$. Una **cota inferior** es un "suelo". El techo **no tiene por qué estar dentro de $A$**.

> [!note] Definición (en $(U,\preceq)$, con $A\subseteq U$)
> - $u\in U$ es **cota superior** de $A$ si $\forall x\in A:\ x\preceq u$.
> - $d\in U$ es **cota inferior** de $A$ si $\forall x\in A:\ d\preceq x$.
> - $A$ está **acotado superiormente** si tiene alguna cota superior; **inferiormente** si tiene alguna inferior; **acotado** si las dos cosas (⇔ está dentro de algún intervalo $[a,b]$).

> [!example] Ejemplos
> - $A=(0,1]\subseteq\mathbb R$: cotas superiores $=[1,\infty)$; cotas inferiores $=(-\infty,0]$.
> - $\mathbb N\subseteq\mathbb R$: acotado inferiormente (por $0$) pero **no** superiormente ([[Propiedad arquimediana]]).
> - En $(\mathbb N^*,\mid)$: $A=\{2,4,6\}$ tiene por cotas superiores los múltiplos comunes (12, 24, 36…) y por cotas inferiores los divisores comunes (1, 2).
> - $A=\{x\in\mathbb Q\mid x^2<2\}$: $2$ es cota superior y $-2$ inferior (en $\mathbb Q$).

> [!warning] Errores típicos
> - Pensar que la cota tiene que ser un elemento de $A$. No: $1$ es cota superior de $(0,1)$ y $1\notin(0,1)$.
> - Una cota no es única: si $u$ es cota superior, cualquier cosa mayor también lo es.

## Conexiones
- **Necesitas antes:** [[Relación de orden]], [[Cuantificadores]]
- **Lleva a:** [[Máximo y mínimo]], [[Supremo e ínfimo]]
