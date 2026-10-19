---
tipo: método
tags: [metodo, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.5 · pp. 255-257; Ejemplos 7.12-7.14"
aliases: [Ecuación de segundo grado, Raíz cuadrada en forma binómica, Discriminante, Fórmulas de Cardano-Vieta]
---
# Ecuación de segundo grado en $\mathbb C$

> [!important] Resultado
> La ecuación $az^2+bz+c=0$ con $a,b,c\in\mathbb C$, $a\neq0$, tiene las soluciones
> $$z_{1,2}=\frac{-b\pm\varepsilon}{2a},$$
> donde $\varepsilon$ es **una** raíz cuadrada (compleja) de $\Delta=b^2-4ac$.
> **Siempre tiene solución** (dos, o una doble si $\Delta=0$).

> [!abstract] Por qué (completar el cuadrado)
> Divide por $a$ y usa $z^2+\frac baz=\left(z+\frac b{2a}\right)^2-\frac{b^2}{4a^2}$:
> $$\left(z+\frac b{2a}\right)^2=\frac{\Delta}{4a^2}=\left(\frac\varepsilon{2a}\right)^2\ \Rightarrow\ z+\frac b{2a}=\pm\frac\varepsilon{2a}.$$

> [!note] Cómo calcular $\varepsilon$
> - $\Delta\ge0$ real: $\varepsilon=\sqrt\Delta$.
> - $\Delta<0$ real: $\varepsilon=i\sqrt{-\Delta}$.
> - $\Delta\notin\mathbb R$: en forma polar (si el argumento es cómodo) o **en binómica**:
>   para $\varepsilon=x+iy$ con $\varepsilon^2=\Delta$, resuelve $x^2-y^2=\operatorname{Re}\Delta$, $2xy=\operatorname{Im}\Delta$, y usa el truco $x^2+y^2=|\Delta|$.

> [!example] Ejemplos
> - **7.12:** $\sqrt{5+12i}$: $x^2-y^2=5$, $x^2+y^2=13$ ⇒ $x^2=9$, $y^2=4$, y $xy=6>0$: $\pm(3+2i)$.
> - **7.13:** $z^2+2z+5=0$: $\Delta=-16$, $\varepsilon=4i$, $z=-1\pm2i$.
> - **7.14:** $z^2+2z+1-2i=0$: $\Delta=8i=8e^{i\pi/2}$, $\varepsilon=2\sqrt2e^{i\pi/4}=2+2i$. Soluciones: $z=i$ y $z=-2-i$.

> [!important] Relaciones de Cardano-Vieta (Ejercicio 7)
> $$z_1+z_2=-\frac ba\qquad z_1z_2=\frac ca$$

> [!warning] Ojo
> Con coeficientes **complejos**, las raíces **no** tienen por qué ser conjugadas (en 7.14: $i$ y $-2-i$). Solo lo son si los coeficientes son **reales**.

## Conexiones
- **Necesitas antes:** [[Forma binómica y conjugado]], [[Raíces n-ésimas de un complejo]]
- **Generaliza a:** [[Teorema fundamental del álgebra]]
