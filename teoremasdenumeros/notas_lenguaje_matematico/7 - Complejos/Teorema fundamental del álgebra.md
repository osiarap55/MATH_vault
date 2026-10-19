---
tipo: teorema
tags: [teorema, complejos, polinomios]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "Teorema 7.19 (comentarios) · pp. 263-264; Ejercicio 19"
aliases: [TFA (álgebra), C es algebraicamente cerrado, Cuerpo algebraicamente cerrado, Teorema de D'Alembert-Gauss]
---
# Teorema fundamental del álgebra

> [!important] Teorema 7.19
> Todo polinomio de grado $\ge1$ con coeficientes complejos tiene **al menos una raíz** en $\mathbb C$.

> [!important] Consecuencia: factorización completa
> Todo polinomio de grado $n\ge1$ se descompone en factores de grado 1:
> $$p(z)=a(z-z_1)(z-z_2)\cdots(z-z_n),$$
> donde $z_1,\dots,z_n$ son sus raíces (no necesariamente distintas). Se dice que **$\mathbb C$ es algebraicamente cerrado**.

> [!tip] En palabras sencillas
> Se inventó $\mathbb C$ solo para resolver $x^2=-1$… y resulta que **ya no hace falta inventar nada más**: cualquier ecuación polinómica tiene solución en $\mathbb C$.

> [!note] Sobre la demostración
> No está en el libro: todas las pruebas conocidas usan **análisis o topología** (no hay una prueba puramente algebraica). La más corta usa el teorema de Liouville del análisis complejo ([[resumen_completo_ahlfors]]). Lo intentaron D'Alembert, Euler, Lagrange, Laplace; Gauss dio las primeras pruebas aceptadas.

> [!example] Consecuencia para polinomios reales (Ejercicio 19)
> Si $p$ tiene coeficientes **reales** y $p(z_1)=0$, entonces $p(\bar z_1)=\overline{p(z_1)}=0$: las raíces no reales vienen **por parejas conjugadas**. Como $(z-z_1)(z-\bar z_1)=z^2-2\operatorname{Re}(z_1)z+|z_1|^2$ tiene coeficientes reales:
> **todo polinomio real se factoriza en polinomios reales de grado 1 y 2.**

## Conexiones
- **Necesitas antes:** [[Números complejos]], [[Ecuación de segundo grado en C]]
- **Relacionado:** [[Números algebraicos y trascendentes]]
- **Profundiza:** [[resumen_completo_ahlfors]], [[resumen_cuerposanillosyteoriadegalois]]
