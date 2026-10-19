---
tipo: definición
tags: [definicion, teorema, algebra, grupos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Def. 4.8 y Prop. 4.12 · pp. 125-129"
aliases: [Grupos, Grupo abeliano, Grupo conmutativo, Propiedad cancelativa, Grupo de Klein, Tabla de Cayley]
---
# Grupo

> [!tip] En palabras sencillas
> Un grupo es un conjunto con una operación en la que **siempre se puede "deshacer"**: hay un elemento que no hace nada y cada elemento tiene su opuesto. Por eso en un grupo **las ecuaciones $a*x=b$ siempre tienen solución única**.

> [!note] Definición
> $(G,*)$ con $G\neq\emptyset$ es un **grupo** si:
> 1. $*$ es **asociativa**;
> 2. existe **elemento neutro** $e$;
> 3. todo $a\in G$ tiene **simétrico** $a^{-1}$.
>
> Si además $*$ es conmutativa: grupo **conmutativo** o **abeliano**.

> [!example] Ejemplos
> - ✓ $(\mathbb Z,+)$, $(\mathbb Q,+)$, $(\mathbb R,+)$, $(\mathbb C,+)$: abelianos.
> - ✓ $(\mathbb Q^*,\cdot)$, $(\mathbb R^*,\cdot)$, $(\mathbb C^*,\cdot)$: abelianos.
> - ✓ Matrices $n\times m$ con $+$; matrices **invertibles** con $\cdot$ (**no** abeliano).
> - ✓ Biyecciones de $\Omega$ con $\circ$ (no abeliano si $\Omega$ tiene ≥3 elementos).
> - ✓ $(\mathcal P(\Omega),\triangle)$, con neutro $\emptyset$ y $A^{-1}=A$.
> - ✓ **Grupo de Klein** $\{e,a,b,c\}$ con $a^2=b^2=c^2=e$, $ab=c$, $bc=a$, $ca=b$ (las simetrías respecto a los ejes en $\mathbb R^3$).
> - ✗ $(\mathbb N,+)$, $(\mathbb R,\cdot)$ (el 0 no tiene inverso), $(\mathcal P(\Omega),\cap)$, matrices cuadradas con $\cdot$.

> [!important] Proposición 4.12: propiedades de todo grupo
> 1. **Cancelativa:** $a*b=a*c\Rightarrow b=c$.
> 2. **Ecuaciones:** $a*x=b$ tiene **solución única** $x=a^{-1}*b$.
> 3. **Inverso del producto:** $(a*b)^{-1}=b^{-1}*a^{-1}$.

> [!abstract] Demostración (idea y pasos)
> 1. Multiplica **por la izquierda** por $a^{-1}$: $a^{-1}*(a*b)=a^{-1}*(a*c)$; asociativa: $(a^{-1}*a)*b=(a^{-1}*a)*c$; o sea $e*b=e*c$, $b=c$.
> 2. Igual: de $a*x=b$ sale $x=a^{-1}*b$; y ese $x$ funciona.
> 3. Comprueba: $(b^{-1}*a^{-1})*(a*b)=b^{-1}*(a^{-1}*a)*b=b^{-1}*b=e$, y al revés.

> [!tip] Tablas de operación (tablas de Cayley)
> En un grupo finito, en la tabla de la operación **cada elemento aparece exactamente una vez en cada fila y cada columna** (por la propiedad 2). Es un buen test rápido. Simetría respecto a la diagonal ⇔ conmutativo.

> [!warning] Errores típicos
> - En un grupo no abeliano, $a^{-1}*b$ puede ser distinto de $b*a^{-1}$: por eso nunca se escribe $\frac ba$.
> - $(ab)^{-1}=a^{-1}b^{-1}$ **solo** si el grupo es abeliano.

## Conexiones
- **Necesitas antes:** [[Operación interna]], [[Elemento neutro y simétrico]]
- **Lleva a:** [[Subgrupo]], [[Teorema de Lagrange]], [[Anillo]], [[Homomorfismo]]
- **Profundiza:** [[resumen_teoriadegrupos]]
- **Practica:** [[LM Ejercicios Cap 4#Ejercicio 1 · Grupo de tres elementos]]
