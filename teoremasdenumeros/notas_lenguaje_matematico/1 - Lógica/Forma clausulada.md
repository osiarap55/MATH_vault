---
tipo: método
tags: [metodo, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.6 · pp. 23-27"
aliases: [Forma normal conjuntiva, FNC, Cláusula, Cláusulas]
---
# Forma clausulada (forma normal conjuntiva)

> [!tip] En palabras sencillas
> Es reescribir cualquier fórmula como **un "y" de varios "o"**: $(\ldots\lor\ldots)\land(\ldots\lor\ldots)\land\cdots$, donde dentro de cada paréntesis solo hay letras o letras negadas. Cada paréntesis es una **cláusula**. Así es facilísimo ver si es tautología: **cada cláusula debe contener alguna letra y su negación**.

> [!note] Definición
> Una **cláusula** es una disyunción de proposiciones simples o negadas ($p\lor\neg q\lor r$). La **forma clausulada** de una proposición es una conjunción de cláusulas equivalente a ella.
> Ejemplo: $(p\lor\neg q)\land(q\lor r)\land(p\lor\neg r)$.

> [!abstract] Los 4 pasos
> 1. **Quitar $\leftrightarrow$:** $p\leftrightarrow q\ \leadsto\ (p\to q)\land(q\to p)$.
> 2. **Quitar $\to$:** $p\to q\ \leadsto\ \neg p\lor q$ ([[Leyes del condicional]]).
> 3. **Meter las negaciones** hasta las letras: [[Leyes de De Morgan]] y doble negación.
> 4. **Distribuir** $\lor$ sobre $\land$ ([[Leyes lógicas|distributivas]]), y usar asociativas/conmutativas para ordenar.
>
> Luego simplifica: $p\lor\neg p\lor\dots=\mathbf 1$ ([[Tercio excluso y no contradicción|tercio excluso]]), y $\mathbf 1\land A=A$.

> [!example] Ejemplo: $p\to(p\land q)$
> 1. $\neg p\lor(p\land q)$
> 2. Distribuir: $(\neg p\lor p)\land(\neg p\lor q)$
> 3. Tercio excluso: $\mathbf 1\land(\neg p\lor q)=\neg p\lor q$.
>
> Forma clausulada: $\neg p\lor q$, la misma que $p\to q$. **Luego $p\to(p\land q)\iff p\to q$.**

> [!important] Propiedades útiles
> - Dos proposiciones con la **misma** forma clausulada son **equivalentes**.
> - Es **tautología** ⇔ todas sus cláusulas contienen una letra y su negación.
> - Para la tabla de verdad, la forma clausulada suele ser más fácil de evaluar.

> [!warning] Errores típicos
> - Distribuir antes de quitar las negaciones de fuera.
> - Confundir con la forma normal **disyuntiva** (un "o" de "y"s).

## Conexiones
- **Necesitas antes:** [[Leyes del condicional]], [[Leyes de De Morgan]], [[Leyes lógicas]]
- **Alternativas:** [[Tabla de verdad]], [[Validación por refutación]]
- **Practica:** [[LM Ejercicios Cap 1#Ejercicio 8 · Forma clausulada]]
