---
tipo: teorema
tags: [teorema, logica, inferencia]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · p. 20"
aliases: [Modus tollendo tollens]
---
# Modus tollens

> [!tip] En palabras sencillas
> "Si llueve, el suelo se moja. El suelo **no** está mojado. **Luego** no llueve." Si la consecuencia no se da, la causa tampoco.

> [!important] Enunciado
> $$(p\to q)\land\neg q\ \Rightarrow\ \neg p$$

> [!abstract] Demostración (idea)
> Por [[Recíproco y contrarrecíproco|transposición]], $p\to q\iff\neg q\to\neg p$. Aplicando [[Modus ponens]] a $\neg q\to\neg p$ con $\neg q$ verdadera, sale $\neg p$.

> [!example] Ejemplos
> - Teorema: "si $f$ derivable tiene un máximo local en $x_0$, entonces $f'(x_0)=0$". Para $f(x)=-x^2$ en un punto con $f'(x_0)\neq 0$: **no** hay máximo local ahí.
> - Es el uso de una **condición necesaria** para descartar ([[Condición necesaria y condición suficiente]]).

> [!warning] Error típico: la falacia de negar el antecedente
> $(p\to q)\land\neg p\ \not\Rightarrow\ \neg q$. "Si llueve, el suelo se moja. No llueve. Luego el suelo no está mojado" ✗.

## Conexiones
- **Necesitas antes:** [[Condicional]], [[Recíproco y contrarrecíproco]]
- **Se usa en:** [[Demostración por contrarrecíproco]], [[Validación por refutación]]
- **Hermano:** [[Modus ponens]]
