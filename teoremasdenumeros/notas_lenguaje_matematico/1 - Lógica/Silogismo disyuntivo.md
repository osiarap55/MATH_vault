---
tipo: teorema
tags: [teorema, logica, inferencia]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · p. 20"
aliases: [Leyes de inferencia, Silogismos disyuntivos]
---
# Silogismo disyuntivo

> [!tip] En palabras sencillas
> "O es A o es B. No es A. **Luego** es B." Es el razonamiento por **descarte**.

> [!important] Enunciado
> $$\neg p\land(p\lor q)\ \Rightarrow\ q \qquad\qquad p\land(\neg p\lor\neg q)\ \Rightarrow\ \neg q$$

> [!abstract] Demostración (idea)
> Si $\neg p=1$ entonces $p=0$; para que $p\lor q=1$ tiene que ser $q=1$.
> Otra forma: $p\lor q\iff\neg p\to q$ ([[Leyes del condicional]]) y se aplica [[Modus ponens]].

> [!example] Ejemplo
> "$x^2=x$ implica $x=0$ o $x=1$. Si sabemos que $x\ne 0$, entonces $x=1$."

> [!warning] Error típico
> $p\land(p\lor q)\not\Rightarrow\neg q$. Saber que $p$ es verdadera **no** dice nada de $q$ (la disyunción es inclusiva, ver [[Disyunción]]).

## Conexiones
- **Necesitas antes:** [[Disyunción]], [[Negación]]
- **Se usa en:** demostraciones por casos; [[Dominio de integridad]] ($ab=0\Rightarrow a=0\lor b=0$)
