---
tipo: teorema
tags: [definicion, teorema, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "§7.1-7.2 · pp. 241-246; Def. 7.1, Teorema 7.2"
aliases: [C, ℂ, Complejos, Construcción de C, Unidad imaginaria, i]
---
# Números complejos  $\mathbb C$

> [!tip] En palabras sencillas
> Queremos un "sitio" donde $x^2=-1$ tenga solución sin perder las reglas de cálculo. **Un complejo es un par de reales** $(a,b)$, con una multiplicación especial que hace que $(0,1)^2=(-1,0)$.

> [!note] Planteamiento (§7.1): qué **tiene** que pasar
> Si existe un cuerpo $\mathbb C\supset\mathbb R$ con un $i$ tal que $i^2=-1$, entonces necesariamente:
> - $a+ib=a'+ib'\iff a=a'$ y $b=b'$;
> - $(a+ib)+(a'+ib')=(a+a')+i(b+b')$;
> - $(a+ib)(a'+ib')=(aa'-bb')+i(ab'+a'b)$ (distributiva + $i^2=-1$).
>
> Basta con $\sqrt{-1}$: si $\beta<0$, $\beta=(i\sqrt{-\beta})^2$.

> [!note] Definición 7.1
> $\mathbb C=\mathbb R^2$ con
> $$(a,b)+(a',b')=(a+a',\,b+b')\qquad(a,b)\cdot(a',b')=(aa'-bb',\,ab'+a'b)$$

> [!important] Teorema 7.2: $(\mathbb C,+,\cdot)$ es un cuerpo
> - Neutros: $(0,0)$ y $(1,0)$. Opuesto: $(-a,-b)$.
> - **Inverso** de $(a,b)\neq(0,0)$: $\left(\dfrac a{a^2+b^2},\dfrac{-b}{a^2+b^2}\right)$.
> - **$\mathbb R\subset\mathbb C$:** $a\mapsto(a,0)$ es un isomorfismo de cuerpos sobre su imagen ([[Homomorfismo]]). Escribimos $a$ en vez de $(a,0)$.
> - Con $i=(0,1)$: $(a,b)=a+ib$ y $i^2=-1$.

> [!example] Potencias de $i$
> $i^1=i$, $i^2=-1$, $i^3=-i$, $i^4=1$, y se repiten con periodo 4. Para $i^n$ usa el **resto de dividir $n$ entre 4**: $i^{323}=i^{4\cdot80+3}=i^3=-i$.

> [!warning] Ojo
> $\sqrt{xy}=\sqrt x\sqrt y$ **solo vale para reales positivos**. Si no: $1=\sqrt1=\sqrt{(-1)(-1)}\ "="\ \sqrt{-1}\sqrt{-1}=i^2=-1$ ✗. Por eso Gauss introdujo el símbolo $i$ en vez de $\sqrt{-1}$.

## Conexiones
- **Necesitas antes:** [[Números reales]], [[Cuerpo]], [[Producto cartesiano]]
- **Lleva a:** [[Forma binómica y conjugado]], [[Plano complejo]], [[C no es un cuerpo ordenado]]
- **Profundiza:** [[resumen_completo_ahlfors]]
