---
tipo: teorema
tags: [teorema, conjuntos, chuleta]
capitulo: "[[LM Cap 2 - Conjuntos]]"
ref: "§2.3 · pp. 53-55, Cuadro 2.1"
aliases: [Propiedades del álgebra de conjuntos, Leyes de De Morgan para conjuntos, Leyes de conjuntos, Álgebra de Boole de conjuntos]
---
# Álgebra de conjuntos (chuleta)

> [!tip] En palabras sencillas
> **Cada ley de conjuntos es una [[Leyes lógicas|ley lógica]] disfrazada.** Si $A=\{x\mid P_x\}$, $B=\{x\mid Q_x\}$, entonces $\cup\leftrightarrow\lor$, $\cap\leftrightarrow\land$, $\bar{\ }\leftrightarrow\neg$, $U\leftrightarrow\mathbf 1$, $\emptyset\leftrightarrow\mathbf 0$.

Todos los conjuntos son subconjuntos de un universo $U$.

| Ley | Conjuntos | Lógica |
|---|---|---|
| Idempotencia | $A\cup A=A$ · $A\cap A=A$ | $P\lor P\iff P$ · $P\land P\iff P$ |
| Conmutativas | $A\cup B=B\cup A$ · $A\cap B=B\cap A$ | $P\lor Q\iff Q\lor P$ · … |
| Asociativas | $(A\cup B)\cup C=A\cup(B\cup C)$ · igual con $\cap$ | $(P\lor Q)\lor R\iff P\lor(Q\lor R)$ · … |
| Distributivas | $A\cup(B\cap C)=(A\cup B)\cap(A\cup C)$ | $P\lor(Q\land R)\iff(P\lor Q)\land(P\lor R)$ |
| | $A\cap(B\cup C)=(A\cap B)\cup(A\cap C)$ | $P\land(Q\lor R)\iff(P\land Q)\lor(P\land R)$ |
| Identidad | $A\cup\emptyset=A$ · $A\cup U=U$ | $P\lor\mathbf 0\iff P$ · $P\lor\mathbf 1\iff\mathbf 1$ |
| | $A\cap\emptyset=\emptyset$ · $A\cap U=A$ | $P\land\mathbf 0\iff\mathbf 0$ · $P\land\mathbf 1\iff P$ |
| Complementario | $A\cup\bar A=U$ · $A\cap\bar A=\emptyset$ | tercio excluso · no contradicción |
| | $\bar{\bar A}=A$ · $\bar U=\emptyset$ · $\bar\emptyset=U$ | doble negación · $\neg\mathbf 1\iff\mathbf 0$ |
| **De Morgan** | $\overline{A\cup B}=\bar A\cap\bar B$ · $\overline{A\cap B}=\bar A\cup\bar B$ | $\neg(P\lor Q)\iff\neg P\land\neg Q$ · … |
| Inclusión | $A\subseteq B$ | $P\Rightarrow Q$ |

> [!example] Cómo se usa (Ejercicio 2.29): $(A\cap B)\cup(A\cap\bar B)=A$
> $$(A\cap B)\cup(A\cap\bar B)\overset{\text{distrib.}}{=}A\cap(B\cup\bar B)\overset{\text{compl.}}{=}A\cap U\overset{\text{ident.}}{=}A$$
> Interpretación: los elementos de $A$ o están en $B$ o no lo están.

> [!tip] Dos maneras de demostrar una igualdad de conjuntos
> 1. **Doble inclusión** con elementos ([[Inclusión de conjuntos]]).
> 2. **Cálculo** con las leyes de esta tabla (como arriba). Suele ser más corto.

## Conexiones
- **Necesitas antes:** [[Unión e intersección]], [[Diferencia y complementario]], [[Leyes lógicas]]
- **Estructura:** $(\mathcal P(U),\cup,\cap,\bar{\ })$ es un *álgebra de Boole*, igual que las proposiciones con $\lor,\land,\neg$
- **Practica:** [[LM Ejercicios Cap 2#Ejercicio 7 · Simplificar y deducir inclusiones]]
