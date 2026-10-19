---
tipo: teorema
tags: [teorema, metodo, conjuntos, naturales]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "Ejemplo 2.5 · pp. 38-40; Comentarios cap. 2 · pp. 65-66; cap. 5"
aliases: [Inducción, Inducción matemática, Demostración por inducción, Inducción completa, Inducción fuerte, Método de inducción]
---
# Principio de inducción

> [!tip] En palabras sencillas
> Es el **efecto dominó**: si tiras la primera ficha ($P(0)$) y cada ficha tira la siguiente ($P(n)\Rightarrow P(n+1)$), caen todas.

> [!important] Principio de inducción
> Sea $P$ una propiedad sobre $\mathbb N$ tal que:
> 1. **Caso base:** $P(0)$ es cierta.
> 2. **Paso inductivo:** para todo $n$, si $P(n)$ es cierta entonces $P(n+1)$ es cierta.
>
> Entonces $P(n)$ es cierta **para todo** $n\in\mathbb N$.

> [!abstract] Por qué es cierto
> Sea $M=\{n\in\mathbb N\mid P(n)\}$. Por 1, $0\in M$. Por 2, si $n\in M$ entonces su sucesor está en $M$. El **quinto [[Axiomas de Peano|axioma de Peano]]** dice justo que un subconjunto así es todo $\mathbb N$. Luego $M=\mathbb N$.
> (Equivale a que $\mathbb N$ esté [[Buen orden|bien ordenado]].)

> [!note] Variantes
> - **Empezando en $a$:** si $P(a)$ y $\forall n\ge a\ (P(n)\Rightarrow P(n+1))$, entonces $P(n)$ para todo $n\ge a$. (Típico: empezar en $n=1$.)
> - **Inducción completa (fuerte):** si $P(0)$ y "$P(k)$ para todo $k\le n$" $\Rightarrow P(n+1)$, entonces $P(n)$ para todo $n$. Útil cuando para el paso necesitas **varios** casos anteriores (p. ej. Fibonacci, o "todo $n\ge2$ es producto de primos").

> [!example] Ejemplo (Ejercicio 2.6): $\displaystyle\sum_{k=0}^n\frac{k}{2^k}=2-\frac{n+2}{2^n}$
> 1. **Base** $n=0$: izquierda $=0$; derecha $=2-\frac{2}{1}=0$ ✓.
> 2. **Hipótesis de inducción:** supón que es cierta para $n$.
> 3. **Paso:** $\displaystyle\sum_{k=0}^{n+1}\frac{k}{2^k}=\Big(2-\frac{n+2}{2^n}\Big)+\frac{n+1}{2^{n+1}}=2-\frac{2n+4-n-1}{2^{n+1}}=2-\frac{(n+1)+2}{2^{n+1}}$ ✓. ∎

> [!warning] Errores típicos
> - **Olvidar el caso base.** "Todo $n$ cumple $n=n+1$" tiene paso inductivo correcto ($n=n+1\Rightarrow n+1=n+2$) pero es falsa.
> - En el paso, **suponer lo que quieres probar para $n+1$**. Se supone $P(n)$ y se *llega* a $P(n+1)$.
> - No usar la hipótesis de inducción: si no la usas, o la prueba es directa o hay un error.

## Conexiones
- **Necesitas antes:** [[Axiomas de Peano]], [[Cuantificadores]]
- **Lleva a:** [[Definición por recurrencia]], [[Buen orden]]
- **Se usa en:** [[Conjunto de las partes]] ($2^n$ subconjuntos), [[Teorema fundamental de la aritmética]], [[Fórmula de De Moivre]], [[Conjunto finito]], [[Binomio de Newton]]
- **Otros métodos:** [[Métodos de demostración]]
