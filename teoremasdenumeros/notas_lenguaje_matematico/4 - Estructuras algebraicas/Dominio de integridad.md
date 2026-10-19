---
tipo: definición
tags: [definicion, algebra, anillos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "§4.3 · pp. 135-136; Ejercicio 4.23"
aliases: [Divisor de cero, Divisores de cero, Anillo íntegro, Dominio íntegro]
---
# Dominio de integridad (divisores de cero)

> [!tip] En palabras sencillas
> En los números, si $ab=0$ entonces $a=0$ o $b=0$. **No en todos los anillos pasa eso.** Los elementos que "multiplicados por algo no nulo dan cero" se llaman divisores de cero. Un anillo sin ellos es **íntegro**.

> [!note] Definición
> - $a\neq0$ es **divisor de cero** si existe $b\neq0$ con $ab=0$.
> - Un anillo es **íntegro** si no tiene divisores de cero: $ab=0\Rightarrow a=0\ \lor\ b=0$.
> - Un **dominio de integridad** es un anillo conmutativo unitario e íntegro.

> [!important] Proposición (Ejercicio 4.23)
> En un anillo unitario, **un elemento inversible no es divisor de cero**.
> *Idea:* si $a$ es inversible y $ab=0$, multiplica por $a^{-1}$: $b=a^{-1}ab=0$.
> Consecuencia: **un [[Cuerpo]] no tiene divisores de cero.**

> [!important] En un anillo íntegro se puede simplificar
> $ab=ac$ y $a\neq0$ $\Rightarrow$ $a(b-c)=0\Rightarrow b=c$.

> [!example] Ejemplos
> - ✓ Íntegros: $\mathbb Z$, $\mathbb Q$, $\mathbb R$, $\mathbb Z[\sqrt2]$, $\mathbb Z/p$ con $p$ primo.
> - ✗ $\mathbb Z/6$: $\bar2\cdot\bar3=\bar0$.
> - ✗ Matrices: $\begin{pmatrix}1&1\\1&1\end{pmatrix}\begin{pmatrix}-1&1\\1&-1\end{pmatrix}=0$.
> - ✗ $(\mathcal P(\Omega),\triangle,\cap)$: $A\cap\bar A=\emptyset$ (el "cero").
> - **Todo dominio de integridad finito es un cuerpo** (ver [[LM Ejercicios Cap 4#Ejercicio 6 · Íntegro y finito implica cuerpo|ejercicio]]).

> [!warning] Error típico
> Resolver $x^2=x$ en matrices o en $\mathbb Z/6$ "simplificando": $x(x-1)=0$ **no** da solo $x=0,1$. En $\mathbb Z/6$, $\bar3^2=\bar9=\bar3$ y $\bar4^2=\overline{16}=\bar4$.

## Conexiones
- **Necesitas antes:** [[Anillo]]
- **Lleva a:** [[Cuerpo]]
- **Se usa en:** resolver ecuaciones en $\mathbb Z$, $\mathbb R$… ($ab=0$), [[Silogismo disyuntivo]]
