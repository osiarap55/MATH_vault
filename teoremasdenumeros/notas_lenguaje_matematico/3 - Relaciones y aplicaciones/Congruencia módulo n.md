---
tipo: definición
tags: [definicion, relaciones, enteros]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Ejemplo 3.10 · p. 80; cap. 4 y 5"
aliases: [Congruencia, Enteros módulo n, Z/n, Z/p, Aritmética modular, Congruencias]
---
# Congruencia módulo $n$  ($\mathbb Z/n$)

> [!tip] En palabras sencillas
> Dos enteros son congruentes módulo $n$ si **dan el mismo resto al dividir entre $n$**. Es la "aritmética del reloj": en un reloj de 12 horas, $15\equiv3$.

> [!note] Definición
> $$a\equiv b\pmod n\iff n\mid(a-b)\iff\exists k\in\mathbb Z:\ a-b=kn$$
> Es una [[Relación de equivalencia]]. Su [[Conjunto cociente]] es
> $$\mathbb Z/n=\{\bar0,\bar1,\dots,\overline{n-1}\},$$
> y la clase $\bar0=n\mathbb Z=\{kn\mid k\in\mathbb Z\}$ son los múltiplos de $n$.

> [!abstract] Por qué es de equivalencia
> - Reflexiva: $a-a=0=0\cdot n$.
> - Simétrica: $a-b=kn\Rightarrow b-a=(-k)n$.
> - Transitiva: $a-b=kn$, $b-c=k'n\Rightarrow a-c=(k+k')n$.

> [!important] Se puede operar con las clases
> Si $a\equiv a'$ y $b\equiv b'$ (mód $n$), entonces $a+b\equiv a'+b'$ y $ab\equiv a'b'$. Por eso están bien definidas $\bar a+\bar b=\overline{a+b}$ y $\bar a\cdot\bar b=\overline{ab}$, y $\mathbb Z/n$ es un [[Anillo]].
> **$\mathbb Z/n$ es un [[Cuerpo]] si y sólo si $n$ es primo.**

> [!example] Ejemplos
> - $17\equiv2\pmod5$, porque $17-2=15=3\cdot5$.
> - $-1\equiv n-1\pmod n$.
> - En $\mathbb Z/6$: $\bar2\cdot\bar3=\bar0$. ¡Producto de dos no nulos da cero! (No es [[Dominio de integridad]].)

## Conexiones
- **Necesitas antes:** [[Relación de equivalencia]], [[Divisibilidad]], [[División euclídea]]
- **Lleva a:** [[Anillo]], [[Cuerpo]], [[Números primos]]
- **Más allá del libro:** aritmética modular, criptografía (RSA), teoría de números
