---
tipo: definición
tags: [definicion, relaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.3 · pp. 77-78"
aliases: [Clases de equivalencia, Representante, Representante de una clase]
---
# Clase de equivalencia

> [!tip] En palabras sencillas
> La clase de $x$ es "**el grupo de todos los que son equivalentes a $x$**". Cualquier miembro del grupo puede hacer de **representante**.

> [!note] Definición
> Dada una [[Relación de equivalencia]] $\sim$ en $U$, la **clase** de $x\in U$ es
> $$[x]=\{y\in U\mid x\sim y\}.$$
> Cada $y\in[x]$ es un **representante** de la clase.

> [!important] Propiedades (las dos claves)
> 1. Si $x\sim y$, entonces $[x]=[y]$.
> 2. Si $x\not\sim y$, entonces $[x]\cap[y]=\emptyset$.
>
> Es decir: **dos clases o son iguales o son disjuntas**. Nunca se solapan "a medias". Y como $x\in[x]$ (reflexiva), ninguna clase es vacía.

> [!abstract] Demostración (idea y pasos)
> **1.** ($[x]\subseteq[y]$) Si $z\in[x]$, entonces $x\sim z$; por simetría $z\sim x$; con $x\sim y$ y transitividad, $z\sim y$; por simetría $y\sim z$, o sea $z\in[y]$. La otra inclusión es igual.
> **2.** [[Reducción al absurdo]]: si existiera $z\in[x]\cap[y]$, tendríamos $x\sim z$ y $y\sim z$; con simetría y transitividad, $x\sim y$. Contradicción.

> [!example] Ejemplos
> - Módulo 3 en $\mathbb Z$: $[0]=\{\dots,-3,0,3,6,\dots\}$, $[1]=\{\dots,-2,1,4,\dots\}$, $[2]=\{\dots,-1,2,5,\dots\}$. Y $[1]=[4]=[-2]$.
> - En $\mathbb Q$: $[(1,2)]=\{(1,2),(2,4),(-3,-6),\dots\}$, que es lo que llamamos $\frac12$.

> [!warning] Errores típicos
> - Pensar que $[x]$ es un elemento: es un **conjunto** (un subconjunto de $U$).
> - Creer que $[x]\neq[y]$ porque $x\neq y$. Si $x\sim y$, las clases son la misma.

## Conexiones
- **Necesitas antes:** [[Relación de equivalencia]], [[Reducción al absurdo]]
- **Lleva a:** [[Conjunto cociente]], [[Partición de un conjunto]]
