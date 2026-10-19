---
tipo: definición
tags: [definicion, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "Ejemplo 2.27 · p. 53"
aliases: [Diferencia simétrica de conjuntos, Δ]
---
# Diferencia simétrica  $A\,\triangle\,B$

> [!tip] En palabras sencillas
> Lo que está en **uno solo** de los dos conjuntos. Es la unión quitando la parte común. Es el "o exclusivo" de los conjuntos.

> [!note] Definición
> $$A\triangle B=(A\cup B)\setminus(A\cap B)=(A\setminus B)\cup(B\setminus A)$$
> Con predicados: $A\triangle B=\{x\mid(P_x\land\neg Q_x)\lor(\neg P_x\land Q_x)\}$, es decir, $P_x\oplus Q_x$ ([[Disyunción|disyunción excluyente]]).

> [!important] Propiedades
> - Conmutativa y **asociativa**: $A\triangle(B\triangle C)=(A\triangle B)\triangle C$.
> - $A\triangle\emptyset=A$ y $A\triangle A=\emptyset$ (cada conjunto es su propio "opuesto").
> - $A\cap(B\triangle C)=(A\cap B)\triangle(A\cap C)$.
> - $A\setminus B=A\triangle(A\cap B)$.
>
> Por todo esto, $(\mathcal P(U),\triangle,\cap)$ es un **[[Anillo|anillo]] conmutativo**: un buen ejemplo para el cap. 4.

> [!example] Ejemplo
> $A=\{1,2,3\}$, $B=\{2,3,4\}$: $A\triangle B=\{1,4\}$.

## Conexiones
- **Necesitas antes:** [[Diferencia y complementario]], [[Disyunción]]
- **Aparece en:** [[Grupo]] y [[Anillo]] como ejemplo ($(\mathcal P(U),\triangle)$ es un grupo abeliano)
- **Practica:** [[LM Ejercicios Cap 2#Ejercicio 8 · Igualdades de conjuntos]]
