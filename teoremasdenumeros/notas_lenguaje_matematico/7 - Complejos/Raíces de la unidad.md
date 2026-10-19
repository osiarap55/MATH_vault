---
tipo: teorema
tags: [teorema, complejos, grupos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "Ejemplo 7.11 · p. 255; Ejercicios 12-13"
aliases: [Raíces n-ésimas de la unidad, U_n, Grupo de las raíces de la unidad]
---
# Raíces $n$-ésimas de la unidad

> [!note] Definición
> Son las soluciones de $z^n=1$:
> $$U_n=\{z_k=e^{2k\pi i/n}\mid k=0,1,\dots,n-1\}$$
> Son los vértices de un **polígono regular de $n$ lados** inscrito en la circunferencia unidad, con un vértice en $1$.
> Ej.: $U_3=\left\{1,\ -\frac12+i\frac{\sqrt3}2,\ -\frac12-i\frac{\sqrt3}2\right\}$; $U_4=\{1,i,-1,-i\}$.

> [!important] Propiedades
> 1. $z_k=(z_1)^k$: todas son **potencias de una sola**, $z_1=e^{2\pi i/n}$.
> 2. $(U_n,\cdot)$ es un **grupo**, isomorfo a $(\mathbb Z/n,+)$ mediante $\bar k\mapsto z_1^k$ ([[Homomorfismo]], [[Congruencia módulo n]]).
> 3. **Suma** de todas ($n\ge2$): $1+z_1+\cdots+z_1^{n-1}=\frac{1-z_1^n}{1-z_1}=0$.
> 4. **Producto** de todas: $(-1)^{n+1}$.
> 5. $(U_n,+,\cdot)$ **no** es un cuerpo: $1+1=2\notin U_n$ (la suma no es interna).

> [!abstract] Por qué la suma es 0
> Es una progresión geométrica de razón $z_1\neq1$ y $z_1^n=1$. Geométricamente: los vértices de un polígono regular están "equilibrados" alrededor del centro.

> [!tip] Relación con todas las raíces
> Si $z_0$ es **una** raíz $n$-ésima de $w$, todas las demás son $z_0\cdot u$ con $u\in U_n$.

## Conexiones
- **Necesitas antes:** [[Raíces n-ésimas de un complejo]], [[Grupo]]
- **Isomorfo a:** $\mathbb Z/n$ ([[Congruencia módulo n]])
- **Profundiza:** [[resumen_teoriadegrupos]] (grupos cíclicos), [[resumen_cuerposanillosyteoriadegalois]] (extensiones ciclotómicas)
