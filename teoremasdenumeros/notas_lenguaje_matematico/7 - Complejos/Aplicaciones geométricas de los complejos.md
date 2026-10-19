---
tipo: método
tags: [metodo, complejos, geometria]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.6 · pp. 257-263; Ejemplos 7.15-7.18"
aliases: [Movimientos del plano con complejos, Giros con complejos, Rotación, Traslación, Homotecia, Simetría axial, Semejanza, Alineación, Perpendicularidad]
---
# Aplicaciones geométricas de los complejos

> [!tip] En palabras sencillas
> Al identificar el plano con $\mathbb C$, la geometría se convierte en **álgebra**: sumar es trasladar, multiplicar por $e^{i\alpha}$ es girar, multiplicar por un real es escalar, conjugar es reflejar.

> [!note] Puntos, distancias y ángulos (Ejemplos 7.15-7.17)
> Sean $A,B,C$ con afijos $z_A,z_B,z_C$.
> | Concepto | Fórmula |
> |---|---|
> | Vector $\vec{AB}$ | $z_B-z_A$ |
> | Punto medio de $AB$ | $\frac{z_A+z_B}2$ |
> | Distancia $AB$ | $\lvert z_B-z_A\rvert$ |
> | Ángulo $(\vec e_1,\vec{AB})$ | $\arg(z_B-z_A)$ |
> | Ángulo $(\vec{AB},\vec{AC})$ | $\arg\dfrac{z_C-z_A}{z_B-z_A}$ |
> | $A,B,C$ **alineados** | $\dfrac{z_C-z_A}{z_B-z_A}$ es **real** |
> | $AB\perp AC$ | $\dfrac{z_C-z_A}{z_B-z_A}$ es **imaginario puro** |

> [!note] Movimientos del plano (Ejemplo 7.18)
> | Transformación | Fórmula ($z\mapsto z'$) |
> |---|---|
> | Traslación de vector $w$ | $z'=z+w$ |
> | Giro de centro $O$ y ángulo $\alpha$ | $z'=e^{i\alpha}z$ |
> | Giro de centro $\omega$ y ángulo $\alpha$ | $z'-\omega=e^{i\alpha}(z-\omega)$ |
> | Homotecia de centro $\omega$ y razón $k\in\mathbb R^*$ | $z'-\omega=k(z-\omega)$ |
> | Semejanza $z'=wz$ | homotecia de razón $\lvert w\rvert$ + giro de ángulo $\arg w$ |
> | Simetría respecto al eje real | $z'=\bar z$ |
> | Simetría respecto a una recta por $O$ de ángulo $\alpha$ | $z'=e^{2i\alpha}\bar z$ |

> [!abstract] Idea: girar alrededor de un punto $\omega$
> Traslada $\omega$ al origen ($z-\omega$), gira ($e^{i\alpha}(z-\omega)$) y deshaz la traslación ($+\omega$). La misma idea (girar para llevar la recta al eje real, reflejar y deshacer el giro) da la fórmula de la simetría.

> [!example] Ejercicio tipo
> Cuadrado de centro $(1,1)$ con un vértice en $(2,1+\sqrt3)$: los otros vértices se obtienen girando $\frac\pi2$, $\pi$, $\frac{3\pi}2$ alrededor del centro: $z_k=(1+i)+i^k\big(1+i\sqrt3\big)$.

## Conexiones
- **Necesitas antes:** [[Plano complejo]], [[Forma exponencial de un complejo]], [[Módulo y argumento]]
- **Profundiza:** geometría afín y euclídea (tu carpeta `geometria_topologia/geometria/geometriaanalitica`)
