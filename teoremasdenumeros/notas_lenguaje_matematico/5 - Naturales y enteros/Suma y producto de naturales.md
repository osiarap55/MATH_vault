---
tipo: teorema
tags: [definicion, teorema, naturales]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Def. 5.1-5.5 y Prop. 5.2, 5.4 · pp. 161-167"
aliases: [Suma de naturales, Producto de naturales, Potencia de naturales, Propiedades de la suma, Propiedades del producto]
---
# Suma y producto de números naturales

> [!tip] En palabras sencillas
> Sumar es "dar pasos de sucesor": $m+3=s(s(s(m)))$. Multiplicar es "sumar repetidamente". Ambas se definen **por recurrencia** y sus propiedades se **demuestran por inducción**: nada se da por supuesto.

> [!note] Definiciones (por recurrencia en $n$)
> | Suma | Producto | Potencia ($a\neq0$) |
> |---|---|---|
> | $m+0=m$ | $m\cdot0=0$ | $a^0=1$ |
> | $m+s(n)=s(m+n)$ | $m\cdot s(n)=m\cdot n+m$ | $a^{n+1}=a^n\cdot a$ |
> Consecuencia: $m+1=s(m)$ (por eso escribimos $n+1$ para el sucesor).

> [!important] Proposiciones 5.2 y 5.4
> | Propiedad | Suma | Producto |
> |---|---|---|
> | Interna | ✓ | ✓ |
> | Neutro | $m+0=0+m=m$ | $m\cdot1=1\cdot m=m$ |
> | Asociativa | ✓ | ✓ |
> | Conmutativa | ✓ | ✓ |
> | Cancelativa | $m+p=n+p\Rightarrow m=n$ | $mp=np,\ p\neq0\Rightarrow m=n$ |
> | Distributiva | — | $m(n+p)=mn+mp$ |
> Además: $m+n=0\Rightarrow m=n=0$; $\ 0$ es absorbente; $\ mp=0\Rightarrow m=0$ o $p=0$.
> Potencias: $a^{m+n}=a^ma^n$, $(a^m)^n=a^{mn}$, $a^nb^n=(ab)^n$.

> [!abstract] Modelo de demostración: asociativa $(m+n)+p=m+(n+p)$, inducción en $p$
> - **$p=0$:** $(m+n)+0=m+n=m+(n+0)$.
> - **Paso:** $(m+n)+s(p)\overset{\text{def}}=s((m+n)+p)\overset{\text{HI}}=s(m+(n+p))\overset{\text{def}}=m+s(n+p)\overset{\text{def}}=m+(n+s(p))$. ∎
>
> Todas las demás siguen el mismo esquema: **aplicar la definición, usar la hipótesis de inducción (HI) y volver a aplicar la definición**. Fíjate en el orden lógico: la conmutativa usa la asociativa y el lema $1+m=s(m)$.

> [!note] ¿Y $0^0$?
> El libro no lo define. En álgebra y combinatoria se toma $0^0=1$ (para que $(1+x)^n=\sum\binom nkx^k$ valga en $x=0$); en límites, $0^0$ es una **indeterminación**.

## Conexiones
- **Necesitas antes:** [[Axiomas de Peano]], [[Definición por recurrencia]], [[Principio de inducción]]
- **Lleva a:** [[Orden en los naturales]], [[Números enteros]]
- **Misma idea con cardinales:** [[Suma y producto de cardinales]]
