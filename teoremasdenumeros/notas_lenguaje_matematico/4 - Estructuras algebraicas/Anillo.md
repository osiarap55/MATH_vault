---
tipo: definición
tags: [definicion, teorema, algebra, anillos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Def. 4.18 y Prop. 4.21 · pp. 132-135"
aliases: [Anillos, Anillo conmutativo, Anillo unitario, Elemento inversible, Unidad, Propiedad distributiva]
---
# Anillo

> [!tip] En palabras sencillas
> Un anillo es un conjunto donde se puede **sumar, restar y multiplicar** (pero no necesariamente dividir), con las reglas de siempre: el modelo es $\mathbb Z$.

> [!note] Definición
> $(A,+,\cdot)$ es un **anillo** si:
> 1. $(A,+)$ es un [[Grupo]] **abeliano** (neutro $0$, opuesto $-a$);
> 2. $\cdot$ es **asociativa**;
> 3. $\cdot$ es **distributiva** respecto a $+$: $a(b+c)=ab+ac$ y $(b+c)a=ba+ca$.
>
> - **Conmutativo** si $ab=ba$.
> - **Unitario** si tiene neutro del producto $1\neq0$.
> - $a$ es **inversible** (una *unidad*) si existe $a^{-1}$ con $aa^{-1}=a^{-1}a=1$.

> [!example] Ejemplos
> - $\mathbb Z$, $\mathbb Q$, $\mathbb R$, $\mathbb C$: anillos conmutativos unitarios.
> - Matrices $n\times n$: anillo unitario **no conmutativo**.
> - $(\mathcal P(\Omega),\triangle,\cap)$: conmutativo unitario (unidad $\Omega$).
> - $\mathbb Z/n$: conmutativo unitario ([[Congruencia módulo n]]).
> - $\mathbb Z[\sqrt2]=\{a+b\sqrt2\}$: subanillo de $\mathbb R$.
> - $n\mathbb Z$ ($n\ge2$): anillo **sin** unidad.

> [!important] Proposición 4.21: reglas de cálculo
> 1. $a\cdot0=0\cdot a=0$ (el 0 es **absorbente**).
> 2. $(-a)b=a(-b)=-(ab)$ y $(-a)(-b)=ab$ ("menos por menos es más").
> 3. Si es **conmutativo**: $(a+b)^2=a^2+2ab+b^2$, $(a+b)(a-b)=a^2-b^2$ y el [[Binomio de Newton]].

> [!abstract] Demostración de 1 y 2
> 1. $a\cdot0=a(0+0)=a\cdot0+a\cdot0$. Por la cancelativa del grupo $(A,+)$, $a\cdot0=0$.
> 2. $ab+(-a)b=(a+(-a))b=0\cdot b=0$, luego $(-a)b$ es el opuesto de $ab$. Aplicándolo dos veces, $(-a)(-b)=ab$.
>
> **"Menos por menos es más" no es un convenio: es un teorema** que sale de la distributiva.

> [!warning] Errores típicos
> - En un anillo **no** conmutativo (matrices), $(a+b)^2=a^2+ab+ba+b^2\neq a^2+2ab+b^2$.
> - En un anillo, $ab=0$ **no** implica $a=0$ o $b=0$ ([[Dominio de integridad]]).
> - $ab=ac$ **no** implica $b=c$ (no hay cancelativa del producto en general).

## Conexiones
- **Necesitas antes:** [[Grupo]]
- **Lleva a:** [[Dominio de integridad]], [[Subanillo]], [[Ideal]], [[Cuerpo]], [[Binomio de Newton]]
- **Ejemplos centrales:** [[Números enteros]], [[Congruencia módulo n]]
- **Profundiza:** [[resumen_cuerposanillosyteoriadegalois]]
