---
tipo: teorema
tags: [teorema, algebra, grupos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Teorema 4.40 · pp. 148-149"
aliases: [Núcleo, Ker, Kernel, Imagen de un homomorfismo, Inyectivo si y sólo si núcleo trivial]
---
# Núcleo e imagen de un homomorfismo

> [!note] Definición
> Sea $f:(G,+)\to(G',+)$ un homomorfismo de grupos.
> $$\operatorname{Ker}f=\{a\in G\mid f(a)=0_{G'}\}=f^{-1}(\{0_{G'}\})\qquad\operatorname{Im}f=f(G)$$

> [!important] Teorema 4.40
> 1. $\operatorname{Im}f$ es un subgrupo de $G'$.
> 2. $\operatorname{Ker}f$ es un subgrupo de $G$.
> 3. **$f$ es inyectivo $\iff\operatorname{Ker}f=\{0_G\}$.**
> 4. $f$ es sobreyectivo $\iff\operatorname{Im}f=G'$.

> [!tip] Por qué el punto 3 es tan útil
> Para ver si $f$ es inyectiva, en vez de estudiar todos los pares $f(a)=f(b)$, **basta mirar qué va al 0**.

> [!abstract] Demostración de 3
> Clave: $f(a)=f(b)\iff f(a)-f(b)=0\iff f(a-b)=0\iff a-b\in\operatorname{Ker}f$.
> - (⇐) Si $\operatorname{Ker}f=\{0\}$ y $f(a)=f(b)$, entonces $a-b=0$.
> - (⇒) Si $f$ es inyectiva y $c\in\operatorname{Ker}f$, entonces $f(c)=0=f(0)$, luego $c=0$.

> [!example] Ejemplos
> - $f(x,y)=(x+y,\,3x+5y)$ en $(\mathbb R^2,+)$: $\operatorname{Ker}f$ = soluciones de $x+y=0$, $3x+5y=0$ = $\{(0,0)\}$. **Inyectiva.**
> - $\det$: su núcleo son las matrices con $\det=1$, que no es $\{I\}$ (p. ej. $\begin{pmatrix}2&0\\0&1/2\end{pmatrix}$). No inyectivo.
> - $n\mapsto na$: el núcleo $\{n\mid na=0\}$ es un subgrupo de $\mathbb Z$, de la forma $m\mathbb Z$ ($m$ = **orden** de $a$).
> - En anillos conmutativos, $\operatorname{Ker}f$ es un [[Ideal]].

## Conexiones
- **Necesitas antes:** [[Homomorfismo]], [[Subgrupo]], [[Imagen y antiimagen]]
- **Lleva a:** el primer teorema de isomorfía $G/\operatorname{Ker}f\cong\operatorname{Im}f$ ([[Factorización canónica de una aplicación]] + estructura)
- **Profundiza:** [[resumen_teoriadegrupos]], [[resumen_algebralineal]] (teorema rango-núcleo)
