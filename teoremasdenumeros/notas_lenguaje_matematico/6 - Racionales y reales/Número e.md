---
tipo: definición
tags: [definicion, reales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Ejemplo 6.9 · pp. 220-221"
aliases: [e, Número de Euler, Constante de Euler]
---
# El número $e$

> [!note] Definición (Ejemplo 6.9)
> $$e=\sup\left\{\left(1+\frac1n\right)^n\ \Big|\ n\in\mathbb N^*\right\}\approx2{,}7182818\ldots$$

> [!abstract] Por qué el supremo existe
> Con el [[Binomio de Newton]]:
> $$\left(1+\frac1n\right)^n=1+1+\frac1{2!}\Big(1-\frac1n\Big)+\frac1{3!}\Big(1-\frac1n\Big)\Big(1-\frac2n\Big)+\cdots$$
> Cada paréntesis es $\le1$, así que
> $$\left(1+\frac1n\right)^n\le1+1+\frac1{2!}+\cdots+\frac1{n!}\le1+1+\frac12+\frac1{2^2}+\cdots+\frac1{2^{n-1}}<3.$$
> El conjunto está acotado por 3 y no es vacío: por el [[Axioma del supremo]] tiene supremo.

> [!tip] En palabras sencillas
> Si inviertes 1 € al 100 % anual y capitalizas los intereses $n$ veces al año, al final tienes $(1+\frac1n)^n$ €. Por mucho que aumentes $n$, nunca pasas de $e\approx2{,}72$ €.

> [!note] Más adelante (análisis)
> La sucesión es creciente, así que $e=\lim_{n\to\infty}(1+\frac1n)^n=\sum_{k\ge0}\frac1{k!}$. Es irracional (y trascendente).

## Conexiones
- **Usa:** [[Axioma del supremo]], [[Binomio de Newton]]
- **Aparece en:** [[Forma exponencial de un complejo]] ($e^{i\theta}$)
- **Relacionado:** [[Números algebraicos y trascendentes]]
