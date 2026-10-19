---
tipo: teorema
tags: [definicion, teorema, naturales, orden]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Def. 5.6 y Prop. 5.7 · pp. 167-169"
aliases: [Orden de N, Menor o igual en N]
---
# Orden en los naturales

> [!note] Definición
> $$m\le n\iff\exists p\in\mathbb N:\ m+p=n$$
> ("$n$ se alcanza desde $m$ dando pasos"). $m<n$ si además $m\neq n$, que equivale a $m+1\le n$.

> [!important] Proposición 5.7
> $\le$ es una [[Relación de orden]] **total** en $\mathbb N$, **compatible** con las operaciones:
> $$m\le n\Rightarrow m+p\le n+p\ \text{ y }\ mp\le np.$$

> [!abstract] Demostración (idea y pasos)
> - Reflexiva: $n+0=n$.
> - Antisimétrica: si $n+p=m$ y $m+q=n$, entonces $n+(q+p)=n+0$; cancelando, $q+p=0$, luego $p=q=0$.
> - Transitiva: $n+p=m$, $m+q=r\Rightarrow n+(p+q)=r$.
> - Total: por inducción en $n$.
> - Compatible: si $m+q=n$, entonces $(m+p)+q=n+p$ y $mp+qp=np$.

> [!important] Propiedades **específicas** de $\mathbb N$ (falsas en $\mathbb Q$ y $\mathbb R$)
> 1. **Discreto:** $(n,n+1)_{\mathbb N}=\emptyset$. No hay naturales "entre" $n$ y $n+1$.
> 2. **[[Buen orden]]:** todo subconjunto no vacío tiene mínimo.
> 3. Todo subconjunto no vacío **acotado superiormente** tiene **máximo**.
> 4. $\mathbb N$ no tiene máximo.

> [!abstract] Idea de la prueba del buen orden
> Si $A$ no tuviera mínimo, sea $U$ el conjunto de cotas inferiores de $A$. Entonces $U\cap A=\emptyset$ (un elemento en los dos sería el mínimo) y por inducción $U=\mathbb N$ (si $n\in U$, como $n\notin A$, $n<a$ para todo $a\in A$, luego $n+1\le a$). Así $A\subseteq\mathbb N\setminus U=\emptyset$.

## Conexiones
- **Necesitas antes:** [[Suma y producto de naturales]], [[Relación de orden]]
- **Lleva a:** [[Buen orden]], [[Conjunto finito]], [[Orden en los enteros]], [[División euclídea]]
