---
tipo: definición
tags: [definicion, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.2 · pp. 244-246"
aliases: [Forma binómica, Conjugado, Parte real, Parte imaginaria, Imaginario puro, Re(z), Im(z), Cociente de complejos]
---
# Forma binómica y conjugado

> [!note] Definiciones
> Para $z=a+ib$ ($a,b\in\mathbb R$):
> - **Parte real** $\operatorname{Re}z=a$; **parte imaginaria** $\operatorname{Im}z=b$ (¡es un número real!).
> - $z$ es **imaginario puro** si $\operatorname{Re}z=0$.
> - **Conjugado:** $\bar z=a-ib$.

> [!important] Propiedades del conjugado
> - $z+\bar z=2\operatorname{Re}z$, $\ z-\bar z=2i\operatorname{Im}z$, $\ $**$z\bar z=a^2+b^2=|z|^2$** (real y $\ge0$).
> - $z$ es real $\iff z=\bar z$; imaginario puro $\iff\bar z=-z$.
> - $\bar{\bar z}=z$, $\ \overline{z+z'}=\bar z+\bar z'$, $\ \overline{zz'}=\bar z\,\bar z'$, $\ \overline{z^n}=\bar z^n$, $\ \overline{1/z}=1/\bar z$.
>
> Es decir, **conjugar es un automorfismo del cuerpo $\mathbb C$** que deja fijos los reales ([[Homomorfismo]]).

> [!tip] Cómo dividir complejos
> Multiplica arriba y abajo por el **conjugado del denominador**:
> $$\frac1z=\frac{\bar z}{z\bar z}=\frac{a-ib}{a^2+b^2}\qquad\frac{2+i}{1-i}=\frac{(2+i)(1+i)}{(1-i)(1+i)}=\frac{1+3i}2$$

> [!example] Ejemplo 7.4
> ¿Para qué $z=x+iy$ es $w=(z-1)(\bar z-i)$ real? Desarrollando $\big((x-1)+iy\big)\big(x-i(y+1)\big)$ sale $w=(x^2-x+y^2+y)+i(y-x+1)$. Es real $\iff y=x-1$ (una recta). Es imaginario puro $\iff x^2-x+y^2+y=0$ (una circunferencia).

> [!warning] Errores típicos
> - Decir que $\operatorname{Im}(3+2i)=2i$. Es $2$.
> - Olvidar que $z\bar z=|z|^2$ y no $z^2$.

## Conexiones
- **Necesitas antes:** [[Números complejos]]
- **Lleva a:** [[Módulo y argumento]], [[Plano complejo]], [[Ecuación de segundo grado en C]]
