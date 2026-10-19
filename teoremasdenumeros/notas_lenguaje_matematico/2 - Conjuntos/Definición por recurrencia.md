---
tipo: definición
tags: [definicion, conjuntos, naturales]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "Ejemplo 2.7 · p. 40; Comentarios cap. 2 · pp. 65-66"
aliases: [Definición recurrente, Sucesión recurrente, Recurrencia, Factorial, Fibonacci, Progresión aritmética, Progresión geométrica]
---
# Definición por recurrencia

> [!tip] En palabras sencillas
> Defines el primer término y una **regla** para obtener cada término a partir de los anteriores. Gracias a la [[Principio de inducción|inducción]], eso define **todos** los términos sin ambigüedad.

> [!note] Definición
> Un objeto $a_n$ que depende de $n\in\mathbb N$ se define **por recurrencia** dando:
> 1. el valor (o valores) iniciales, y
> 2. una fórmula para $a_{n+1}$ en función de $a_n$ (o de varios anteriores).

> [!example] Ejemplos
> | Nombre | Inicio | Regla | Fórmula cerrada |
> |---|---|---|---|
> | Factorial | $0!=1$ | $(n+1)!=(n+1)\,n!$ | $n!=n(n-1)\cdots 2\cdot 1$ |
> | Progresión aritmética | $x_1$ | $x_n=x_{n-1}+d$ | $x_n=x_1+(n-1)d$ |
> | Progresión geométrica | $x_1$ | $x_n=r\,x_{n-1}$ | $x_n=x_1r^{n-1}$ |
> | Fibonacci | $F_0=0,\ F_1=1$ | $F_{n+1}=F_n+F_{n-1}$ | $0,1,1,2,3,5,8,13,21,\dots$ |
>
> Fibonacci necesita **dos** valores iniciales porque la regla usa dos términos anteriores.

> [!warning] Errores típicos
> - Olvidar el valor inicial: sin $0!=1$ la regla $(n+1)!=(n+1)n!$ no determina nada.
> - Para demostrar propiedades de algo definido por recurrencia, lo natural es **inducción**.

## Conexiones
- **Necesitas antes:** [[Principio de inducción]], [[Axiomas de Peano]]
- **Se usa en:** [[Suma y producto de naturales]] (la suma y el producto se definen así), [[Número combinatorio]], potencias $a^{n+1}=a^n\cdot a$
