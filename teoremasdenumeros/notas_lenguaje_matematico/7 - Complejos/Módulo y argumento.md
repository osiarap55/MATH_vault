---
tipo: definición
tags: [definicion, teorema, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.3 · pp. 248-250; Ejemplo 7.5"
aliases: [Módulo, Argumento, Módulo de un complejo, Argumento de un complejo, |z|, arg z, Desigualdad triangular en C]
---
# Módulo y argumento

> [!note] Definiciones
> - **Módulo:** $|z|=r=\sqrt{z\bar z}=\sqrt{a^2+b^2}$ (la distancia al origen).
> - **Argumento** ($z\neq0$): el ángulo $\alpha$ entre el eje real positivo y el vector $\vec{OM_z}$. Es un número real **módulo $2\pi$**: $\arg z=\alpha\ [\mathrm{mód}\ 2\pi]$ ([[Congruencia módulo n|$\mathbb R/2\pi$]]). **El 0 no tiene argumento.**

> [!important] Propiedades del módulo
> 1. $|z|\ge0$; $|z|=0\iff z=0$.
> 2. $|zz'|=|z|\,|z'|$ (prueba: $|zz'|^2=zz'\overline{zz'}=z\bar z\,z'\bar z'$).
> 3. $|\bar z|=|z|$.
> 4. **Triangular:** $|z+z'|\le|z|+|z'|$.
> 5. $\big||z|-|z'|\big|\le|z-z'|$ (Ejemplo 7.5).

> [!abstract] Demostración de la triangular
> $|z+z'|^2=(z+z')(\bar z+\bar z')=|z|^2+|z'|^2+2\operatorname{Re}(z\bar z')\le|z|^2+|z'|^2+2|z||z'|=(|z|+|z'|)^2$, usando $\operatorname{Re}w\le|w|$.

> [!important] Propiedades del argumento ($z\neq0$)
> - $z$ real $\iff\arg z=0\ [\mathrm{mód}\ \pi]$; imaginario puro $\iff\arg z=\frac\pi2\ [\mathrm{mód}\ \pi]$.
> - $\arg\bar z=-\arg z$; $\ \arg(-z)=\pi+\arg z$.
> - $\arg(zz')=\arg z+\arg z'$; $\ \arg(1/z)=-\arg z$; $\ \arg(z^n)=n\arg z$ (todo mód $2\pi$).

> [!warning] Error típico
> Calcular el argumento como $\arctan(b/a)$ **sin mirar el cuadrante**: $-1-i$ tiene argumento $\frac{5\pi}4$, no $\frac\pi4$.

## Conexiones
- **Necesitas antes:** [[Forma binómica y conjugado]], [[Plano complejo]]
- **Lleva a:** [[Forma trigonométrica y polar]]
- **Generaliza:** [[Valor absoluto]] (en $\mathbb R$, el módulo es el valor absoluto)
