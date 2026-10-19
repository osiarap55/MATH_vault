---
tipo: definición
tags: [definicion, conjuntos, logica]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.1 · pp. 41-44; §2.5 · pp. 64-65"
aliases: [Cuantificador, Cuantificador universal, Cuantificador existencial, Para todo, Existe, ∀, ∃, Negación de cuantificadores, Contraejemplo]
---
# Cuantificadores  $\forall$ y $\exists$

> [!tip] En palabras sencillas
> - $\forall x\,P(x)$: "**todos** cumplen $P$".
> - $\exists x\,P(x)$: "**al menos uno** cumple $P$".
>
> Convierten un [[Predicado]] (frase con hueco) en una [[Proposición]] (verdadera o falsa).

> [!note] Definición
> Sea $P$ un predicado sobre $C$ y $C_P=\{x\in C\mid P_x\}$.
> - **Universal:** $(\forall x\in C)\,P_x$ es verdadera si todo $x$ cumple $P$. Equivale a $C_P=C$.
> - **Existencial:** $(\exists x\in C)\,P_x$ es verdadera si algún $x$ cumple $P$. Equivale a $C_P\neq\emptyset$.
> - Si $C=\{1,2,3\}$: $\forall x\,P_x\iff P_1\land P_2\land P_3$ y $\exists x\,P_x\iff P_1\lor P_2\lor P_3$.
>   **$\forall$ es un "y" gigante; $\exists$ es un "o" gigante.**
> - La letra de la variable no importa: $\forall x\,P_x\iff\forall y\,P_y$.

> [!important] Negación de cuantificadores (De Morgan generalizado)
> $$\neg(\forall x\,P_x)\iff\exists x\,\neg P_x\qquad\qquad\neg(\exists x\,P_x)\iff\forall x\,\neg P_x$$
> **Regla práctica:** para negar, cambia cada $\forall$ por $\exists$ (y viceversa) y niega lo de dentro.
> $$\neg(\exists x\,\forall y\,P_{xy})\iff\forall x\,\exists y\,\neg P_{xy}$$

> [!important] Contraejemplo
> Para probar que $\forall x\,P_x$ es **falsa** basta encontrar **un** $x_0$ con $\neg P_{x_0}$.
> Ejemplo: "$\forall x\in\mathbb R,\ x\le x^2$" es falsa: $x_0=1/2$ da $x_0^2=1/4<1/2$.

> [!warning] El orden de los cuantificadores importa
> - $(\forall x\in\mathbb R)(\exists n\in\mathbb N)\ n>x$: "para cada real hay un natural mayor" ✓ ([[Propiedad arquimediana]]).
> - $(\exists n\in\mathbb N)(\forall x\in\mathbb R)\ n>x$: "hay un natural mayor que todos los reales" ✗.
>
> En $\forall x\,\exists y$, el $y$ **puede depender** de $x$. En $\exists y\,\forall x$, el mismo $y$ sirve para todos.
> Dos cuantificadores **iguales** sí se pueden intercambiar: $\forall x\forall y\iff\forall y\forall x$.

> [!example] Más ejemplos
> - $(\forall x\in\mathbb R)\ x^2-1=(x+1)(x-1)$ ✓ (identidad).
> - $(\exists x\in\mathbb R)\ x+5=3$ ✓ (ecuación con solución).
> - $(\forall x\in\mathbb R)\ ax+b=0\iff a=b=0$.
> - Definición de límite: $\forall\varepsilon>0\ \exists n_\varepsilon\ \forall n\ge n_\varepsilon:\ |x_n-r|<\varepsilon$ ([[Unicidad del límite de una sucesión]]).

> [!warning] Más errores típicos
> - Negar "$\forall x,\ x>0$" como "$\forall x,\ x\le 0$" ✗. Es "$\exists x,\ x\le 0$".
> - Creer que un ejemplo demuestra un $\forall$. **Solo** demuestra un $\exists$.
> - $\forall x\,(P_x\lor Q_x)$ **no** implica $\forall x\,P_x\lor\forall x\,Q_x$ (ver [[LM Ejercicios Cap 2#Ejercicio 2 · Cuantificadores y conectores]]).

## Conexiones
- **Necesitas antes:** [[Predicado]], [[Leyes de De Morgan]]
- **Se usa en:** todas las definiciones del libro: [[Aplicación inyectiva]], [[Aplicación sobreyectiva]], [[Supremo e ínfimo]], [[Unicidad del límite de una sucesión]], [[Propiedad arquimediana]]
- **Practica:** [[LM Ejercicios Cap 2#Ejercicio 5 · Negar con cuantificadores]]
