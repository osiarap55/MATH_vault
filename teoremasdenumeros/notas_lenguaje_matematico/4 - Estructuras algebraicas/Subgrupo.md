---
tipo: teorema
tags: [definicion, teorema, algebra, grupos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "§4.2 · pp. 130-131; Prop. 4.14"
aliases: [Subgrupos, Caracterización de subgrupos, Criterio de subgrupo, Subgrupo generado]
---
# Subgrupo

> [!tip] En palabras sencillas
> Un subgrupo es un trozo de un grupo que **es un grupo por sí mismo** con la misma operación. Para comprobarlo **no** hace falta repetir todo: basta un test de una línea.

> [!note] Definición
> $\emptyset\neq H\subseteq G$ es **subgrupo** de $(G,*)$ si $(H,*)$ es un grupo. Siempre lo son $\{e\}$ y $G$.
> Hay que comprobar: (i) $a,b\in H\Rightarrow a*b\in H$; (ii) $e\in H$; (iii) $a\in H\Rightarrow a^{-1}\in H$. La asociativa (y la conmutativa) **se heredan** de $G$.

> [!important] Proposición 4.14 (criterio de subgrupo)
> $\emptyset\neq H\subseteq G$ es subgrupo $\iff$ para todo $a,b\in H$: $\ a*b^{-1}\in H$.
> En notación aditiva: $a-b\in H$.

> [!abstract] Demostración (idea y pasos)
> (⇒) Evidente. (⇐) Como $H\neq\emptyset$, toma $a\in H$:
> 1. $e=a*a^{-1}\in H$.
> 2. Para $b\in H$: $b^{-1}=e*b^{-1}\in H$.
> 3. Para $a,b\in H$: $a*b=a*(b^{-1})^{-1}\in H$.

> [!example] Ejemplos
> - $n\mathbb Z=\{kn\}$ es subgrupo de $(\mathbb Z,+)$: $kn-hn=(k-h)n$.
> - $2\pi\mathbb Z$ es subgrupo de $(\mathbb R,+)$.
> - $\mathbb Z[\sqrt2]=\{a+b\sqrt2\mid a,b\in\mathbb Z\}$ es subgrupo de $(\mathbb R,+)$.
> - La intersección de dos subgrupos es un subgrupo. (La unión, en general, **no**.)
> - **Subgrupo generado por $a$:** $\{\dots,-2a,-a,0,a,2a,\dots\}$, la imagen de $n\mapsto na$.

> [!tip] Truco práctico
> Para probar que algo **es un grupo**, muchas veces es más rápido ver que es **subgrupo** de un grupo conocido: te ahorras la asociativa.

## Conexiones
- **Necesitas antes:** [[Grupo]]
- **Lleva a:** [[Teorema de Lagrange]], [[Núcleo e imagen de un homomorfismo]], [[Subanillo]], [[Ideal]]
- **Profundiza:** [[resumen_teoriadegrupos]]
