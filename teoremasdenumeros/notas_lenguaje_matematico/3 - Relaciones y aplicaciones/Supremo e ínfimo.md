---
tipo: definición
tags: [definicion, teorema, orden]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.25 y Prop. 3.26 · pp. 87-89"
aliases: [Supremo, Ínfimo, sup, inf, Propiedad del supremo, Extremo superior, Extremo inferior]
---
# Supremo e ínfimo

> [!tip] En palabras sencillas
> El **supremo** es **el techo más bajo posible**: la menor de todas las cotas superiores. Puede estar dentro de $A$ (y entonces es el máximo) o justo en el "borde" fuera de $A$.

> [!note] Definición
> - $s=\sup(A)$ si $s$ es cota superior de $A$ y $s\preceq u$ para **toda** cota superior $u$. (= el **mínimo** del conjunto de cotas superiores.)
> - $i=\inf(A)$ si $i$ es cota inferior y $d\preceq i$ para **toda** cota inferior $d$. (= el **máximo** de las cotas inferiores.)

> [!important] Proposición 3.26
> 1. Si existe el supremo (o el ínfimo), es **único** (porque es un mínimo/máximo).
> 2. Si $\sup(A)\in A$, entonces es el **máximo** de $A$. Si $\inf(A)\in A$, es el **mínimo**.
> 3. Si $A$ tiene máximo, entonces $\sup(A)=\max(A)$.

> [!tip] Cómo se reconoce el supremo en $\mathbb R$ (lo usarás mucho)
> $s=\sup A$ si y sólo si:
> - (i) $x\le s$ para todo $x\in A$ (es cota), y
> - (ii) para todo $\varepsilon>0$ existe $x\in A$ con $x>s-\varepsilon$ (nada más pequeño es cota).

> [!example] Ejemplos
> - $(0,1)$: $\sup=1$, $\inf=0$, sin máximo ni mínimo.
> - $\{1-\frac1n\mid n\ge1\}$: $\min=0$, $\sup=1$ (no es máximo).
> - $(\mathbb N^*,\mid)$, $A=\{2,4,6\}$: $\sup=\operatorname{mcm}(4,6)=12$ (no es máximo: $12\notin A$), $\inf=\min=2$.
> - $\{x\in\mathbb Q\mid x^2<2\}$: **en $\mathbb Q$ no tiene supremo**; en $\mathbb R$, $\sup=\sqrt2$. ← esta es la razón de construir $\mathbb R$.

> [!important] Propiedad del supremo
> $(U,\preceq)$ tiene la **propiedad del supremo** si todo subconjunto no vacío y acotado superiormente tiene supremo.
> - $\mathbb R$ la tiene: es el [[Axioma del supremo]].
> - $\mathbb Q$ **no** la tiene: [[Insuficiencia de los racionales]].
> - $(\mathbb R^2,\preceq_L)$ tampoco ([[Orden lexicográfico y orden producto]]).

> [!warning] Errores típicos
> - Pensar que el supremo es "el elemento más grande de $A$": eso es el máximo, que puede no existir.
> - Olvidar el conjunto en el que se busca: el supremo de un subconjunto de $\mathbb Q$ puede existir en $\mathbb R$ y no en $\mathbb Q$.

## Conexiones
- **Necesitas antes:** [[Cotas de un conjunto]], [[Máximo y mínimo]]
- **Lleva a:** [[Axioma del supremo]], [[Números reales]], [[Propiedad arquimediana]]
- **Se usa en:** [[Máximo común divisor]] y [[Mínimo común múltiplo]] (son el ínfimo y el supremo para "divide")
- **Practica:** [[LM Ejercicios Cap 3#Ejercicio 3 · Cotas en el plano]]
