---
tipo: definición
tags: [definicion, teorema, algebra, cuerpos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Def. 4.30 y Prop. 4.33-4.34 · pp. 138-141"
aliases: [Cuerpos, Subcuerpo, Cuerpo conmutativo, Field]
---
# Cuerpo

> [!tip] En palabras sencillas
> Un cuerpo es un conjunto donde se puede **sumar, restar, multiplicar y dividir** (entre lo que no sea cero), con todas las reglas habituales. El modelo es $\mathbb Q$ o $\mathbb R$.

> [!note] Definición
> $(K,+,\cdot)$ es un **cuerpo** si $+$ y $\cdot$ son asociativas y conmutativas, $\cdot$ es distributiva respecto de $+$, existen neutros $0\neq1$, todo $a$ tiene opuesto $-a$ y **todo $a\neq0$ tiene inverso $a^{-1}$**.
>
> **Prop. 4.33 (forma compacta):** $K$ es cuerpo $\iff$ $(K,+)$ es grupo abeliano, $(K^*,\cdot)$ es grupo abeliano ($K^*=K\setminus\{0\}$) y vale la distributiva.

> [!important] Consecuencias
> - $a\cdot0=0$.
> - **No hay divisores de cero:** $ab=0\Rightarrow a=0$ o $b=0$ ([[Dominio de integridad]]).
> - **Cancelativa:** $ab=ac$, $a\neq0\Rightarrow b=c$.
> - **La ecuación $ax+b=0$ ($a\neq0$) tiene solución única** $x=-ba^{-1}$.

> [!example] Ejemplos
> - ✓ $\mathbb Q$, $\mathbb R$, $\mathbb C$.
> - ✓ $\mathbb Z/3$: tabla del producto $\bar1\cdot\bar1=\bar1$, $\bar2\cdot\bar2=\bar1$. Todo no nulo tiene inverso.
> - ✗ $\mathbb Z/4$: $\bar2$ no tiene inverso ($\bar2\cdot\bar x\in\{\bar0,\bar2\}$).
> - ✗ $\mathbb Z$, $\mathbb Z[\sqrt2]$: el 2 no tiene inverso.
> - **Teorema:** $\mathbb Z/n$ es cuerpo $\iff$ $n$ es primo (ver [[LM Ejercicios Cap 4#Ejercicio 5 · Z-n es cuerpo si y sólo si n es primo|ejercicio]]).

> [!important] Subcuerpo (Prop. 4.34)
> $H\neq\emptyset$ es subcuerpo de $K$ $\iff$ $a-b\in H$ para $a,b\in H$, y $ab^{-1}\in H$ para $a,b\in H^*$.
> Ejemplo: $\mathbb Q\subseteq\mathbb R\subseteq\mathbb C$.

> [!note] Convenio
> En este libro "cuerpo" incluye que el producto sea **conmutativo** (en inglés *field*). Si no lo es, se llama *anillo de división*.

## Conexiones
- **Necesitas antes:** [[Anillo]], [[Grupo]], [[Dominio de integridad]]
- **Lleva a:** [[Cuerpo ordenado]], [[Números racionales]], [[Números reales]], [[Números complejos]]
- **Profundiza:** [[resumen_cuerposanillosyteoriadegalois]], [[resumen_algebralineal]] (los espacios vectoriales se definen sobre un cuerpo)
