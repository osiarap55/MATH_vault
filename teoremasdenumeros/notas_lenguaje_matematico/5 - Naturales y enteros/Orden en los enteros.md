---
tipo: teorema
tags: [teorema, enteros, orden]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "§5.4 · pp. 190-193; Def. 5.39, Teorema 5.40, Prop. 5.41-5.42"
aliases: [Orden de Z, Enteros positivos, Z+, Propiedad arquimediana de Z]
---
# Orden en los enteros

> [!note] Definición
> Positivos: $\mathbb Z^+=\{[(m,0)]\}$; negativos: $\mathbb Z^-=\{[(0,n)]\}$. Se cumple $\mathbb Z^+\cup\mathbb Z^-=\mathbb Z$, $\mathbb Z^+\cap\mathbb Z^-=\{0\}$, y $\mathbb Z^+$ es cerrado para $+$ y $\cdot$.
> $$\alpha\le\beta\iff\beta-\alpha\in\mathbb Z^+$$

> [!important] Teorema 5.40
> $(\mathbb Z,+,\cdot,\le)$ es un **anillo totalmente ordenado**. Valen todas las reglas de [[Cuerpo ordenado|Prop. 4.37]]: $\alpha^2\ge0$, multiplicar por negativo invierte, $|\alpha\beta|=|\alpha||\beta|$, $|\alpha+\beta|\le|\alpha|+|\beta|$…

> [!important] Proposición 5.41
> En $\mathbb Z$, todo subconjunto no vacío **acotado superiormente tiene máximo**, y todo subconjunto no vacío **acotado inferiormente tiene mínimo**.
> *(Pero $\mathbb Z$ **no** está bien ordenado: él mismo no tiene mínimo.)*

> [!important] Proposición 5.42 (propiedad arquimediana de $\mathbb Z$)
> Si $\alpha>0$, para todo $\beta$ existe $n\in\mathbb N$ con $n\alpha>\beta$.
> *Idea:* si $\beta\ge\alpha$, el conjunto $\{k\alpha\mid k\alpha\le\beta\}$ está acotado, tiene máximo $m\alpha$, y $(m+1)\alpha>\beta$.
> La versión para $\mathbb R$: [[Propiedad arquimediana]].

## Conexiones
- **Necesitas antes:** [[Números enteros]], [[Orden en los naturales]], [[Cuerpo ordenado]]
- **Lleva a:** [[División euclídea]] (usa la Prop. 5.41), [[Valor absoluto]]
