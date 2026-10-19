---
tipo: teorema
tags: [teorema, logica, chuleta]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.4 · pp. 14-21"
aliases: [Chuleta de leyes lógicas, Leyes de la lógica, Leyes asociativas, Leyes distributivas, Leyes conmutativas, Leyes de identidad, Leyes de simplificación, Ley de absorción]
---
# Leyes lógicas (chuleta)

> [!tip] En palabras sencillas
> Son **tautologías** que funcionan como las reglas del álgebra ($a(b+c)=ab+ac$…), pero para proposiciones. Sirven para **simplificar** y para **justificar cada paso** de una demostración.

## Leyes de equivalencia ($\iff$): se puede sustituir una por otra

### Con una proposición
| Ley | Fórmula |
|---|---|
| Doble negación | $\neg\neg p\iff p$ → [[Negación]] |
| Identidad | $p\lor p\iff p$ · $p\land p\iff p$ · $p\to p\iff \mathbf 1$ · $p\leftrightarrow p\iff\mathbf 1$ |
| Tercio excluso | $p\lor\neg p\iff\mathbf 1$ → [[Tercio excluso y no contradicción]] |
| No contradicción | $p\land\neg p\iff\mathbf 0$ |

### Con dos proposiciones
| Ley | Fórmula |
|---|---|
| Simplificación | $p\lor\mathbf 0\iff p$ · $p\land\mathbf 1\iff p$ · $\mathbf 1\to p\iff p$ |
| Conmutativas | $p\lor q\iff q\lor p$ · $p\land q\iff q\land p$ · $p\leftrightarrow q\iff q\leftrightarrow p$ (**¡$\to$ no es conmutativo!**) |
| **De Morgan** | $\neg(p\lor q)\iff\neg p\land\neg q$ · $\neg(p\land q)\iff\neg p\lor\neg q$ → [[Leyes de De Morgan]] |
| **Condicional** | $p\to q\iff\neg p\lor q\iff\neg(p\land\neg q)$ → [[Leyes del condicional]] |
| Expansión del condicional | $p\to q\iff p\leftrightarrow(p\land q)$ · $p\to q\iff q\leftrightarrow(p\lor q)$ |
| Bicondicional | $p\leftrightarrow q\iff(p\to q)\land(q\to p)$ → [[Bicondicional]] |
| **Reducción al absurdo** | $\neg p\to(q\land\neg q)\iff p$ → [[Reducción al absurdo]] |
| **Transposición** | $p\to q\iff\neg q\to\neg p$ · $p\leftrightarrow q\iff\neg p\leftrightarrow\neg q$ → [[Recíproco y contrarrecíproco]] |
| Absorción (no está en el libro, muy útil) | $p\land(p\lor q)\iff p$ · $p\lor(p\land q)\iff p$ |

### Con tres proposiciones
| Ley | Fórmula |
|---|---|
| Asociativas | $(p\lor q)\lor r\iff p\lor(q\lor r)$ · igual con $\land$ y con $\leftrightarrow$ |
| Distributivas | $p\lor(q\land r)\iff(p\lor q)\land(p\lor r)$ · $p\land(q\lor r)\iff(p\land q)\lor(p\land r)$ |
| Distributivas del $\to$ | $p\to(q\lor r)\iff(p\to q)\lor(p\to r)$ · $p\to(q\land r)\iff(p\to q)\land(p\to r)$ |
| Exportación | $(p\land q)\to r\iff p\to(q\to r)$ |

## Leyes condicionales ($\Rightarrow$): solo van en un sentido
| Ley | Fórmula |
|---|---|
| Simplificación condicional | $p\land q\Rightarrow p$ · $p\Rightarrow p\lor q$ |
| [[Silogismo disyuntivo]] | $\neg p\land(p\lor q)\Rightarrow q$ |
| [[Modus ponens]] | $(p\to q)\land p\Rightarrow q$ |
| [[Modus tollens]] | $(p\to q)\land\neg q\Rightarrow\neg p$ |
| [[Silogismo hipotético]] (transitiva) | $(p\to q)\land(q\to r)\Rightarrow(p\to r)$ |
| Resolución | $(\neg p\lor q)\land(p\lor r)\Rightarrow q\lor r$ |
| Dilema constructivo | $(p\to r)\land(q\to r)\land(p\lor q)\Rightarrow r$ |

> [!warning] Errores típicos
> - Aplicar una ley $\Rightarrow$ "al revés": de $p\lor q$ **no** se deduce $p$.
> - Distribuir mal: $\neg(p\land q)$ **no** es $\neg p\land\neg q$ (hay que cambiar $\land$ por $\lor$: De Morgan).

> [!abstract] Cómo se demuestra cualquiera de ellas
> Con una [[Tabla de verdad]] (todas las filas dan 1), por [[Validación por refutación]] o reduciendo a [[Forma clausulada]].

## Conexiones
- **Necesitas antes:** [[Tautología y contradicción]], [[Tabla de verdad]]
- **Lleva a:** [[Métodos de demostración]], [[Forma clausulada]]
- **Las mismas leyes para conjuntos:** [[Álgebra de conjuntos]]
- **Practica:** [[LM Ejercicios Cap 1#Ejercicio 2 · Simplificar]]
