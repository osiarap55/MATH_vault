---
tipo: definición
tags: [definicion, teorema, algebra]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "§4.6 · pp. 145-150; Prop. 4.39"
aliases: [Homomorfismos, Isomorfismo, Endomorfismo, Automorfismo, Isomorfos, Homomorfismo de grupos, Homomorfismo de anillos, Homomorfismo de orden, Aplicación creciente, Inmersión]
---
# Homomorfismo

> [!tip] En palabras sencillas
> Un homomorfismo es una aplicación que **respeta la operación**: da igual operar y luego transformar, que transformar y luego operar. Un **isomorfismo** (homomorfismo biyectivo) dice que dos estructuras son "**la misma con distinto disfraz**".

> [!note] Definición
> $f:(G,*)\to(G',\star)$ es un **homomorfismo** si
> $$f(a*b)=f(a)\star f(b)\quad\text{para todo }a,b.$$
> | Nombre | Condición |
> |---|---|
> | Endomorfismo | $G=G'$ con la misma operación |
> | **Isomorfismo** | biyectivo |
> | Automorfismo | endomorfismo biyectivo |
> - **De anillos:** $f(a+b)=f(a)+f(b)$ **y** $f(ab)=f(a)f(b)$.
> - **De orden:** $u\preceq u'\Rightarrow f(u)\preceq f(u')$ (aplicación **creciente**).

> [!example] Ejemplos
> - $e^x:(\mathbb R,+)\to(\mathbb R^+,\cdot)$: $e^{a+b}=e^ae^b$. Es **isomorfismo**; su inverso es $\log$ ("el logaritmo convierte productos en sumas").
> - $\det:(\text{matrices invertibles},\cdot)\to(\mathbb R^*,\cdot)$: $\det(AB)=\det A\det B$. No es inyectivo.
> - $x\mapsto ax$ ($a\neq0$): automorfismo de $(\mathbb R,+)$.
> - En un grupo abeliano: $a\mapsto na$ y $a\mapsto-a$ son endomorfismos.
> - $n\mapsto na$ de $(\mathbb Z,+)$ en $G$: su imagen es el **subgrupo generado** por $a$.

> [!important] Proposición 4.39
> 1. $f(G)$ es cerrado para la operación de $G'$.
> 2. La **composición** de homomorfismos es homomorfismo.
> 3. La **inversa** de un isomorfismo es isomorfismo.
>
> ⇒ "Ser isomorfos" es reflexivo, simétrico y transitivo.

> [!important] En grupos
> - $f(0_G)=0_{G'}$ y $f(-a)=-f(a)$.
> - Imagen de un subgrupo = subgrupo; antiimagen de un subgrupo = subgrupo.
> - Ver [[Núcleo e imagen de un homomorfismo]].

> [!note] Identificaciones $\mathbb N\subset\mathbb Z\subset\mathbb Q\subset\mathbb R\subset\mathbb C$
> Estas "inclusiones" son en realidad **inmersiones**: homomorfismos inyectivos.
> - $\mathbb Z\subset\mathbb Q$: isomorfismo de anillos **ordenados** entre $\mathbb Z$ y $\{\frac z1\}\subseteq\mathbb Q$.
> - $\mathbb R\subset\mathbb C$: isomorfismo de **cuerpos** $x\mapsto(x,0)$ (sin orden, porque $\mathbb C$ no se ordena).

## Conexiones
- **Necesitas antes:** [[Aplicación]], [[Grupo]], [[Composición de aplicaciones]]
- **Lleva a:** [[Núcleo e imagen de un homomorfismo]], [[Factorización canónica de una aplicación]]
- **Se usa en:** [[Números enteros]], [[Números racionales]], [[Números complejos]] (inmersiones)
- **Profundiza:** [[resumen_teoriadegrupos]], [[resumen_algebralineal]] (aplicaciones lineales = homomorfismos de espacios vectoriales)
