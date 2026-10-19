---
tipo: teorema
tags: [teorema, enteros, divisibilidad]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Teorema 5.45 · p. 196; Ejercicio 21"
aliases: [mcm, MCM, m.c.m.]
---
# Mínimo común múltiplo

> [!important] Teorema 5.45
> Sean $a,b\in\mathbb N^*$.
> 1. Existe un único $m\in\mathbb N^*$ tal que $a\mathbb Z\cap b\mathbb Z=m\mathbb Z$.
> 2. $m$ es múltiplo común de $a$ y $b$, y **todo múltiplo común de $a$ y $b$ es múltiplo de $m$**.
>
> $m=\operatorname{mcm}(a,b)$.

> [!tip] En palabras sencillas
> Los múltiplos comunes de $a$ y $b$ son exactamente los múltiplos de un número: el mcm.

> [!abstract] Demostración (idea)
> La intersección de dos ideales es un ideal, luego es $m\mathbb Z$ ([[Ideales de Z]]). No es $\{0\}$ porque contiene a $ab$. Los elementos de $a\mathbb Z\cap b\mathbb Z$ son los múltiplos comunes, y son los múltiplos de $m$.

> [!important] Relación con el mcd (Ejercicio 21)
> $$\operatorname{mcd}(a,b)\cdot\operatorname{mcm}(a,b)=a\cdot b$$

> [!example] Ejemplo
> $\operatorname{mcm}(4,6)=12$; $\operatorname{mcd}(4,6)=2$; $2\cdot12=24=4\cdot6$ ✓.
> En el orden "divide" de $\mathbb N^*$, el mcm es el **supremo** de $\{a,b\}$ ([[Supremo e ínfimo]]).

## Conexiones
- **Necesitas antes:** [[Ideales de Z]], [[Divisibilidad]]
- **Pareja:** [[Máximo común divisor]]
