---
tipo: teorema
tags: [teorema, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · p. 16"
aliases: [De Morgan, Ley de De Morgan, Leyes de Morgan]
---
# Leyes de De Morgan

> [!tip] En palabras sencillas
> Para negar un "y" o un "o": **niega cada parte y cambia el conector**.
> - "No (llueve **y** hace frío)" = "no llueve **o** no hace frío".
> - "No (llueve **o** hace frío)" = "no llueve **y** no hace frío".

> [!important] Enunciado
> $$\neg(p\lor q)\iff\neg p\land\neg q \qquad\qquad \neg(p\land q)\iff\neg p\lor\neg q$$

> [!abstract] Demostración (idea y pasos)
> **Idea:** $p\lor q$ solo es falsa cuando las dos son falsas, que es exactamente lo que dice $\neg p\land\neg q$.
> 1. Haz la [[Tabla de verdad]] de $\neg(p\lor q)$: vale 1 solo en la fila $p=0,q=0$.
> 2. Haz la de $\neg p\land\neg q$: vale 1 solo en la misma fila.
> 3. Columnas iguales ⇒ equivalentes. La segunda ley igual (o aplicando la primera a $\neg p,\neg q$ y la doble negación).

> [!example] Ejemplos
> - $\neg[(p\land q)\lor r]\iff\neg(p\land q)\land\neg r\iff(\neg p\lor\neg q)\land\neg r$.
> - "No es cierto que $x\ge 0$ y $y\ge 0$" ⇔ "$x<0$ **o** $y<0$".
> - Con cuantificadores, De Morgan se generaliza: $\neg\forall x\,P(x)\iff\exists x\,\neg P(x)$ ([[Cuantificadores]]).

> [!warning] Errores típicos
> - Negar las partes **sin** cambiar el conector: $\neg(p\land q)\neq\neg p\land\neg q$.
> - Cambiar el conector **sin** negar las partes.

## Conexiones
- **Necesitas antes:** [[Negación]], [[Conjunción]], [[Disyunción]]
- **Se usa en:** [[Forma clausulada]] (paso 3), [[Cuantificadores]] (negar $\forall$/$\exists$), [[Álgebra de conjuntos]] ($(A\cup B)^c=A^c\cap B^c$)
- **Practica:** [[LM Ejercicios Cap 1#Ejercicio 1 · Negar con De Morgan]]
