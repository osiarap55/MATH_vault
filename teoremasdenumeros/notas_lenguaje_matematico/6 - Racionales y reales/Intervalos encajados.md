---
tipo: teorema
tags: [teorema, reales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Prop. 6.15 · pp. 225-226"
aliases: [Principio de los intervalos encajados, Teorema de los intervalos encajados, Cantor (intervalos encajados)]
---
# Intervalos encajados

> [!important] Proposición 6.15
> Sea $[a_0,b_0]\supseteq[a_1,b_1]\supseteq[a_2,b_2]\supseteq\cdots$ una sucesión de intervalos **cerrados** encajados.
> 1. $\displaystyle\bigcap_{n\in\mathbb N}[a_n,b_n]\neq\emptyset$.
> 2. Si además $b_n-a_n\to0$, la intersección es **un único punto**.

> [!tip] En palabras sencillas
> Si vas "cercando" una zona con intervalos cerrados cada vez más pequeños, siempre queda algo dentro; y si los intervalos se encogen hasta longitud 0, lo que queda es exactamente un punto. **En $\mathbb Q$ esto falla** (el punto podría ser $\sqrt2$).

> [!abstract] Demostración (idea y pasos)
> 1. $A=\{a_n\}$ está acotado por $b_0$: sea $\alpha=\sup A$. $B=\{b_n\}$ está acotado por $a_0$: sea $\beta=\inf B$ ([[Axioma del supremo]]).
> 2. Como $a_n\le b_m$ para todo $n,m$: $\alpha\le\beta$, y $[\alpha,\beta]\subseteq[a_n,b_n]$ para todo $n$. **No vacía.**
> 3. Si hubiera dos puntos $x\neq y$ en todos, $b_n-a_n\ge|x-y|>0$ para todo $n$: no tiende a 0.

> [!failure] Las hipótesis importan
> - **Cerrados:** $\bigcap(0,\frac1n)=\emptyset$.
> - **Acotados:** $\bigcap[n,\infty)=\emptyset$.
> - **En $\mathbb R$:** en $\mathbb Q$, los intervalos de aproximaciones decimales de $\sqrt2$ tienen intersección vacía.

## Conexiones
- **Usa:** [[Axioma del supremo]], [[Supremo e ínfimo]]
- **Se usa en:** [[Expresión decimal]] (todo decimal infinito es un real), [[R no es numerable]]
- **Relacionado:** [[Familias de conjuntos]]
