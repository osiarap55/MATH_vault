---
tipo: método
tags: [metodo, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.2-1.5 · pp. 6-22"
aliases: [Tablas de verdad, Validación mediante tabla de verdad]
---
# Tabla de verdad

> [!tip] En palabras sencillas
> Una tabla de verdad es una lista de **todos los casos posibles** (todas las combinaciones de 0 y 1 de las proposiciones simples) con el valor que toma la proposición compuesta en cada caso. Es "probar todas las posibilidades".

> [!note] Cómo se construye
> 1. Pon una columna por cada proposición simple. Con $n$ proposiciones hay $2^n$ filas (2, 4, 8, 16, …).
> 2. Rellena las filas contando en binario: 00, 01, 10, 11 (para dos), 000, 001, …, 111 (para tres).
> 3. Añade columnas intermedias para cada trozo de la fórmula, **de dentro hacia fuera**.
> 4. La última columna es el valor de la proposición entera.

> [!example] Ejemplo: comprobar $p\to q \iff \neg p\lor q$
> | $p$ | $q$ | $\neg p$ | $p\to q$ | $\neg p\lor q$ | $(p\to q)\leftrightarrow(\neg p\lor q)$ |
> |:-:|:-:|:-:|:-:|:-:|:-:|
> | 0 | 0 | 1 | 1 | 1 | 1 |
> | 0 | 1 | 1 | 1 | 1 | 1 |
> | 1 | 0 | 0 | 0 | 0 | 1 |
> | 1 | 1 | 0 | 1 | 1 | 1 |
>
> Las columnas 4 y 5 son iguales → las proposiciones son **equivalentes**; la última columna es todo 1 → el bicondicional es una [[Tautología y contradicción|tautología]].

> [!important] Para qué sirve
> - Saber si una proposición es **tautología** (todo 1), **contradicción** (todo 0) o **contingente** (hay de los dos).
> - Saber si dos proposiciones son **equivalentes**: tienen la misma columna final.

> [!warning] Limitaciones y errores típicos
> - Con muchas variables es inviable a mano: 5 variables = 32 filas. Entonces es mejor [[Validación por refutación]] o [[Forma clausulada]].
> - Olvidar alguna fila: comprueba siempre que tienes $2^n$.
> - Equivocarse en el orden de los paréntesis: haz columnas intermedias.

## Conexiones
- **Necesitas antes:** [[Conectores lógicos]]
- **Lleva a:** [[Tautología y contradicción]], [[Leyes lógicas]]
- **Alternativas:** [[Validación por refutación]], [[Forma clausulada]]
- **Practica:** [[LM Ejercicios Cap 1#Ejercicio 4 · Tablas de verdad]]
