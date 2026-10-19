---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2-1.3 · pp. 6-13"
aliases: [Conector lógico, Conectivas, Conectiva lógica]
---
# Conectores lógicos

> [!tip] En palabras sencillas
> Los conectores son las "palabras pegamento" ("no", "y", "o", "si… entonces", "si y sólo si") que unen [[Proposición|proposiciones]] para formar otras más grandes. El valor de la proposición grande depende **solo** de los valores de las pequeñas.

> [!note] Los cinco conectores básicos
> | Conector | Símbolo | Se lee | Es verdadera cuando… |
> |---|---|---|---|
> | [[Negación]] | $\neg p$ | no $p$ | $p$ es falsa |
> | [[Conjunción]] | $p\land q$ | $p$ y $q$ | las dos son verdaderas |
> | [[Disyunción]] | $p\lor q$ | $p$ o $q$ | al menos una es verdadera |
> | [[Condicional]] | $p\to q$ | si $p$ entonces $q$ | **no** ocurre "$p$ verdadera y $q$ falsa" |
> | [[Bicondicional]] | $p\leftrightarrow q$ | $p$ si y sólo si $q$ | las dos tienen el mismo valor |

## ¿Cuántos conectores hay?
Un conector queda totalmente determinado por su [[Tabla de verdad]].
- Con **una** proposición hay $2^2 = 4$ tablas posibles: siempre 0, identidad ($p$), negación ($\neg p$) y siempre 1.
- Con **dos** proposiciones hay 4 filas, luego $2^4 = 16$ conectores posibles ($C_0,\dots,C_{15}$). Entre ellos: $\land = C_1$, $\lor = C_7$, $\leftrightarrow = C_9$, $\to = C_{13}$ y la **disyunción excluyente** $p\oplus q = C_6$.
- Con **tres** proposiciones hay 8 filas y $2^8 = 256$ tablas distintas.

> [!important] Idea clave
> Por muy larga que escribas una expresión con $n$ proposiciones, **solo hay $2^{2^n}$ significados distintos posibles**. Por eso tiene sentido buscar la expresión más corta equivalente: para eso sirven las [[Leyes lógicas]].

## Paréntesis: quién afecta a quién
- $\neg$ solo afecta a lo que tiene **inmediatamente** a la derecha: $\neg p \land q$ es $(\neg p)\land q$, que **no** es lo mismo que $\neg(p\land q)$.
- $p\land q\lor r$ **está mal escrita**: puede ser $(p\land q)\lor r$ o $p\land(q\lor r)$, y no son equivalentes.
- El orden importa en el condicional: $p\to q$ **no** equivale a $q\to p$ (ver [[Recíproco y contrarrecíproco]]).

> [!warning] Errores típicos
> - Quitar paréntesis "porque se entiende". En lógica no se entiende: hay que ponerlos.
> - Creer que $\to$ significa causa-efecto. Es solo una tabla de verdad (ver [[Condicional]]).

## Conexiones
- **Necesitas antes:** [[Proposición]]
- **Lleva a:** [[Tabla de verdad]], [[Leyes lógicas]]
- **Paralelismo:** las operaciones de conjuntos copian a los conectores: $\land \leftrightarrow \cap$, $\lor \leftrightarrow \cup$, $\neg \leftrightarrow$ complementario (ver [[Unión e intersección]]).
