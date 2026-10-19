---
tipo: teorema
tags: [teorema, logica, inferencia]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · p. 20"
aliases: [Modus ponendo ponens, Regla de separación]
---
# Modus ponens

> [!tip] En palabras sencillas
> "Si llueve, el suelo se moja. Llueve. **Luego** el suelo se moja." Es la forma más básica de razonar: aplicar una regla a un caso.

> [!important] Enunciado
> $$(p\to q)\land p\ \Rightarrow\ q$$
> Si el condicional es verdadero y el antecedente es verdadero, el consecuente es verdadero.

> [!abstract] Demostración (idea)
> En la tabla de $p\to q$, la única fila con $p=1$ y $p\to q=1$ es la fila $p=1,q=1$. Luego $q=1$.

> [!example] Ejemplos
> - Teorema: "toda función continua en $[a,b]$ alcanza un máximo". $f(x)=x^2$ es continua en $[0,1]$. **Luego** alcanza un máximo en $[0,1]$.
> - Es exactamente lo que haces cada vez que **aplicas un teorema**: compruebas las hipótesis ($p$) y obtienes la tesis ($q$).

> [!warning] Error típico: la falacia de afirmar el consecuente
> $(p\to q)\land q\ \not\Rightarrow\ p$. "Si llueve, el suelo se moja. El suelo está mojado. Luego llueve" ✗ (pueden haber regado).

## Conexiones
- **Necesitas antes:** [[Condicional]], [[Implicación y equivalencia lógica]]
- **Se usa en:** [[Demostración directa]], [[Silogismo hipotético]], [[Validación por refutación]]
- **Hermano:** [[Modus tollens]]
