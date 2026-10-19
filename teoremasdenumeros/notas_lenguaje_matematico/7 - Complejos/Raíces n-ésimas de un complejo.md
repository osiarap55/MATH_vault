---
tipo: teorema
tags: [teorema, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.5 · pp. 254-255; Ejemplo 7.10"
aliases: [Raíces n-ésimas, Raíz n-ésima, Raíces cúbicas, Raíces de un complejo]
---
# Raíces $n$-ésimas de un número complejo

> [!important] Teorema
> Todo $w=\rho e^{i\theta}\neq0$ tiene **exactamente $n$ raíces $n$-ésimas** (soluciones de $z^n=w$):
> $$z_k=\sqrt[n]\rho\;e^{\,i\frac{\theta+2k\pi}n},\qquad k=0,1,\dots,n-1.$$

> [!tip] En palabras sencillas
> Las $n$ raíces tienen **todas el mismo módulo** $\sqrt[n]\rho$ y están **repartidas uniformemente** en una circunferencia: forman un **polígono regular de $n$ lados**.

> [!abstract] Demostración (idea y pasos)
> Escribe $z=re^{i\alpha}$. Entonces $z^n=w\iff r^ne^{in\alpha}=\rho e^{i\theta}\iff$
> 1. $r^n=\rho$ (ecuación en $\mathbb R^+$): $r=\sqrt[n]\rho$ (única raíz positiva, ver [[Existencia de la raíz cuadrada]]).
> 2. $n\alpha=\theta\ [\mathrm{mód}\ 2\pi]$: $\alpha=\frac{\theta+2k\pi}n$ con $k\in\mathbb Z$.
> 3. Valores de $k$ que difieren en múltiplos de $n$ dan el mismo ángulo mód $2\pi$: hay exactamente $n$ raíces distintas ($k=0,\dots,n-1$).

> [!example] Raíces cúbicas de $-1$ (Ejemplo 7.10)
> $-1=1\cdot e^{i\pi}$: $r=1$, $\alpha=\frac{\pi+2k\pi}3$.
> - $k=0$: $e^{i\pi/3}=\frac12+i\frac{\sqrt3}2$
> - $k=1$: $e^{i\pi}=-1$
> - $k=2$: $e^{i5\pi/3}=\frac12-i\frac{\sqrt3}2$

> [!warning] Errores típicos
> - Dar solo una raíz (la "principal"). En $\mathbb C$ hay **$n$**.
> - Olvidar el $2k\pi$ al dividir el argumento entre $n$.

## Conexiones
- **Necesitas antes:** [[Forma exponencial de un complejo]], [[Fórmula de De Moivre]]
- **Lleva a:** [[Raíces de la unidad]], [[Ecuación de segundo grado en C]]
