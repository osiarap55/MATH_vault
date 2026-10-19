---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2 · p. 8"
aliases: [Si entonces, →, Antecedente, Consecuente]
---
# Condicional  $p\to q$

> [!tip] En palabras sencillas
> "Si $p$, entonces $q$" es una **promesa**: *si se cumple $p$, te garantizo $q$*. La promesa solo se rompe si se cumple $p$ y **no** se cumple $q$. Si $p$ no ocurre, la promesa no se ha roto (es verdadera "por defecto").

> [!note] Definición
> $p\to q$ es **falsa únicamente cuando $p$ es verdadera y $q$ es falsa**.
> $p$ es el **antecedente** (hipótesis) y $q$ el **consecuente** (conclusión).
>
> | $p$ | $q$ | $p\to q$ |
> |:-:|:-:|:-:|
> | 0 | 0 | 1 |
> | 0 | 1 | 1 |
> | 1 | 0 | **0** |
> | 1 | 1 | 1 |

> [!important] Las dos formas de reescribirlo que más se usan
> $$p\to q \iff \neg p\lor q \qquad\qquad p\to q\iff \neg q\to\neg p$$
> La primera es la base de la [[Forma clausulada]]; la segunda, de la [[Demostración por contrarrecíproco]]. Ver [[Leyes del condicional]].

> [!example] Ejemplos
> - "Si 8 es par, entonces 8 es suma de dos números iguales" → $1\to 1 = 1$.
> - "Si $f$ es derivable en $\mathbb R$, entonces $f$ es continua en $\mathbb R$" → verdadera (teorema de análisis).
> - "Si $2+2=5$, entonces yo soy el Papa" → **verdadera**, porque el antecedente es falso.

> [!warning] Errores típicos
> - **"De lo falso se deduce cualquier cosa"**: si el antecedente es falso, el condicional es verdadero. Choca con la intuición, pero es así.
> - El condicional **no** es causa-efecto: "si 2 es par, la Luna es un satélite" es verdadera aunque no haya relación.
> - $p\to q$ **no** es lo mismo que $q\to p$ (el recíproco). Ver [[Recíproco y contrarrecíproco]].
> - No confundas $\to$ (un conector, puede ser verdadero o falso) con $\Rightarrow$ (afirmar que $p\to q$ es verdadero). Ver [[Implicación y equivalencia lógica]].

## Conexiones
- **Necesitas antes:** [[Conectores lógicos]]
- **Lleva a:** [[Recíproco y contrarrecíproco]], [[Leyes del condicional]], [[Implicación y equivalencia lógica]], [[Modus ponens]], [[Modus tollens]]
- **Se usa en:** todas las demostraciones del tipo "si H entonces C" → [[Métodos de demostración]]
