---
tipo: método
tags: [metodo, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · p. 18; Comentarios · p. 30"
aliases: [Negación del consecuente, Prueba por contraposición, Contraposición]
---
# Demostración por contrarrecíproco

> [!tip] En palabras sencillas
> En vez de probar "si $H$ entonces $C$", pruebas "**si no $C$, entonces no $H$**". Dice exactamente lo mismo y a veces es mucho más fácil.

> [!note] Esquema
> Para probar $H\Rightarrow C$: supón $\neg C$ y deduce $\neg H$.
> Justificación: [[Recíproco y contrarrecíproco|ley de transposición]] $H\to C\iff\neg C\to\neg H$.

> [!example] Ejemplo: "si $n^2$ es par, entonces $n$ es par"
> Directamente es incómodo (¿cómo saco $n$ de $n^2$?). Por contrarrecíproco: "si $n$ es **impar**, $n^2$ es **impar**".
> 1. $n$ impar ⇒ $n=2k+1$.
> 2. $n^2=4k^2+4k+1=2(2k^2+2k)+1$.
> 3. Luego $n^2$ es impar. ∎
>
> Este resultado se usa en [[Irracionalidad de raíz de 2]].

> [!warning] Errores típicos
> - Probar $\neg H\Rightarrow\neg C$ (el **contrario**), que **no** equivale al enunciado.
> - Negar mal la conclusión. La negación de "$x>0$" es "$x\le 0$".

## Conexiones
- **Necesitas antes:** [[Recíproco y contrarrecíproco]], [[Modus tollens]]
- **Otros métodos:** [[Métodos de demostración]], [[Reducción al absurdo]]
- **Se usa en:** [[Irracionalidad de raíz de 2]], [[Aplicación inyectiva]] (probar inyectividad)
