---
tipo: teorema
tags: [teorema, algebra, grupos]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "§4.2 · pp. 131-132 (Congruencia módulo un subgrupo)"
aliases: [Congruencia módulo un subgrupo, Clases laterales, Grupo cociente, Orden de un grupo, G/H]
---
# Teorema de Lagrange (congruencia módulo un subgrupo)

> [!tip] En palabras sencillas
> Un subgrupo $H$ "trocea" el grupo $G$ en copias de sí mismo, todas del mismo tamaño. Por eso, si $G$ es finito, **el tamaño de $H$ divide al de $G$**.

> [!note] Congruencia módulo $H$
> Sea $(G,*)$ abeliano y $H$ subgrupo. Se define
> $$a\,\mathcal R_H\,b\iff a*b^{-1}\in H.$$
> Es una [[Relación de equivalencia]] y su clase es $[a]=a*H=\{a*h\mid h\in H\}$. El cociente se escribe $G/H$.

> [!important] Teorema de Lagrange
> 1. Todas las clases son **equipotentes** a $H$.
> 2. Si $G$ es finito, $\operatorname{card}(H)$ **divide** a $\operatorname{card}(G)$ (el **orden** del grupo).

> [!abstract] Demostración (idea y pasos)
> 1. **Es equivalencia:** reflexiva ($a*a^{-1}=e\in H$), simétrica (el inverso de $a*b^{-1}$ es $b*a^{-1}$), transitiva ($(a*b^{-1})*(b*c^{-1})=a*c^{-1}$).
> 2. **Forma de las clases:** $b\in[a]\iff b*a^{-1}=h\in H\iff b=a*h$.
> 3. **Mismo tamaño:** $\varphi:H\to[a]$, $h\mapsto a*h$ es sobreyectiva (por 2) e inyectiva (propiedad **cancelativa** del [[Grupo]]).
> 4. **Contar:** las clases forman una [[Partición de un conjunto|partición]] de $G$ en $c$ trozos de $k=\operatorname{card}H$ elementos: $n=c\cdot k$. ∎

> [!example] Ejemplos
> - $H=n\mathbb Z\subseteq\mathbb Z$: el cociente es $\mathbb Z/n\mathbb Z$ ([[Congruencia módulo n]]).
> - $H=2\pi\mathbb Z\subseteq\mathbb R$: el cociente son los ángulos $\mathbb R/2\pi\mathbb Z$.
> - Un grupo de 7 elementos solo tiene los subgrupos triviales ($\{e\}$ y $G$), porque 7 es primo.

> [!note] El cociente también es un grupo
> Con $[a]*[b]=[a*b]$ (bien definido, ver [[LM Ejercicios Cap 4#Ejercicio 3 · El cociente es un grupo|ejercicio]]), $G/H$ es un grupo: el **grupo cociente**.

## Conexiones
- **Necesitas antes:** [[Subgrupo]], [[Relación de equivalencia]], [[Partición de un conjunto]]
- **Lleva a:** [[Congruencia módulo n]], [[Ideal]] (la misma idea en anillos)
- **Profundiza:** [[resumen_teoriadegrupos]] (clases laterales, subgrupos normales)
