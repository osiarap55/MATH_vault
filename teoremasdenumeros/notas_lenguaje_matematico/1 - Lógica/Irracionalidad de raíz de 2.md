---
tipo: teorema
tags: [teorema, logica, numeros]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "Ejemplo 1.9 · p. 17; §6.3"
aliases: [Raíz de 2 es irracional, √2 es irracional, √2 no es racional]
---
# $\sqrt 2$ es irracional

> [!important] Teorema
> No existe ningún número racional $a/b$ tal que $(a/b)^2=2$.

> [!tip] En palabras sencillas
> Si $\sqrt2$ fuera una fracción, podrías simplificarla hasta el final… y aun así numerador y denominador seguirían siendo pares. Imposible.

> [!abstract] Demostración (idea y pasos) · [[Reducción al absurdo]]
> 1. Supón que $\sqrt 2=\dfrac ab$ con la fracción **irreducible** ($\operatorname{mcd}(a,b)=1$).
> 2. Elevando al cuadrado: $a^2=2b^2$, luego $a^2$ es par.
> 3. Si $a^2$ es par, $a$ es par ([[Demostración por contrarrecíproco|por contrarrecíproco]]): $a=2k$.
> 4. Sustituyendo: $4k^2=2b^2\Rightarrow b^2=2k^2$, luego $b$ también es par.
> 5. Entonces 2 divide a $a$ y a $b$: $\operatorname{mcd}(a,b)\ge 2$. **Contradicción** con el paso 1. ∎

> [!warning] Detalles que se suelen olvidar
> - Hay que justificar que **toda** fracción se puede escribir irreducible (dividiendo por el [[Máximo común divisor]]).
> - El paso "$a^2$ par ⇒ $a$ par" **necesita demostración**: no es lo mismo que "$a$ par ⇒ $a^2$ par".

> [!example] Generalización
> El mismo argumento prueba que $\sqrt p$ es irracional para todo primo $p$ (usando que si $p\mid a^2$ entonces $p\mid a$, ver [[Números primos]]).

## Conexiones
- **Usa:** [[Reducción al absurdo]], [[Demostración por contrarrecíproco]], [[Máximo común divisor]]
- **Consecuencia:** $\mathbb Q$ "tiene agujeros" → [[Insuficiencia de los racionales]] → [[Axioma del supremo]] → [[Números reales]]
