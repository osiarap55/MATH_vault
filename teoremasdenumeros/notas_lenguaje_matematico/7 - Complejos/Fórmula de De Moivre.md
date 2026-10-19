---
tipo: teorema
tags: [teorema, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.3 · pp. 251-252; Ejemplo 7.6; Ejercicios 10-11"
aliases: [De Moivre, Moivre, Fórmula de Moivre]
---
# Fórmula de De Moivre

> [!important] Teorema
> Para todo $\alpha\in\mathbb R$ y todo $n\in\mathbb Z$:
> $$(\cos\alpha+i\sin\alpha)^n=\cos n\alpha+i\sin n\alpha.$$

> [!tip] En palabras sencillas
> Elevar a $n$ un complejo de módulo 1 es **girar $n$ veces el mismo ángulo**.

> [!abstract] Demostración (idea) · [[Principio de inducción|inducción]] en $n\ge0$
> - $n=0$: $1=\cos0+i\sin0$.
> - Paso: $(\cos\alpha+i\sin\alpha)^{n+1}=(\cos n\alpha+i\sin n\alpha)(\cos\alpha+i\sin\alpha)=\cos(n+1)\alpha+i\sin(n+1)\alpha$ por la regla del producto en [[Forma trigonométrica y polar|forma polar]].
> - Para $n<0$: usa que el inverso de $\cos\alpha+i\sin\alpha$ es $\cos(-\alpha)+i\sin(-\alpha)$.

> [!example] Uso clásico: fórmulas de ángulo múltiple (Ejemplo 7.6)
> Desarrolla $(\cos\alpha+i\sin\alpha)^3$ con el [[Binomio de Newton]] e iguala con $\cos3\alpha+i\sin3\alpha$:
> $$\cos3\alpha=\cos^3\alpha-3\cos\alpha\sin^2\alpha\qquad\sin3\alpha=3\cos^2\alpha\sin\alpha-\sin^3\alpha$$
> (Igualar partes reales e imaginarias.)

## Conexiones
- **Necesitas antes:** [[Forma trigonométrica y polar]], [[Principio de inducción]]
- **Lleva a:** [[Raíces n-ésimas de un complejo]], [[Forma exponencial de un complejo]]
- **Practica:** [[LM Ejercicios Cap 7#Ejercicio 5 · Coseno de 5α y de π entre 10]]
