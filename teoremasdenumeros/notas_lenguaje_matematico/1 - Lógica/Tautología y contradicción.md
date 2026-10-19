---
tipo: definición
tags: [definicion, logica]
capitulo: "[[LM Cap 1 - Nociones de lógica]]"
ref: "§1.3 · p. 13"
aliases: [Tautología, Contradicción, Proposiciones equivalentes]
---
# Tautología y contradicción

> [!tip] En palabras sencillas
> - Una **tautología** es una frase que es verdad **pase lo que pase** ("llueve o no llueve").
> - Una **contradicción** es falsa **pase lo que pase** ("llueve y no llueve").

> [!note] Definición
> - **Tautología:** proposición que solo toma el valor 1. Se denota $\mathbf 1$.
> - **Contradicción:** proposición que solo toma el valor 0. Se denota $\mathbf 0$.
> - Dos proposiciones $p, q$ son **equivalentes** ($p\iff q$) si toman siempre el mismo valor, es decir, si $p\leftrightarrow q$ es una tautología.

> [!important] Principio de sustitución
> Si $p\iff q$ y $p$ aparece dentro de otra proposición $r$, puedes **cambiar $p$ por $q$** y lo que obtienes sigue siendo equivalente a $r$. Por eso se dice coloquialmente que $p$ y $q$ "son iguales". Esto es lo que permite **simplificar** usando [[Leyes lógicas]].

> [!example] Ejemplos
> - Tautologías: $p\lor\neg p$, $p\to p$, $(p\land q)\to p$, todas las [[Leyes lógicas]].
> - Contradicciones: $p\land\neg p$, $\neg(p\to p)$.
> - Ni una cosa ni otra (contingente): $p\land q$.

> [!warning] Errores típicos
> - "Tautología" en lógica **no** significa "frase que repite lo mismo", sino "siempre verdadera".
> - Una proposición que no es tautología **no** tiene por qué ser contradicción: puede ser contingente.

## Conexiones
- **Necesitas antes:** [[Tabla de verdad]]
- **Lleva a:** [[Leyes lógicas]], [[Implicación y equivalencia lógica]], [[Tercio excluso y no contradicción]], [[Reducción al absurdo]]
- **En el comentario del capítulo:** un *teorema* es una tautología deducida de axiomas → [[Sistema axiomático]]
