---
tipo: teorema
tags: [definicion, teorema, algebra, orden]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "§4.5 · pp. 141-145; Prop. 4.35 y 4.37"
aliases: [Grupo ordenado, Anillo ordenado, Cuerpo totalmente ordenado, Elementos positivos, Reglas de las desigualdades, Desigualdades]
---
# Grupo, anillo y cuerpo ordenado

> [!tip] En palabras sencillas
> Un orden es **compatible** con las operaciones si se pueden "manipular desigualdades" como en el colegio: sumar lo mismo a los dos lados, multiplicar por positivos… Eso es lo que hace de $\mathbb Q$ y $\mathbb R$ cuerpos ordenados (y lo que **no** se puede hacer en $\mathbb C$).

> [!note] Definiciones
> - **Grupo ordenado** $(G,+,\preceq)$: $a\preceq b\Rightarrow a+c\preceq b+c$.
> - **Anillo ordenado** $(A,+,\cdot,\preceq)$: lo anterior y además $0\preceq a,\ 0\preceq b\Rightarrow0\preceq ab$.
> - Si el orden es **total**: grupo/anillo **totalmente ordenado**; si además es cuerpo: **cuerpo ordenado**.
> - $A^+=\{a\mid 0\preceq a\}$ son los **positivos**.

> [!important] Proposición 4.37 (en un anillo totalmente ordenado)
> 1. $a\le b\iff b-a\ge0$
> 2. $a\le b$, $a'\le b'$ $\Rightarrow a+a'\le b+b'$
> 3. $a\le b\Rightarrow -b\le-a$
> 4. $a\le b$, $c\ge0\Rightarrow ac\le bc$
> 5. $a\le b$, $c\le0\Rightarrow bc\le ac$ ← **multiplicar por negativo da la vuelta**
> 6. **$a^2\ge0$ para todo $a$**
> 7. Si es unitario: **$0<1$**
> 8. $|a|\ge0$, y $|a|=0\iff a=0$
> 9. $|ab|=|a||b|$
> 10. **$|a+b|\le|a|+|b|$** (desigualdad triangular)
>
> En un **cuerpo** ordenado, además:
> 11. $a>0\Rightarrow a^{-1}>0$
> 12. $0<a\le b\Rightarrow b^{-1}\le a^{-1}$
> 13. $a\le b<0\Rightarrow b^{-1}\le a^{-1}$

> [!abstract] Demostraciones clave
> - **4:** $b-a\ge0$ y $c\ge0$ ⇒ $(b-a)c\ge0$ ⇒ $bc-ac\ge0$.
> - **6:** si $a\ge0$, $a\cdot a\ge0$. Si $a\le0$, por 5, $a\cdot a\ge0\cdot a=0$.
> - **7:** $1=1^2\ge0$ por 6, y $1\neq0$.
> - **10:** si $a+b\ge0$: $|a+b|=a+b\le|a|+|b|$. Si no: $|a+b|=-a-b\le|a|+|b|$ (usando $\pm a\le|a|$).
> - **11:** si fuera $a^{-1}<0$, por 4: $1=a\,a^{-1}\le a\cdot0=0$, contra 7.

> [!example] Ejemplos
> - ✓ $(\mathbb Z,+,\cdot,\le)$, $(\mathbb Q,\dots)$, $(\mathbb R,\dots)$.
> - $(\mathbb Q^*,\cdot,\le)$ **no** es grupo ordenado: $1\le2$ pero $1\cdot(-1)\not\le2\cdot(-1)$. Sí lo es $(\mathbb Q^+,\cdot,\le)$.
> - $(\mathbb R^2,+,\le_P)$ es un grupo **parcialmente** ordenado.
> - **$\mathbb C$ no se puede ordenar** de forma compatible: por 6, $i^2=-1\ge0$, y por 7, $1>0$, luego $0=1+(-1)>0$. Absurdo. → [[C no es un cuerpo ordenado]]

> [!warning] Errores típicos
> - Multiplicar una desigualdad por algo **sin saber su signo**.
> - Invertir desigualdades con signos mezclados: $-1<2$ pero $-1<\frac12$ (no se da la vuelta).

## Conexiones
- **Necesitas antes:** [[Cuerpo]], [[Relación de orden]]
- **Lleva a:** [[Valor absoluto]], [[Orden en los enteros]], [[Números racionales]], [[Números reales]]
- **Se usa en:** [[C no es un cuerpo ordenado]]
- **Practica:** [[LM Ejercicios Cap 4#Ejercicio 8 · Desigualdades con valor absoluto]]
