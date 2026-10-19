---
tipo: teorema
tags: [teorema, enteros, divisibilidad]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Teorema 5.46 y Ejercicio 5.47 · pp. 196-197; Def. 5.50"
aliases: [mcd, MCD, m.c.d., Primos entre sí, Coprimos]
---
# Máximo común divisor

> [!important] Teorema 5.46
> Sean $a,b\in\mathbb N^*$.
> 1. Existe un único $d\in\mathbb N^*$ tal que $a\mathbb Z+b\mathbb Z=d\mathbb Z$.
> 2. $d$ es divisor común de $a$ y $b$, y **todo divisor común de $a$ y $b$ divide a $d$**.
>
> $d=\operatorname{mcd}(a,b)$. Además $d=au+bv$ para ciertos $u,v\in\mathbb Z$ ([[Identidad de Bézout]]).

> [!tip] En palabras sencillas
> El mcd no es solo "el mayor" divisor común: es uno al que **todos los demás divisores comunes dividen**. Y se puede escribir como **combinación** de $a$ y $b$.

> [!abstract] Demostración (idea y pasos)
> 1. $a\mathbb Z+b\mathbb Z=\{am+bn\}$ es un ideal ⇒ es $d\mathbb Z$ ([[Ideales de Z]]).
> 2. $a=a\cdot1+b\cdot0\in d\mathbb Z$ y $b\in d\mathbb Z$: $d$ divide a ambos.
> 3. $d\in a\mathbb Z+b\mathbb Z$, luego $d=au+bv$.
> 4. Si $n\mid a$ y $n\mid b$, entonces $n\mid au+bv=d$. ∎

> [!note] Primos entre sí (Def. 5.50)
> $a,b$ son **primos entre sí** (coprimos) si $\operatorname{mcd}(|a|,|b|)=1$.

> [!important] Ejercicio 5.47: simplificar por el mcd
> $d=\operatorname{mcd}(a,b)\iff a=da'$, $b=db'$ con $\operatorname{mcd}(a',b')=1$.
> Es lo que garantiza que **toda fracción se puede escribir irreducible** ([[Números racionales]], [[Irracionalidad de raíz de 2]]).

> [!tip] Cómo se calcula
> Con el [[Algoritmo de Euclides]].

## Conexiones
- **Necesitas antes:** [[Ideales de Z]], [[Divisibilidad]]
- **Lleva a:** [[Identidad de Bézout]], [[Algoritmo de Euclides]], [[Lema de Euclides]]
- **Pareja:** [[Mínimo común múltiplo]]
- **En el orden "divide":** el mcd es el ínfimo ([[Supremo e ínfimo]])
