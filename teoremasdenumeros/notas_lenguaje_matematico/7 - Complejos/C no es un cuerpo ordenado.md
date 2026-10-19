---
tipo: teorema
tags: [teorema, complejos, orden]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "Comentarios cap. 7 · p. 263; Prop. 4.37"
aliases: [ℂ no se puede ordenar, C no es ordenable, No hay orden en C]
---
# $\mathbb C$ no es un cuerpo ordenado

> [!important] Teorema
> No existe ninguna relación de orden total en $\mathbb C$ compatible con la suma y el producto (es decir, que haga de $\mathbb C$ un [[Cuerpo ordenado]]).

> [!tip] En palabras sencillas
> No tiene sentido decir "$i>0$" o "$i<0$". En $\mathbb C$ **no hay desigualdades** entre números (sí entre sus **módulos**, que son reales).

> [!abstract] Demostración · [[Reducción al absurdo]]
> En todo anillo totalmente ordenado, **todo cuadrado es $\ge0$** y $1>0$ ([[Cuerpo ordenado|Prop. 4.37, propiedades 6 y 7]]). Entonces
> - $i^2=-1\ge0$, y
> - $1^2=1>0$.
> Sumando: $0=-1+1>0$. **Contradicción.** ∎

> [!warning] Errores típicos
> - Escribir $z_1<z_2$ con complejos no reales.
> - Confundir con el **orden lexicográfico** de $\mathbb R^2$: es un orden total en $\mathbb C$, pero **no es compatible con el producto**.

## Conexiones
- **Necesitas antes:** [[Cuerpo ordenado]], [[Números complejos]]
- **Contraste:** [[Números reales]] (cuerpo ordenado completo)
