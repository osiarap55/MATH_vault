---
tipo: teorema
tags: [teorema, reales, cardinales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Prop. 6.16 y Ejemplos 6.17-6.20 · pp. 227-228"
aliases: [ℝ no es numerable, Los reales no son numerables, [0,1] no es numerable, Los irracionales no son numerables, Potencia del continuo]
---
# $\mathbb R$ no es numerable

> [!important] Proposición 6.16
> El intervalo $[0,1]$ **no es numerable**.
> **Consecuencias:** ningún intervalo no degenerado es numerable, $\mathbb R$ no lo es, y **los irracionales tampoco**.

> [!tip] En palabras sencillas
> Por mucho que lo intentes, **no puedes hacer una lista** $x_0,x_1,x_2,\dots$ con todos los números de $[0,1]$: siempre se escapa alguno. Hay "más" reales que naturales.

> [!abstract] Demostración (idea y pasos) · [[Reducción al absurdo]] + [[Intervalos encajados]]
> 1. Supón $[0,1]=\{x_0,x_1,x_2,\dots\}$.
> 2. Divide $[0,1]$ en tres partes iguales $[0,\frac13],[\frac13,\frac23],[\frac23,1]$. Un punto está como mucho en dos de ellas, así que $x_0$ **no está** en alguna: llámala $I_0$.
> 3. Divide $I_0$ en tres y elige un tercio $I_1$ que **no contenga** a $x_1$. Y así sucesivamente: $I_n$ no contiene a $x_n$.
> 4. Los $I_n$ son cerrados, encajados y de longitud $3^{-n-1}\to0$: hay un punto $x\in\bigcap I_n\subseteq[0,1]$.
> 5. Pero $x\neq x_n$ para todo $n$ (porque $x\in I_n\not\ni x_n$). Entonces $x$ no está en la lista. **Contradicción.** ∎

> [!example] Consecuencias (Ejemplos 6.17-6.20)
> - $[a,b]\simeq[0,1]$ con $x\mapsto bx+a(1-x)$: no numerable.
> - Todo intervalo con más de un punto contiene un $[x,y]$: no numerable. $\mathbb R$ tampoco.
> - $\mathbb R=\mathbb Q\cup(\mathbb R\setminus\mathbb Q)$: si los irracionales fueran numerables, $\mathbb R$ también. **Los irracionales no son numerables.**
> - **$[0,1)\simeq\mathcal P(\mathbb N)$** ([[Teorema de Cantor-Bernstein]] con dos inyecciones vía [[Expresión decimal|decimales]]): $\operatorname{card}\mathbb R=\operatorname{card}\mathcal P(\mathbb N)=\mathfrak c$.

> [!note] Otra demostración famosa: la diagonal de Cantor
> Escribe la lista de decimales $x_n=0{,}d_{n0}d_{n1}d_{n2}\dots$ y construye $y=0{,}e_0e_1e_2\dots$ con $e_n\neq d_{nn}$ (y $e_n\notin\{0,9\}$ para evitar el problema $0{,}\overline9=1$). Entonces $y$ difiere de cada $x_n$ en la cifra $n$-ésima.

## Conexiones
- **Usa:** [[Intervalos encajados]], [[Conjunto numerable]], [[Reducción al absurdo]]
- **Lleva a:** [[Cardinal]] ($\aleph_0<\mathfrak c$, hipótesis del continuo), [[Números algebraicos y trascendentes]]
- **Mismo espíritu:** [[Teorema de Cantor]]
