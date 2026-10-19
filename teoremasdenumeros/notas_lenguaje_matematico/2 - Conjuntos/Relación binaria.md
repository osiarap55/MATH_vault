---
tipo: definición
tags: [definicion, conjuntos, relaciones]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.5 · pp. 59-65"
aliases: [Relación, Relaciones, Correspondencia, Relación entre conjuntos, Relación inversa, Composición de relaciones, Grafo de una relación, Conjunto original, Conjunto imagen de una relación]
---
# Relación binaria (correspondencia)

> [!tip] En palabras sencillas
> Una relación entre $A$ y $B$ dice **qué elementos de $A$ están "conectados" con cuáles de $B$**. Formalmente es simplemente **el conjunto de parejas conectadas**. Se dibuja con flechas o como puntos en una cuadrícula.

> [!note] Definición
> Una **relación** (o correspondencia) de $A$ a $B$ es cualquier subconjunto $\mathcal R\subseteq A\times B$. Se escribe $\mathcal R:A\to B$.
> - $x\,\mathcal R\,y$ significa $(x,y)\in\mathcal R$.
> - $A$ es el **conjunto inicial** y $B$ el **final**. Si $A=B$, es una **relación en $A$**.
> - Equivale a un predicado de dos variables $R_{xy}$: $\mathcal R=\{(x,y)\mid R_{xy}\}$ es su **grafo**.

> [!note] Conceptos asociados
> - **Relación inversa:** $\mathcal R^{-1}=\{(y,x)\in B\times A\mid(x,y)\in\mathcal R\}$ (dar la vuelta a las flechas).
> - **Imagen de $x$:** $\mathcal R(x)=\{y\in B\mid x\,\mathcal R\,y\}$. **Original de $y$:** $\mathcal R^{-1}(y)=\{x\in A\mid x\,\mathcal R\,y\}$.
> - **Conjunto imagen:** $\mathcal R(A)=\{y\mid\exists x,\ x\,\mathcal R\,y\}$. **Conjunto original:** $\mathcal R^{-1}(B)=\{x\mid\exists y,\ x\,\mathcal R\,y\}$.
> - **Composición:** si $\mathcal R\subseteq A\times B$ y $\mathcal S\subseteq B\times C$,
> $$\mathcal S\circ\mathcal R=\{(x,z)\in A\times C\mid\exists y\in B:\ x\,\mathcal R\,y\ \text{y}\ y\,\mathcal S\,z\}$$
> (primero $\mathcal R$, luego $\mathcal S$: "se puede ir de $x$ a $z$ pasando por algún $y$").

> [!example] Ejemplos
> - En $A=\{1,2,3\}$, "$x<y$": $\mathcal R=\{(1,2),(1,3),(2,3)\}$, $\mathcal R^{-1}=\{(2,1),(3,1),(3,2)\}$ (que es "$x>y$").
> - $\mathcal R=\{(x,y)\in\mathbb R^2\mid x=y^2\}$ (parábola tumbada): $\mathcal R(x)=\emptyset$ si $x<0$, $\mathcal R(0)=\{0\}$, $\mathcal R(x)=\{-\sqrt x,\sqrt x\}$ si $x>0$. **No es una función** (a un $x$ le corresponden dos $y$).
> - La circunferencia $x^2+y^2=1$ es una relación en $\mathbb R$.
> - $\subseteq$ es una relación en $\mathcal P(U)$; $\in$ es una relación entre $A$ y $\mathcal P(A)$.

> [!warning] Errores típicos
> - Confundir relación con función: en una relación un elemento puede tener **0, 1 o muchas** imágenes. Una [[Aplicación]] exige **exactamente una**.
> - El orden de la composición: $\mathcal S\circ\mathcal R$ se lee "**$\mathcal S$ después de $\mathcal R$**".
> - El conjunto de todas las relaciones de $A$ a $B$ es $\mathcal P(A\times B)$.

## Conexiones
- **Necesitas antes:** [[Producto cartesiano]], [[Predicado]]
- **Lleva a:** [[Propiedades de una relación]], [[Relación de equivalencia]], [[Relación de orden]], [[Aplicación]], [[Composición de aplicaciones]]
- **Practica:** [[LM Ejercicios Cap 2#Ejercicio 11 · Relaciones y composición]]
