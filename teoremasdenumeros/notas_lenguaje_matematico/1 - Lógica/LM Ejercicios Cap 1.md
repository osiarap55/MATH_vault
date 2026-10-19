---
tipo: ejercicios
tags: [ejercicios, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "Ejercicios propuestos · pp. 31-32"
---
# Ejercicios · Cap 1 · Nociones de lógica

> [!tip] Cómo usar esta nota
> Intenta cada ejercicio en papel **antes** de abrir la solución (haz clic en "Solución" para desplegarla). Si te atascas, abre la nota enlazada en "Repasa".

## Ejercicio 1 · Negar con De Morgan
> [!question] Enunciado
> Escribe la negación de cada proposición y simplifícala con De Morgan:
> a) $(p\land q)\lor r$  b) $(p\lor q)\land r$  c) $(p\lor q)\land(p\lor r)$

> [!success]- Solución
> a) $\neg[(p\land q)\lor r]\iff\neg(p\land q)\land\neg r\iff(\neg p\lor\neg q)\land\neg r$
> b) $\neg[(p\lor q)\land r]\iff\neg(p\lor q)\lor\neg r\iff(\neg p\land\neg q)\lor\neg r$
> c) $\neg[(p\lor q)\land(p\lor r)]\iff(\neg p\land\neg q)\lor(\neg p\land\neg r)\iff\neg p\land(\neg q\lor\neg r)$ (sacando factor común $\neg p$ con la distributiva).

Repasa: [[Leyes de De Morgan]]

## Ejercicio 2 · Simplificar
> [!question] Enunciado
> Simplifica: a) $(p\lor\neg q)\land\neg p$  b) $(\neg p\lor\neg q)\land(p\lor q)$  c) $(\neg p\land q)\lor(\neg p\land\neg r)\lor(p\land q)$

> [!success]- Solución
> a) Distributiva: $(p\land\neg p)\lor(\neg q\land\neg p)\iff\mathbf 0\lor(\neg p\land\neg q)\iff\neg p\land\neg q$.
> b) Distributiva: $[(\neg p\lor\neg q)\land p]\lor[(\neg p\lor\neg q)\land q]\iff(p\land\neg q)\lor(\neg p\land q)$, que es la **disyunción excluyente** $p\oplus q$.
> c) Agrupa el primero y el último: $(\neg p\land q)\lor(p\land q)\iff(\neg p\lor p)\land q\iff q$. Queda $q\lor(\neg p\land\neg r)$, o en forma clausulada $(q\lor\neg p)\land(q\lor\neg r)$.

Repasa: [[Leyes lógicas]], [[Disyunción]]

## Ejercicio 3 · Evaluar
> [!question] Enunciado
> Con $p=1$, $q=1$, $r=0$, calcula el valor de $(p\land r)\to q$ y de $\neg(p\land\neg q\land r)$. ¿Son equivalentes en general?

> [!success]- Solución
> - $p\land r=1\land 0=0$, y un condicional con antecedente falso vale **1**.
> - $p\land\neg q\land r=1\land 0\land 0=0$, luego $\neg(\cdots)=$ **1**.
> - **Sí son equivalentes siempre:** $(p\land r)\to q\iff\neg p\lor\neg r\lor q$ y $\neg(p\land\neg q\land r)\iff\neg p\lor q\lor\neg r$ (De Morgan). Son la misma cláusula.

Repasa: [[Condicional]], [[Leyes del condicional]]

## Ejercicio 4 · Tablas de verdad
> [!question] Enunciado
> Haz la tabla de verdad de $(r\to q)\lor r$.

> [!success]- Solución
> | $q$ | $r$ | $r\to q$ | $(r\to q)\lor r$ |
> |:-:|:-:|:-:|:-:|
> | 0 | 0 | 1 | 1 |
> | 0 | 1 | 0 | 1 |
> | 1 | 0 | 1 | 1 |
> | 1 | 1 | 1 | 1 |
>
> Es una **tautología**. Sin tabla: $(\neg r\lor q)\lor r\iff(\neg r\lor r)\lor q\iff\mathbf 1$.

Repasa: [[Tabla de verdad]], [[Tautología y contradicción]]

## Ejercicio 5 · Pasar a símbolos
> [!question] Enunciado
> "Si salto en vertical, entonces caigo en el mismo sitio. He saltado y no he caído en el mismo sitio. Luego no he saltado en vertical."

> [!success]- Solución
> $p$: "salto en vertical"; $q$: "caigo en el mismo sitio"; $s$: "he saltado".
> $$[(p\to q)\land s\land\neg q]\to\neg p$$
> Es un razonamiento correcto: es [[Modus tollens]] ($(p\to q)\land\neg q\Rightarrow\neg p$); el dato $s$ no hace falta.

