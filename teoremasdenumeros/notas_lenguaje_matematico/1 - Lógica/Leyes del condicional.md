---
tipo: teorema
tags: [teorema, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · p. 17"
aliases: [Ley del condicional, Primera ley del condicional, Leyes de expansión del condicional, Ley de exportación]
---
# Leyes del condicional

> [!tip] En palabras sencillas
> "Si $p$ entonces $q$" es lo mismo que "**o no se da $p$, o se da $q$**". Y también lo mismo que "**no puede ser que se dé $p$ y no se dé $q$**".

> [!important] Enunciado
> 1. $p\to q\iff\neg p\lor q$ ← **la más usada**
> 2. $p\to q\iff\neg(p\land\neg q)$
> 3. $p\to q\iff p\leftrightarrow(p\land q)$ (expansión)
> 4. $p\to q\iff q\leftrightarrow(p\lor q)$ (expansión)
>
> Relacionadas: $p\to q\iff\neg q\to\neg p$ ([[Recíproco y contrarrecíproco|transposición]]) y $(p\land q)\to r\iff p\to(q\to r)$ (**exportación**).

> [!abstract] Demostración (idea y pasos)
> **Ley 1:** compara tablas. $p\to q$ solo vale 0 en la fila $(1,0)$; $\neg p\lor q$ también solo vale 0 ahí (porque $\neg p=0$ y $q=0$).
> **Ley 2:** aplica [[Leyes de De Morgan|De Morgan]] a la ley 1: $\neg(p\land\neg q)\iff\neg p\lor\neg\neg q\iff\neg p\lor q$.
> **Exportación:** $p\to(q\to r)\iff\neg p\lor(\neg q\lor r)\iff(\neg p\lor\neg q)\lor r\iff\neg(p\land q)\lor r\iff(p\land q)\to r$.

> [!example] Ejemplos
> - "Si $n$ es múltiplo de 4, $n$ es par" ⇔ "$n$ no es múltiplo de 4 **o** $n$ es par".
> - Negar un condicional: $\neg(p\to q)\iff p\land\neg q$. "No es cierto que si estudias apruebas" = "estudias **y** no apruebas".

> [!warning] Errores típicos
> - Creer que la negación de $p\to q$ es $\neg p\to\neg q$ o $p\to\neg q$. **Es $p\land\neg q$**: un contraejemplo (la hipótesis se cumple y la conclusión no).

## Conexiones
- **Necesitas antes:** [[Condicional]], [[Leyes de De Morgan]]
- **Se usa en:** [[Forma clausulada]] (paso 2), [[Recíproco y contrarrecíproco]], [[Validación por refutación]]
- **En conjuntos:** $A\subseteq B$ significa $x\in A\to x\in B$ ([[Inclusión de conjuntos]])
