---
tipo: teorema
tags: [definicion, teorema, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.3 · pp. 250-251"
aliases: [Forma trigonométrica, Forma polar, Producto en forma polar, r_α]
---
# Forma trigonométrica y polar

> [!note] Definición
> Si $z\neq0$ tiene módulo $r$ y argumento $\alpha$:
> $$z=r(\cos\alpha+i\sin\alpha)\quad(\text{trigonométrica})\qquad z=r_\alpha\quad(\text{polar})$$
> - Paso a binómica: $a=r\cos\alpha$, $b=r\sin\alpha$.
> - Paso a polar: $r=\sqrt{a^2+b^2}$, $\alpha$ con $\cos\alpha=\frac ar$, $\sin\alpha=\frac br$.
> - $r_\alpha=r'_{\alpha'}\iff r=r'$ y $\alpha=\alpha'\ [\mathrm{mód}\ 2\pi]$.

> [!important] Teorema: multiplicar en forma polar
> $$r_\alpha\cdot r'_{\alpha'}=(rr')_{\alpha+\alpha'}\qquad\frac{r_\alpha}{r'_{\alpha'}}=\left(\frac r{r'}\right)_{\alpha-\alpha'}\qquad(r_\alpha)^n=(r^n)_{n\alpha}$$
> **Multiplicar = multiplicar módulos y sumar argumentos.**

> [!abstract] Demostración
> $(\cos\alpha+i\sin\alpha)(\cos\alpha'+i\sin\alpha')=(\cos\alpha\cos\alpha'-\sin\alpha\sin\alpha')+i(\sin\alpha\cos\alpha'+\cos\alpha\sin\alpha')$, y por las fórmulas del coseno y seno de la suma, esto es $\cos(\alpha+\alpha')+i\sin(\alpha+\alpha')$.

> [!tip] Cuándo usar cada forma
> - **Sumar/restar:** binómica.
> - **Multiplicar, dividir, potencias, raíces:** polar o exponencial.

## Conexiones
- **Necesitas antes:** [[Módulo y argumento]]
- **Lleva a:** [[Fórmula de De Moivre]], [[Forma exponencial de un complejo]], [[Raíces n-ésimas de un complejo]]
