---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2 · p. 10"
aliases: [Implicación lógica, Equivalencia lógica, ⇒, ⇔, Implica, Es equivalente a]
---
# Implicación y equivalencia lógica  ($\Rightarrow$ y $\Leftrightarrow$)

> [!tip] En palabras sencillas
> - $p\to q$ es **una frase** que puede ser verdadera o falsa.
> - $p\Rightarrow q$ es **afirmar** que esa frase es verdadera: "*$p$ implica $q$*".
>
> Igual con $\leftrightarrow$ (frase) y $\Leftrightarrow$ (afirmación de que es verdadera).

> [!note] Definición (convenio del libro)
> - $p\Rightarrow q$ ("$p$ **implica** $q$") significa: la proposición $p\to q$ es verdadera.
> - $p\Leftrightarrow q$ ("$p$ **es equivalente a** $q$", "$p$ sii $q$", "$p$ iff $q$") significa: $p\leftrightarrow q$ es verdadera.
> - Cuando se habla de **leyes** (tautologías), $p\Rightarrow q$ significa que $p\to q$ es una tautología.

> [!important] Cómo se usan
> - Si sabes $p\Rightarrow q$: basta comprobar que $p$ es verdad para concluir $q$ ([[Modus ponens]]), o que $q$ es falsa para concluir que $p$ es falsa ([[Modus tollens]]).
> - Si sabes $p\Leftrightarrow q$: si una es verdadera (o falsa), la otra también.

> [!example] Ejemplo
> "$f$ derivable en $\mathbb R$ $\Rightarrow$ $f$ continua en $\mathbb R$". Es un teorema: el condicional es siempre verdadero, por eso escribimos $\Rightarrow$.

> [!warning] Errores típicos
> - Usar $\Rightarrow$ como abreviatura de "entonces" entre pasos que **no** son implicaciones verdaderas.
> - Encadenar $\Leftrightarrow$ en una demostración cuando algún paso solo va en un sentido (por ejemplo, elevar al cuadrado: $x=2\Rightarrow x^2=4$, pero $x^2=4\not\Rightarrow x=2$).

## Conexiones
- **Necesitas antes:** [[Condicional]], [[Bicondicional]], [[Tautología y contradicción]]
- **Lleva a:** [[Condición necesaria y condición suficiente]], [[Modus ponens]], [[Modus tollens]], [[Métodos de demostración]]
