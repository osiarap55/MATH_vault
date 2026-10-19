---
tipo: teorema
tags: [teorema, racionales, reales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "§6.3 · pp. 217-218; Ejemplo 6.7; Comentarios (números conmensurables) · pp. 229-230"
aliases: [Q no es completo, Q tiene agujeros, Inconmensurables, Magnitudes inconmensurables, Números conmensurables]
---
# Insuficiencia de los números racionales

> [!tip] En palabras sencillas
> Si dibujas todos los racionales en una recta, **quedan huecos**: por ejemplo, donde "debería" estar $\sqrt2$. Formalmente: hay conjuntos de racionales acotados que **no tienen supremo en $\mathbb Q$**.

> [!important] Ejemplo 6.7
> $A=\{x\in\mathbb Q\mid x\ge0,\ x^2<2\}$ está acotado superiormente (por 2) pero **no tiene supremo en $\mathbb Q$**.

> [!abstract] Demostración (idea y pasos)
> Las cotas superiores racionales de $A$ son $B=\{r\in\mathbb Q\mid r>0,\ r^2>2\}$ (no hay ninguna con $r^2=2$: [[Irracionalidad de raíz de 2]]). Hay que ver que **$B$ no tiene mínimo**: dado $r\in B$, encontramos otra cota $s\in B$ más pequeña.
> 1. Toma $s=\dfrac{2r+2}{r+2}\in\mathbb Q$, $s>0$.
> 2. **$s<r$:** $r-s=\dfrac{r^2-2}{r+2}>0$.
> 3. **$s$ es cota:** $s^2-2=\dfrac{2(r^2-2)}{(r+2)^2}>0$.
> Así ninguna cota es la menor: no hay supremo. ∎

> [!note] Historia: magnitudes inconmensurables (comentarios)
> Para los griegos, dos segmentos eran **conmensurables** si se podían medir con una misma unidad (cociente racional). Para hallar esa unidad usaban… el [[Algoritmo de Euclides]] con segmentos. Si el algoritmo **no termina**, las magnitudes son **inconmensurables** (cociente irracional). La diagonal y el lado de un cuadrado lo son ($\sqrt2$), y también la diagonal y el lado del pentágono regular (razón áurea $\frac{1+\sqrt5}2$).

> [!important] La solución
> Postular un cuerpo ordenado **sin agujeros**: el que cumple el [[Axioma del supremo]]. Ese es $\mathbb R$.

## Conexiones
- **Necesitas antes:** [[Irracionalidad de raíz de 2]], [[Supremo e ínfimo]], [[Números racionales]]
- **Lleva a:** [[Axioma del supremo]], [[Números reales]], [[Cortaduras de Dedekind]]
