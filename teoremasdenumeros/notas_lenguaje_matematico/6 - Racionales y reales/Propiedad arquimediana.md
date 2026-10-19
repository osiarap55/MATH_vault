---
tipo: teorema
tags: [teorema, reales, orden]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Prop. 5.42 (Z), 6.5 (Q), 6.12 (R) · pp. 193, 214, 222"
aliases: [Arquimediana, Arquímedes, Propiedad de Arquímedes, N no está acotado]
---
# Propiedad arquimediana

> [!important] Proposición 6.12
> Para todo $x>0$ y todo $y\in\mathbb R$ existe $n\in\mathbb N$ con
> $$nx>y.$$
> (Vale igual en $\mathbb Z$ —Prop. 5.42— y en $\mathbb Q$ —Prop. 6.5.)

> [!tip] En palabras sencillas
> Por pequeño que sea un paso $x$ y por lejos que esté la meta $y$, **con suficientes pasos llegas**. Equivalentemente: **$\mathbb N$ no está acotado en $\mathbb R$**, y **$\frac1n$ se hace tan pequeño como quieras**.

> [!abstract] Demostración
> Si $y<0$, vale $n=1$. Si $y\ge0$, toma $n=E\!\left(\frac yx\right)+1$ ([[Parte entera]]): entonces $n>\frac yx$, o sea $nx>y$.
> (Otra vía, por el supremo: si $\mathbb N$ estuviera acotado, sea $s=\sup\mathbb N$; hay $n>s-1$, luego $n+1>s$. Absurdo.)

> [!important] Consecuencias que usarás constantemente
> - Para todo $\varepsilon>0$ existe $n$ con $\frac1n<\varepsilon$.
> - $\bigcap_n\left(0,\frac1n\right)=\emptyset$ y $\bigcap_n\left[a-\frac1n,a+\frac1n\right]=\{a\}$ ([[Familias de conjuntos]]).
> - Densidad de $\mathbb Q$ en $\mathbb R$ ([[Densidad de Q en R]]).

> [!warning] El orden de los cuantificadores
> $(\forall x\in\mathbb R)(\exists n)\ n>x$ ✓ pero $(\exists n)(\forall x)\ n>x$ ✗. Ver [[Cuantificadores]].

> [!failure] Un orden no arquimediano
> En el orden lexicográfico de $\mathbb R^2$, $n\cdot(0,1)=(0,n)$ nunca supera a $(1,0)$.

## Conexiones
- **Usa:** [[Parte entera]], [[Axioma del supremo]], [[Orden en los enteros]]
- **Se usa en:** [[Densidad de Q en R]], [[Familias de conjuntos]], [[Intervalos encajados]]
