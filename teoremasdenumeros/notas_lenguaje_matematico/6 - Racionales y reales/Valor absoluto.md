---
tipo: teorema
tags: [definicion, teorema, reales, orden]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "§4.5 · p. 144 (Prop. 4.37); §5.4 · p. 191; §6.4 · p. 221; Ejercicios cap. 4 y 6"
aliases: [Desigualdad triangular, |x|, Módulo de un real, Distancia en R]
---
# Valor absoluto

> [!tip] En palabras sencillas
> $|x|$ es la **distancia de $x$ al 0**, sin signo. Y $|x-y|$ es la **distancia entre $x$ e $y$**.

> [!note] Definición (en cualquier anillo totalmente ordenado)
> $$|a|=\begin{cases}a&\text{si }a\ge0\\-a&\text{si }a<0\end{cases}$$

> [!important] Propiedades
> 1. $|a|\ge0$, y $|a|=0\iff a=0$.
> 2. $|ab|=|a|\,|b|$.
> 3. **Desigualdad triangular:** $|a+b|\le|a|+|b|$.
> 4. $\big||a|-|b|\big|\le|a-b|$.
> 5. $-|a|\le a\le|a|$.
> 6. Si $r>0$: $|x-a|<r\iff a-r<x<a+r\iff x\in(a-r,a+r)$.
> 7. $\sqrt{x^2}=|x|$; $|a^{-1}|=|a|^{-1}$.
> 8. $2\max(a,b)=a+b+|a-b|$, $\ 2\min(a,b)=a+b-|a-b|$.

> [!abstract] Demostración de la triangular
> Por 5, $-|a|-|b|\le a+b\le|a|+|b|$. Si $a+b\ge0$, $|a+b|=a+b\le|a|+|b|$; si no, $|a+b|=-(a+b)\le|a|+|b|$.

> [!tip] Cómo resolver desigualdades con valor absoluto
> 1. Halla dónde se anula cada expresión dentro de $|\ |$.
> 2. Parte la recta en esos trozos y en cada uno **quita las barras** con el signo correcto.
> 3. Resuelve en cada trozo e intersecta con el trozo; une los resultados.
>
> Ej.: $|x+2|+|x-2|<12$: si $x\ge2$, $2x<12$; si $-2\le x\le2$, $4<12$ siempre; si $x\le-2$, $-2x<12$. Solución: $(-6,6)$.

> [!warning] Errores típicos
> - $|a+b|=|a|+|b|$ ✗ (solo si tienen el mismo signo).
> - $|x|<r\iff x<r$ ✗ (falta $x>-r$).

## Conexiones
- **Necesitas antes:** [[Cuerpo ordenado]]
- **Se usa en:** [[Unicidad del límite de una sucesión]], [[Densidad de Q en R]], [[Intervalos encajados]], módulo complejo ([[Forma binómica y conjugado]])
- **Practica:** [[LM Ejercicios Cap 6#Ejercicio 2 · Desigualdades]]
