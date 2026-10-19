---
tipo: método
tags: [metodo, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.5 · p. 22"
aliases: [Refutación, Método de refutación]
---
# Validación por refutación

> [!tip] En palabras sencillas
> Para ver si una fórmula es una tautología **sin hacer la tabla entera**: supón que es falsa y mira si eso te lleva a algo imposible. Si sí → era tautología. Es la [[Reducción al absurdo]] aplicada a fórmulas.

> [!note] Método
> 1. Supón que la proposición vale **0**.
> 2. Usa lo que obliga cada conector:
>    - $A\to B=0$ ⇒ $A=1$ y $B=0$ (la única forma).
>    - $A\lor B=0$ ⇒ $A=0$ y $B=0$.
>    - $A\land B=1$ ⇒ $A=1$ y $B=1$.
> 3. Propaga los valores con [[Modus ponens]] y [[Modus tollens]].
> 4. Si una proposición acaba valiendo **0 y 1 a la vez** → contradicción → la fórmula es **tautología**.
>    Si llegas a una asignación coherente → has encontrado una fila donde es falsa → **no** es tautología.

> [!example] Ejemplo: $(p\to q)\to[(q\to r)\to(p\to r)]$
> | Paso | Deducción |
> |---|---|
> | 1 | Supongo que todo vale 0 |
> | 2 | $p\to q=1$ y $(q\to r)\to(p\to r)=0$ |
> | 3 | $q\to r=1$ y $p\to r=0$ |
> | 4 | $p=1$, $r=0$ |
> | 5 | $p=1$ y $p\to q=1$ ⇒ $q=1$ |
> | 6 | $q=1$ y $q\to r=1$ ⇒ $r=1$ |
> | 7 | $r=0$ (paso 4) y $r=1$ (paso 6): **contradicción** ✓ tautología |

> [!warning] Cuándo funciona mejor
> Va muy bien cuando la fórmula "de fuera" es un $\to$ o un $\lor$ (al suponerla falsa, se fija todo). Si es un $\land$ que vale 0, hay que separar casos y es más lento.

## Conexiones
- **Necesitas antes:** [[Condicional]], [[Reducción al absurdo]]
- **Alternativas:** [[Tabla de verdad]], [[Forma clausulada]]
- **Practica:** [[LM Ejercicios Cap 1#Ejercicio 7 · Dilema constructivo por refutación]]
