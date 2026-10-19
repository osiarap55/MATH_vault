---
tipo: teorema
tags: [definicion, teorema, racionales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Ejemplo 3.9; §6.1 · pp. 208-215; Def. 6.1, Teoremas 6.2 y 6.4, Prop. 6.5-6.6"
aliases: [Q, ℚ, Racionales, Fracción, Fracción irreducible, Construcción de Q, Construcción de los racionales]
---
# Números racionales  $\mathbb Q$

> [!tip] En palabras sencillas
> En $\mathbb Z$ no siempre se puede dividir ($6x=2$ no tiene solución). **Un racional es "una división pendiente" $a/b$**, representada por el par $(a,b)$. Como $\frac12=\frac24=\frac{-3}{-6}$, varios pares representan el mismo número: de nuevo, una relación de equivalencia.

> [!note] Construcción (Def. 6.1)
> En $\mathbb Z\times\mathbb Z^*$:
> $$(a,b)\sim(a',b')\iff ab'=ba'\qquad(\text{"}a/b=a'/b'\text{" sin dividir})$$
> $\mathbb Q=(\mathbb Z\times\mathbb Z^*)/\!\sim$, y la clase de $(a,b)$ se escribe $\frac ab$.
> - **Fracción irreducible** (representante canónico): dividiendo por $d=\operatorname{mcd}(|a|,|b|)$ ([[Máximo común divisor|Ej. 5.47]]); única si se pide denominador $>0$. Cualquier otro representante es proporcional a ella (por el [[Lema de Euclides|teorema de Gauss]]).
> - Dibujo: cada clase son los puntos enteros de una recta por el origen.

> [!note] Operaciones y orden
> $$\frac ab+\frac cd=\frac{ad+bc}{bd}\qquad\frac ab\cdot\frac cd=\frac{ac}{bd}\qquad\frac ab\ge0\iff ab\ge0$$
> (bien definidas: no dependen de los representantes). Inverso de $\frac ab\neq0$: $\frac ba$.

> [!important] Teoremas
> - **6.2:** $(\mathbb Q,+,\cdot)$ es un [[Cuerpo]].
> - **6.4:** $(\mathbb Q,+,\cdot,\le)$ es un [[Cuerpo ordenado]].
> - **$\mathbb Z\subset\mathbb Q$:** $a\mapsto\frac a1$ es un isomorfismo de anillos ordenados. Así $\frac ab=ab^{-1}$.
> - **6.5 (arquimediana):** si $\alpha>0$, para todo $\beta$ existe $n$ con $n\alpha>\beta$.
> - **6.6 (orden divisible/denso):** si $\alpha<\beta$, existe $\gamma\in\mathbb Q$ con $\alpha<\gamma<\beta$ (por ejemplo $\gamma=\frac{\alpha+\beta}2$). **Falso en $\mathbb Z$** (orden discreto).
> - $\mathbb Q$ es **numerable** ([[Conjunto numerable]]).

> [!warning] Pero le falta algo
> $\mathbb Q$ no cumple la propiedad del supremo: [[Insuficiencia de los racionales]].

## Conexiones
- **Necesitas antes:** [[Números enteros]], [[Conjunto cociente]], [[Cuerpo ordenado]]
- **Lleva a:** [[Expresión decimal]], [[Insuficiencia de los racionales]], [[Números reales]], [[Densidad de Q en R]]
