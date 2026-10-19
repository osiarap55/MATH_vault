---
tipo: teorema
tags: [teorema, aplicaciones, relaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "§3.4 · pp. 106-108; Ejemplos 3.43-3.44"
aliases: [Descomposición canónica, Factorización canónica, Primer teorema de isomorfía (versión conjuntos)]
---
# Factorización canónica de una aplicación

> [!tip] En palabras sencillas
> **Toda** aplicación se puede descomponer en tres pasos sencillos:
> 1. **Pegar** los elementos que tienen la misma imagen (proyección, sobreyectiva).
> 2. **Emparejar** cada grupo con su imagen (biyección).
> 3. **Meter** la imagen dentro del conjunto final (inclusión, inyectiva).

> [!important] Teorema
> Sea $f:A\to B$ y la relación de equivalencia $x\sim_f x'\iff f(x)=f(x')$. Entonces
> $$f=i\circ b\circ p$$
> | Pieza | Definición | Tipo |
> |---|---|---|
> | $p:A\to A/\!\sim_f$ | $p(x)=[x]$ | proyección canónica, **sobreyectiva** |
> | $b:A/\!\sim_f\to f(A)$ | $b([x])=f(x)$ | **biyectiva** |
> | $i:f(A)\to B$ | $i(y)=y$ | inclusión, **inyectiva** |
>
> ```
>        f
>   A ───────→ B
>   │          ↑
> p │          │ i
>   ↓    b     │
>  A/~ ──────→ f(A)
> ```

> [!abstract] Demostración (idea y pasos)
> 1. **$b$ está bien definida:** si $[x]=[x']$, entonces $x\sim_f x'$, o sea $f(x)=f(x')$. El valor no depende del representante.
> 2. **$b$ inyectiva:** $b([x])=b([x'])\Rightarrow f(x)=f(x')\Rightarrow x\sim_fx'\Rightarrow[x]=[x']$.
> 3. **$b$ sobreyectiva:** si $y\in f(A)$, $y=f(x)$ para algún $x$, y $b([x])=y$.
> 4. **Composición:** $i(b(p(x)))=i(b([x]))=f(x)$. ∎

> [!example] Ejemplo: $f(x)=\sin x$ de $\mathbb R$ en $\mathbb R$
> - $x\sim x'\iff\sin x=\sin x'\iff x'=x+2k\pi$ o $x'=\pi-x+2k\pi$.
> - Cada clase tiene un único representante en $[-\pi/2,\pi/2]$.
> - $f(\mathbb R)=[-1,1]$, y $b$ es la biyección clases $\to[-1,1]$ (de ahí sale $\arcsin$).

> [!important] Por qué importa
> Es la idea que, con estructura algebraica, se convierte en el **primer teorema de isomorfía**: $G/\ker f\cong\operatorname{Im}f$ (grupos, anillos, espacios vectoriales).

## Conexiones
- **Necesitas antes:** [[Conjunto cociente]], [[Aplicación biyectiva]], [[Imagen y antiimagen]]
- **Lleva a:** [[Homomorfismo]] (núcleo e imagen), [[resumen_teoriadegrupos]] (teoremas de isomorfía)
