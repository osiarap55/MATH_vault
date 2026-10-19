---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2 · p. 11; §1.4 · p. 18"
aliases: [Recíproco, Contrarrecíproco, Contrario, Condicional recíproco, Condicional contrarrecíproco, Ley de transposición, Leyes de transposición]
---
# Recíproco, contrario y contrarrecíproco

> [!tip] En palabras sencillas
> A partir de "si $p$ entonces $q$" se pueden fabricar otros tres condicionales dando la vuelta y/o negando. **Solo uno de ellos dice lo mismo que el original: el contrarrecíproco.**

> [!note] Definición
> Dado el [[Condicional]] $p\to q$:
> | Nombre | Forma | ¿Equivale a $p\to q$? |
> |---|---|:-:|
> | Recíproco | $q\to p$ | ✗ |
> | Contrario | $\neg p\to\neg q$ | ✗ |
> | **Contrarrecíproco** | $\neg q\to\neg p$ | ✓ |
>
> (El recíproco y el contrario sí son equivalentes **entre sí**: uno es el contrarrecíproco del otro.)

> [!important] Ley de transposición
> $$p\to q \iff \neg q\to\neg p \qquad\qquad p\leftrightarrow q\iff \neg p\leftrightarrow\neg q$$

> [!abstract] Por qué es cierta (idea)
> $p\to q \iff \neg p\lor q$ ([[Leyes del condicional]]). Y $\neg q\to\neg p \iff \neg\neg q\lor\neg p \iff q\lor\neg p$. Por la conmutatividad de $\lor$, son la misma cosa.

> [!example] Ejemplo
> Original: "Si $f$ es derivable en $a$, entonces es continua en $a$" ✓ verdadero.
> - Contrarrecíproco: "Si $f$ **no** es continua en $a$, **no** es derivable en $a$" ✓ verdadero (dice lo mismo).
> - Recíproco: "Si $f$ es continua en $a$, es derivable en $a$" ✗ falso: $f(x)=|x|$ en $a=0$.

> [!warning] Errores típicos
> - **El error más común en matemáticas:** usar el recíproco como si fuera el teorema. "Si $n$ es múltiplo de 4, es par" no permite deducir "si $n$ es par, es múltiplo de 4" (falla en $n=6$).
> - Pensar que "contrario" y "contrarrecíproco" son lo mismo.

## Conexiones
- **Necesitas antes:** [[Condicional]], [[Leyes del condicional]]
- **Lleva a:** [[Demostración por contrarrecíproco]], [[Modus tollens]]
- **Se usa en:** [[Unicidad del límite de una sucesión]], [[Aplicación inyectiva]] (la definición se suele usar en forma contrarrecíproca)
