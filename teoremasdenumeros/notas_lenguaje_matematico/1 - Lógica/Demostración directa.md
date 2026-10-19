---
tipo: método
tags: [metodo, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "Comentarios cap. 1 · p. 30"
aliases: [Deducción directa, Prueba directa]
---
# Demostración directa

> [!tip] En palabras sencillas
> Partes de la hipótesis $H$ y, paso a paso, llegas a la conclusión $C$. Cada paso es una implicación verdadera ya conocida.

> [!note] Esquema
> $$H\Rightarrow R_1\Rightarrow R_2\Rightarrow\cdots\Rightarrow C$$
> Se justifica con el [[Silogismo hipotético]]: $(H\to R)\land(R\to C)\Rightarrow(H\to C)$. Cada flecha suele ser una aplicación de un teorema ([[Modus ponens]]).

> [!example] Ejemplo: "si $a$ y $b$ son pares, $a+b$ es par"
> 1. $a$ par ⇒ $a=2k$ para algún entero $k$ (definición de par).
> 2. $b$ par ⇒ $b=2m$.
> 3. $a+b=2k+2m=2(k+m)$.
> 4. $k+m$ es entero ⇒ $a+b$ es par. ∎

> [!warning] Errores típicos
> - Usar la misma letra para dos cosas distintas: $a=2k$ y $b=2k$ (estarías diciendo que $a=b$).
> - Partir de la conclusión y llegar a algo verdadero: eso **no** demuestra nada (salvo que todos los pasos sean $\Leftrightarrow$).

## Conexiones
- **Necesitas antes:** [[Silogismo hipotético]], [[Modus ponens]]
- **Otros métodos:** [[Métodos de demostración]]
