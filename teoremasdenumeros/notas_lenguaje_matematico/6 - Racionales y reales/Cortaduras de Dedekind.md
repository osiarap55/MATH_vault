---
tipo: definición
tags: [definicion, reales, fundamentos]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Comentarios cap. 6 · pp. 231-235; Def. 6.23, Ejercicio 6.24"
aliases: [Cortadura, Cortaduras, Dedekind, Construcción de R, Construcción de los reales, Sucesiones de Cauchy]
---
# Cortaduras de Dedekind (construcción de $\mathbb R$)

> [!tip] En palabras sencillas
> Cada real "corta" la recta de los racionales en dos trozos: los de su izquierda y los de su derecha. **Dedekind invierte la idea: define un real como ese corte.** Así $\sqrt2$ "es" el conjunto de racionales positivos cuyo cuadrado es mayor que 2.

> [!note] Definición 6.23
> Una **cortadura de Dedekind** es un $B\subseteq\mathbb Q$ tal que:
> 1. $B\neq\emptyset$ y $\mathbb Q\setminus B\neq\emptyset$;
> 2. si $b\in B$ y $c>b$ ($c\in\mathbb Q$), entonces $c\in B$ (es "un trozo derecho");
> 3. $B$ **no tiene mínimo**.
>
> **Por definición, un número real es una cortadura**, y $\mathbb R$ es el conjunto de todas ellas.

> [!example] Ejemplos
> - **Cortadura racional** de $\beta\in\mathbb Q$: $i(\beta)=(\beta,+\infty)_{\mathbb Q}=\{x\in\mathbb Q\mid x>\beta\}$.
> - **$\sqrt2$:** $B'=\{x\in\mathbb Q\mid x>0,\ x^2>2\}$. Es cortadura (no tiene mínimo por la [[Insuficiencia de los racionales|construcción $s=\frac{2r+2}{r+2}$]]) y **no** es racional.

> [!abstract] Cómo se construye la estructura
> | Qué | Definición |
> |---|---|
> | Orden | $B\le B'\iff B'\subseteq B$ (al revés, porque son trozos derechos) |
> | **Supremo** (Ej. 6.24) | $\sup\mathcal C=\bigcap_{B\in\mathcal C}B$ ← aquí está el axioma del supremo |
> | Suma | $B+B'=\{\beta+\beta'\mid\beta\in B,\beta'\in B'\}$; neutro $i(0)$ |
> | Producto | si $B,B'\ge0$: $\{\beta\beta'\}$; el resto por casos de signo |
> | $\mathbb Q\hookrightarrow\mathbb R$ | $\beta\mapsto i(\beta)$, inyectiva, conserva suma, producto y orden |
>
> Resultado: un **cuerpo ordenado con el axioma del supremo**. Por la unicidad (Teorema 6.22) es "el" $\mathbb R$.

> [!note] La otra construcción: sucesiones de Cauchy
> Un real es una **clase de equivalencia** de sucesiones de Cauchy de racionales, donde dos sucesiones son equivalentes si su diferencia tiende a 0. (Es otro [[Conjunto cociente]].)

## Conexiones
- **Necesitas antes:** [[Números racionales]], [[Insuficiencia de los racionales]], [[Supremo e ínfimo]]
- **Demuestra la existencia de:** [[Números reales]] ([[Axioma del supremo]])
- **Patrón:** igual que $\mathbb Z$ y $\mathbb Q$, $\mathbb R$ se **construye** a partir del anterior
