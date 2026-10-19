---
tipo: definición
tags: [definicion, relaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "§3.1 · pp. 75-76"
aliases: [Propiedad reflexiva, Propiedad simétrica, Propiedad antisimétrica, Propiedad transitiva, Reflexiva, Simétrica, Antisimétrica, Transitiva]
---
# Propiedades de una relación

> [!tip] En palabras sencillas
> Cuatro preguntas que se le hacen a una relación $\mathcal R$ en un conjunto $U$:
> - **Reflexiva:** ¿todo el mundo está relacionado consigo mismo?
> - **Simétrica:** si $x$ va con $y$, ¿$y$ va con $x$?
> - **Antisimétrica:** si van en los dos sentidos, ¿es porque son el mismo?
> - **Transitiva:** si $x$ va con $y$ e $y$ con $z$, ¿$x$ va con $z$?

> [!note] Definición
> | Propiedad | Con cuantificadores | Con conjuntos |
> |---|---|---|
> | Reflexiva | $\forall x:\ x\mathcal Rx$ | contiene la diagonal $\{(x,x)\}$ |
> | Simétrica | $\forall x,y:\ x\mathcal Ry\Rightarrow y\mathcal Rx$ | $\mathcal R^{-1}\subseteq\mathcal R$ |
> | Antisimétrica | $\forall x,y:\ (x\mathcal Ry\land y\mathcal Rx)\Rightarrow x=y$ | $\mathcal R\cap\mathcal R^{-1}\subseteq$ diagonal |
> | Transitiva | $\forall x,y,z:\ (x\mathcal Ry\land y\mathcal Rz)\Rightarrow x\mathcal Rz$ | $\mathcal R\circ\mathcal R\subseteq\mathcal R$ |
>
> En $\mathbb R$: reflexiva ⇔ el dibujo contiene la recta $y=x$; simétrica ⇔ el dibujo es simétrico respecto a $y=x$.

> [!example] Ejemplos en $\mathbb N^*$
> | Relación | Refl. | Sim. | Antisim. | Trans. | Tipo |
> |---|:-:|:-:|:-:|:-:|---|
> | $x\le y$ | ✓ | ✗ | ✓ | ✓ | [[Relación de orden\|orden]] total |
> | $x\mid y$ (divide) | ✓ | ✗ | ✓ | ✓ | orden parcial |
> | $x=y$ | ✓ | ✓ | ✓ | ✓ | equivalencia **y** orden |
> | $x\neq y$ | ✗ | ✓ | ✗ | ✗ | — |
> | $x+y=20$ | ✗ | ✓ | ✗ | ✗ | — |
> | $x-y=1$ | ✗ | ✗ | ✓ | ✗ | — |
> | $xy$ es un cuadrado | ✓ | ✓ | ✗ | ✓ | [[Relación de equivalencia\|equivalencia]] |

> [!warning] Errores típicos
> - **Antisimétrica no es "no simétrica".** Una relación puede ser las dos cosas ($=$) o ninguna ($x+y=20$ no es antisimétrica: $1\mathcal R19$ y $19\mathcal R1$).
> - "$x-y=1$" es antisimétrica **por vacuidad**: nunca ocurre $x\mathcal Ry$ y $y\mathcal Rx$ a la vez, y un condicional con antecedente falso es verdadero ([[Condicional]]).
> - Para refutar una propiedad basta **un contraejemplo** concreto.

## Conexiones
- **Necesitas antes:** [[Relación binaria]], [[Cuantificadores]]
- **Lleva a:** [[Relación de equivalencia]], [[Relación de orden]]
- **Practica:** [[LM Ejercicios Cap 3#Ejercicio 1 · Propiedades de relaciones]]
