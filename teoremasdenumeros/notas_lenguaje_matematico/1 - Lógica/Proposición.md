---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.1 · p. 4"
aliases: [Proposición lógica, Proposiciones, Proposición simple, Proposición compuesta]
---
# Proposición

> [!tip] En palabras sencillas
> Una proposición es una frase de la que se puede decir **sin dudar** si es verdadera o falsa. Es el "átomo" de la lógica: todo lo demás se construye con ellas.

> [!note] Definición
> - **Proposición simple:** describe una propiedad de un objeto concreto y se le puede atribuir sin ambigüedad el valor **verdadero (1)** o **falso (0)**. Se denotan con minúsculas: $p, q, r, \dots$
> - **Proposición compuesta:** se obtiene uniendo proposiciones simples con [[Conectores lógicos|conectores]] ("y", "o", "si… entonces", …).

> [!example] Ejemplos
> - "2 es un número primo" → proposición **verdadera** ($p=1$).
> - "9 es el cubo de 3" → proposición **falsa** ($p=0$).
> - "Doce es divisible por dos **y** por tres" → proposición **compuesta**.
> - "Si llueve, el suelo se moja" → compuesta por "llueve" y "el suelo se moja".

> [!failure] No son proposiciones
> - "**El número elegido** es par" → no sabemos qué número es, así que no tiene un valor fijo. Es un [[Predicado]] (una frase con una variable): $P(x)$: "$x$ es par".
> - "El primer número es menor que el segundo" → es una relación entre dos variables (predicado de dos argumentos).
> - "¿Qué hora es?" o "¡Cierra la puerta!" → preguntas y órdenes no son verdaderas ni falsas.

> [!warning] Errores típicos
> - Pensar que una frase con **variables** ($x>3$) es una proposición. No lo es hasta que das un valor a $x$ o la **cuantificas** ($\forall x$, $\exists x$). Lo verás en [[Cuantificadores]].
> - Confundir "no sé si es verdadera" con "no es una proposición". *"Hay vida en Marte"* es una proposición aunque no sepamos su valor.

## Conexiones
- **Lleva a:** [[Conectores lógicos]], [[Tabla de verdad]]
- **Se generaliza en:** [[Predicado]] (cap. 2)
- **Practica:** [[LM Ejercicios Cap 1#Ejercicio 5 · Pasar a símbolos]]
