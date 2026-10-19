---
tipo: definición
tags: [definicion, cardinales]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Comentarios cap. 4 · pp. 151-153"
aliases: [Aritmética de cardinales, Suma de cardinales, Producto de cardinales]
---
# Suma y producto de cardinales

> [!tip] En palabras sencillas
> Para sumar tamaños, **junta** dos conjuntos que no se solapen. Para multiplicar tamaños, haz el **producto cartesiano**. Para conjuntos finitos sale la aritmética de siempre; para infinitos salen cosas curiosas.

> [!note] Definición
> Sean $a=\operatorname{card}A$, $b=\operatorname{card}B$.
> - **Suma** (con $A\cap B=\emptyset$): $a+b=\operatorname{card}(A\cup B)$.
>   Si no son disjuntos, usa $\{0\}\times A$ y $\{1\}\times B$.
> - **Producto:** $a\cdot b=\operatorname{card}(A\times B)$.
>
> No dependen de los conjuntos elegidos (biyecciones entre representantes dan biyecciones entre uniones/productos).

> [!important] Propiedades
> - Suma: conmutativa, asociativa, neutro $0$; $a+b=0\Rightarrow a=b=0$.
> - $a\le b\iff$ existe $c$ con $a+c=b$.
> - Producto: conmutativo ($A\times B\simeq B\times A$), asociativo, neutro $1$, $a\cdot0=0$, distributivo respecto a la suma.
> - $ab=0\Rightarrow a=0$ o $b=0$; $ab=1\Rightarrow a=b=1$.

> [!example] Curiosidades con infinitos
> - $\aleph_0+1=\aleph_0$ (el hotel de Hilbert: siempre cabe uno más).
> - $\aleph_0+\aleph_0=\aleph_0$ (pares + impares = naturales).
> - $\aleph_0\cdot\aleph_0=\aleph_0$ ($\mathbb N\times\mathbb N$ es numerable, ver [[Conjunto numerable]]).
> - Por eso **no** se puede "restar" ni "dividir" cardinales infinitos.

## Conexiones
- **Necesitas antes:** [[Cardinal]], [[Producto cartesiano]], [[Unión e intersección]]
- **Lleva a:** [[Suma y producto de naturales]] (los naturales como cardinales finitos), [[Conjunto numerable]]
