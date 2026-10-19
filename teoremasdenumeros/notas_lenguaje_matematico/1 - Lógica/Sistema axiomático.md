---
tipo: definición
tags: [definicion, logica, fundamentos]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "Comentarios cap. 1 · pp. 27-28"
aliases: [Axioma, Axiomas, Axiomática, Principia Mathematica, Sistema PM]
---
# Sistema axiomático

> [!tip] En palabras sencillas
> Las matemáticas funcionan como un juego con reglas: se aceptan unas pocas verdades de partida (**axiomas**) y unas reglas para deducir (**reglas de inferencia**). Todo lo que se deduzca así es un **teorema**.

> [!note] Ingredientes
> 1. **Alfabeto:** los símbolos ($p, q, \dots$).
> 2. **Reglas de formación:** cómo escribir fórmulas correctas (conectores y paréntesis).
> 3. **Axiomas:** fórmulas que se aceptan como verdaderas sin demostración.
> 4. **Reglas de transformación (deducción):** cómo pasar de fórmulas verdaderas a otras.
>
> Un **teorema** es una fórmula a la que se llega desde los axiomas con las reglas; la cadena de pasos es su **demostración**.

> [!example] El sistema PM (Whitehead y Russell, *Principia Mathematica*)
> Solo usa $\neg$ y $\lor$; el resto se define: $p\land q:=\neg(\neg p\lor\neg q)$, $p\to q:=\neg p\lor q$.
> Axiomas: (A1) $p\lor p\to p$; (A2) $q\to(p\lor q)$; (A3) $(p\lor q)\to(q\lor p)$; (A4) $(p\to q)\to[(r\lor p)\to(r\lor q)]$.
> Reglas: **sustitución** (cambiar una letra por una fórmula) y **separación** (= [[Modus ponens]]).

> [!important] Dónde volverás a ver axiomas en este libro
> - [[Axiomas de Peano]] → definen los números naturales.
> - [[Axioma del supremo]] → define los números reales.
> - [[Axioma de elección]] → teoría de conjuntos.
> - Los axiomas de [[Grupo]], [[Anillo]] y [[Cuerpo]] → estructuras algebraicas.

> [!warning] Ojo
> Algunos conceptos básicos (como **conjunto**) no se definen: se describen por los axiomas que cumplen. Ver [[Paradoja de Russell]].

## Conexiones
- **Necesitas antes:** [[Tautología y contradicción]], [[Modus ponens]]
- **Lleva a:** [[Definición, teorema, lema y corolario]], [[Métodos de demostración]]