Repasa: [[Proposición]], [[Modus tollens]]

## Ejercicio 6 · Ley de exportación
> [!question] Enunciado
> Demuestra que $(p\land q)\to r\iff p\to(q\to r)$.

> [!success]- Solución
> Con leyes (más rápido que la tabla de 8 filas):
> $p\to(q\to r)\iff\neg p\lor(\neg q\lor r)\iff(\neg p\lor\neg q)\lor r\iff\neg(p\land q)\lor r\iff(p\land q)\to r$.
> Pasos: ley del condicional (×2), asociativa, De Morgan, ley del condicional.

Repasa: [[Leyes del condicional]]

## Ejercicio 7 · Dilema constructivo por refutación
> [!question] Enunciado
> Valida por refutación: $(p\to r)\land(q\to r)\land(p\lor q)\Rightarrow r$.

> [!success]- Solución
> 1. Supón que el condicional es falso: el antecedente vale 1 y $r=0$.
> 2. Entonces $p\to r=1$, $q\to r=1$, $p\lor q=1$.
> 3. $p\to r=1$ y $r=0$ ⇒ $p=0$ ([[Modus tollens]]). Igual, $q=0$.
> 4. Entonces $p\lor q=0$, pero en el paso 2 era 1. **Contradicción** → es tautología.
>
> Interpretación: "Si llueve me quedo en casa; si nieva me quedo en casa; llueve o nieva. Luego me quedo en casa."

Repasa: [[Validación por refutación]]

## Ejercicio 8 · Forma clausulada
> [!question] Enunciado
> Halla la forma clausulada de: a) $(p\to q)\lor\neg q$  b) $\neg p\land(r\to\neg q)$  c) $[(p\to q)\lor p]\to\neg(q\land p)$

> [!success]- Solución
> a) $(\neg p\lor q)\lor\neg q\iff\neg p\lor(q\lor\neg q)\iff\mathbf 1$. **Tautología.**
> b) $\neg p\land(\neg r\lor\neg q)$: dos cláusulas, $\neg p$ y $\neg q\lor\neg r$.
> c) El antecedente: $(\neg p\lor q)\lor p\iff\mathbf 1$. Queda $\mathbf 1\to\neg(q\land p)\iff\neg(p\land q)\iff\neg p\lor\neg q$. Una cláusula.

Repasa: [[Forma clausulada]]

## Ejercicio 9 · ¿Equivalentes?
> [!question] Enunciado
> a) ¿$(\neg p\lor\neg q)\land\neg p$ equivale a $(\neg p\land\neg q)\lor\neg p$?
> b) ¿$p\to(p\land q)$ equivale a $\neg p\lor q$?

> [!success]- Solución
> a) **Sí**: ambas valen $\neg p$ por la ley de **absorción** ($a\land(a\lor b)\iff a$ y $a\lor(a\land b)\iff a$, con $a=\neg p$).
> b) **Sí**: está hecho en la nota [[Forma clausulada]] (ejemplo).

## Ejercicio 10 · Fabricar proposiciones con una tabla dada
> [!question] Enunciado
> Filas ordenadas como en el libro ($00, 01, 10, 11$ o $000,\dots,111$). Da dos proposiciones distintas con tabla:
> a) $1100$  c) $10101010$  d) $0110$

> [!success]- Solución
> a) Vale 1 cuando $p=0$: $\neg p$, y también $p\to\neg p$.
> c) Tres variables; vale 1 exactamente cuando $r=0$: $\neg r$, y también $\neg r\lor(p\land\neg p)$.
> d) Vale 1 cuando $p\neq q$: $(p\land\neg q)\lor(\neg p\land q)$ y $\neg(p\leftrightarrow q)$ (disyunción excluyente).

## Ejercicio 11 · Elige la equivalente
> [!question] Enunciado
> ¿Cuál equivale a $(p\lor r)\land(p\lor q)$? a) $p\land(q\lor r)$ b) $(p\to\neg r)\land(p\to\neg q)$ c) $p\lor(q\land r)$

> [!success]- Solución
> **c)**, por la ley distributiva $p\lor(q\land r)\iff(p\lor q)\land(p\lor r)$.
> a) falla con $p=0,q=r=1$ (la original vale 1, a) vale 0).
> b) falla con $p=q=r=1$ (la original vale 1, b) vale 0).
> Para descartar basta **un contraejemplo** (una fila).

Repasa: [[Leyes lógicas]]
