---
tipo: definición
tags: [definicion, relaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.1 · p. 77"
aliases: [Relaciones de equivalencia, Equivalencia]
---
# Relación de equivalencia

> [!tip] En palabras sencillas
> Una relación de equivalencia dice cuándo dos cosas son "**iguales en algo**" (misma edad, mismo resto al dividir entre 5, misma dirección…). Sirve para **clasificar**: los que son "iguales en ese algo" forman un grupo (una **clase**).

> [!note] Definición
> Una relación $\sim$ en $U$ es **de equivalencia** si es:
> 1. **Reflexiva:** $x\sim x$
> 2. **Simétrica:** $x\sim y\Rightarrow y\sim x$
> 3. **Transitiva:** $x\sim y$ y $y\sim z$ $\Rightarrow x\sim z$

> [!example] Ejemplos importantes
> | Conjunto | Relación | Clases | Cociente |
> |---|---|---|---|
> | Vectores fijos | equipolencia (misma dirección, módulo y sentido) | vectores libres | — |
> | Ecuaciones $ax+by+c=0$ | coeficientes proporcionales | rectas del plano | — |
> | Rectas del plano | paralelismo | direcciones | — |
> | $\mathbb N\times\mathbb N$ | $(a,b)\sim(c,d)\iff a+d=b+c$ | "$a-b$" | [[Números enteros\|$\mathbb Z$]] |
> | $\mathbb Z\times\mathbb Z^*$ | $(a,b)\sim(c,d)\iff ad=bc$ | fracciones $\frac ab$ | [[Números racionales\|$\mathbb Q$]] |
> | $\mathbb Z$ | $a\equiv b\pmod p\iff p\mid a-b$ | restos | [[Congruencia módulo n\|$\mathbb Z/p$]] |
> | $\mathbb R$ | $a-b=2k\pi$ | ángulos | $\mathbb R/2\pi$ |
> | $\mathbb R^*$ | $xy>0$ | positivos, negativos | 2 clases |
> | $A$ (con $f:A\to B$) | $f(x)=f(y)$ | fibras $f^{-1}(b)$ | ver [[Factorización canónica de una aplicación]] |

> [!failure] No son de equivalencia
> - $\le$: no es simétrica.
> - "ser amigo de": no suele ser transitiva.
> - $|x-y|<1$ en $\mathbb R$: no es transitiva ($0\sim0{,}9\sim1{,}8$ pero $0\not\sim1{,}8$).

> [!warning] Errores típicos
> - Comprobar solo simétrica y transitiva. La reflexiva también hay que comprobarla (no se deduce de las otras si hay elementos sin relacionar).
> - Al definir algo sobre las clases (como la suma en $\mathbb Z$), hay que comprobar que **no depende del representante elegido** ("está bien definido").

## Conexiones
- **Necesitas antes:** [[Propiedades de una relación]]
- **Lleva a:** [[Clase de equivalencia]], [[Conjunto cociente]], [[Partición de un conjunto]]
- **Se usa para construir:** [[Números enteros]], [[Números racionales]], [[Congruencia módulo n]], [[Cortaduras de Dedekind]]
- **Practica:** [[LM Ejercicios Cap 3#Ejercicio 2 · Una relación de equivalencia]]
