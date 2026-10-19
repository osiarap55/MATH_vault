---
tipo: teorema
tags: [teorema, definicion, relaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.12 · p. 81"
aliases: [Partición, Particiones, Equivalencia y partición]
---
# Partición de un conjunto

> [!tip] En palabras sencillas
> Partir un conjunto es **repartirlo en trozos** que no se solapan y que juntos lo cubren todo (como un puzle). **Dar una partición y dar una relación de equivalencia es exactamente lo mismo.**

> [!note] Definición
> Una **partición** de $U$ es una familia $\mathcal P$ de subconjuntos (no vacíos) de $U$ tal que
> 1. son **disjuntos dos a dos**: $A\neq B$ en $\mathcal P$ ⇒ $A\cap B=\emptyset$;
> 2. su **unión es $U$**: $\bigcup_{A\in\mathcal P}A=U$.

> [!important] Teorema: equivalencias ⇔ particiones
> - Toda relación de equivalencia $\sim$ en $U$ da una partición: el [[Conjunto cociente]] $U/\!\sim$.
> - Toda partición $\mathcal P$ da una relación de equivalencia: $x\sim y\iff$ $x$ e $y$ están en el **mismo trozo**.

> [!abstract] Demostración (idea y pasos)
> **(⇒)** Las clases no son vacías ($x\in[x]$), cubren $U$ (cada $x$ está en la suya) y dos clases distintas son disjuntas ([[Clase de equivalencia|propiedad 2]]).
> **(⇐)** Reflexiva: cada $x$ está en algún trozo (la unión es $U$). Simétrica: obvio. Transitiva: si $x,y\in A$ e $y,z\in B$, entonces $y\in A\cap B$, y como los trozos son disjuntos, $A=B$; luego $x,z$ están en el mismo trozo.

> [!example] Ejemplos
> - $\{[i-1,i)\mid i\in\mathbb Z\}$ es una partición de $\mathbb R$. La relación asociada: "tener la misma [[Parte entera]]".
> - Una rejilla de cuadraditos en $[0,1]^2$ (como la que usa un ordenador para dibujar superficies) es una partición; de cada cuadradito se toma un representante.
> - $\{\text{pares},\text{impares}\}$ es una partición de $\mathbb Z$ (congruencia módulo 2).

## Conexiones
- **Necesitas antes:** [[Clase de equivalencia]], [[Familias de conjuntos]]
- **Se usa en:** [[Conjunto de las partes]] (separar subconjuntos que contienen o no a $a$), [[Factorización canónica de una aplicación]], conteo en [[Conjunto finito]]
