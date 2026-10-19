---
tipo: definición
tags: [definicion, conjuntos]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.1 · pp. 34-38"
aliases: [Conjuntos, Elemento, Pertenencia, Conjunto vacío, Conjunto unitario, Extensión, Comprensión, Diagrama de Venn, Igualdad de conjuntos]
---
# Conjunto

> [!tip] En palabras sencillas
> Un conjunto es una "bolsa" de objetos (sus **elementos**). Lo único que importa es **qué hay dentro**: no importa el orden ni si repites un elemento.

> [!note] Ideas básicas (el libro no lo define: es un término primitivo)
> - **Pertenencia:** $b\in C$ ("$b$ es elemento de $C$") debe ser una [[Proposición]]: verdadera o falsa sin ambigüedad. Si es falsa, $b\notin C$.
> - **Igualdad:** $A=B$ si y sólo si tienen **los mismos elementos**.
> - **Por extensión:** dando la lista, $A=\{1,2\}$.
> - **Por comprensión:** dando una propiedad, $A=\{x\in\mathbb Z\mid x^2-3x+2=0\}$ (ver [[Predicado]]).
> - **Unitario:** $\{a\}$, cuyo único elemento es $a$. **No es lo mismo** $a$ que $\{a\}$.
> - **Vacío:** $\emptyset=\{x\in C\mid x\neq x\}$, no tiene elementos y es **subconjunto de cualquier conjunto**.
> - Reglas: un objeto no puede ser elemento de sí mismo ($b\in b$ es falso) y **no existe el conjunto de todos los conjuntos** (ver [[Paradoja de Russell]]).

> [!example] Ejemplos
> - $\{1,2\}=\{2,1\}=\{1,1,2\}$: mismo conjunto (orden y repeticiones no importan).
> - $\{x\in\mathbb Z\mid x^2-3x+2=0\}=\{1,2\}=\{x\in\mathbb Z\mid 0<x<3\}$: un conjunto puede describirse con predicados distintos.
> - Pares: $2\mathbb N=\{x\in\mathbb N\mid\exists k\in\mathbb N,\ x=2k\}=\{2k\mid k\in\mathbb N\}$.

> [!failure] Cosas que se confunden
> - $\emptyset$ (vacío, 0 elementos) vs $\{\emptyset\}$ (1 elemento: el vacío).
> - $\in$ (elemento) vs $\subseteq$ (subconjunto): $1\in\{1,2\}$, pero $\{1\}\subseteq\{1,2\}$. Y $1\not\subseteq\{1,2\}$.

> [!warning] Errores típicos
> - Escribir $\{x\mid P(x)\}$ sin decir de dónde sale $x$. Siempre hay que fijar el **universo**: $\{x\in U\mid P(x)\}$.
> - Pensar que el orden importa: para eso están los **pares ordenados** ([[Producto cartesiano]]).

## Conexiones
- **Necesitas antes:** [[Proposición]]
- **Lleva a:** [[Predicado]], [[Inclusión de conjuntos]], [[Unión e intersección]], [[Producto cartesiano]]
- **Infinito/finito:** [[Conjunto finito]], [[Conjunto infinito]] (cap. 5)
