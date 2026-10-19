---
tipo: ejercicios
tags: [ejercicios, complejos]
capitulo: "[[LM Cap 7 - Números complejos]]"
ref: "Ejercicios propuestos · pp. 265-267"
---
# Ejercicios · Cap 7 · Números complejos

> [!tip] Cómo usar esta nota
> Intenta cada ejercicio en papel antes de desplegar la solución. Entre paréntesis, el número del ejercicio en el libro.

## Ejercicio 1 · Operar en forma binómica
> [!question] Enunciado (3 y Ejemplo 7.3)
> Calcula: a) $\dfrac1{1+i}+\dfrac1{1-i}$  b) $\dfrac{2+i}{1-i}$  c) $i^{2026}$

> [!success]- Solución
> a) $\frac{1-i}2+\frac{1+i}2=1$.
> b) $\frac{(2+i)(1+i)}{(1-i)(1+i)}=\frac{2+3i+i^2}2=\frac{1+3i}2$.
> c) $2026=4\cdot506+2$, luego $i^{2026}=i^2=-1$.

Repasa: [[Forma binómica y conjugado]], [[Números complejos]]

## Ejercicio 2 · Un cociente que es real
> [!question] Enunciado (4)
> Si $|z|=|z'|=1$ y $zz'\neq-1$, prueba que $w=\dfrac{z+z'}{1+zz'}$ es real.

> [!success]- Solución
> Si $|z|=1$, entonces $\bar z=\frac1z$. Así
> $$\bar w=\frac{\bar z+\bar z'}{1+\bar z\bar z'}=\frac{\frac1z+\frac1{z'}}{1+\frac1{zz'}}=\frac{\frac{z'+z}{zz'}}{\frac{zz'+1}{zz'}}=\frac{z+z'}{1+zz'}=w.$$
> Y $w=\bar w\iff w\in\mathbb R$.

Repasa: [[Forma binómica y conjugado]], [[Módulo y argumento]]

## Ejercicio 3 · z² = z̄
> [!question] Enunciado (5)
> Resuelve $z^2=\bar z$.

> [!success]- Solución
> Tomando módulos: $|z|^2=|z|$, luego $|z|=0$ o $|z|=1$.
> - $z=0$ es solución.
> - Si $|z|=1$: $\bar z=\frac1z$, y la ecuación es $z^3=1$: las [[Raíces de la unidad|raíces cúbicas de la unidad]].
>
> Soluciones: $0,\ 1,\ -\frac12+i\frac{\sqrt3}2,\ -\frac12-i\frac{\sqrt3}2$.

## Ejercicio 4 · Ecuaciones
> [!question] Enunciado (6)
> Resuelve: a) $z^{10}+2z^5+1=0$  b) $z^2+2(1+i)z-5(1+2i)=0$

> [!success]- Solución
> a) Es $(z^5+1)^2=0$, o sea $z^5=-1=e^{i\pi}$: $z=e^{i\frac{\pi+2k\pi}5}$, $k=0,\dots,4$ (cada una **doble**).
> b) $\Delta=4(1+i)^2+20(1+2i)=8i+20+40i=20+48i$.
> Raíz de $\Delta$: $x^2-y^2=20$, $x^2+y^2=|\Delta|=52$ ⇒ $x^2=36$, $y^2=16$, $xy=24>0$: $\varepsilon=6+4i$.
> $z=\frac{-2(1+i)\pm(6+4i)}2$: $\boxed{z_1=2+i,\ z_2=-4-3i}$.
> Comprobación con Vieta: $z_1+z_2=-2-2i=-2(1+i)$ ✓.

Repasa: [[Ecuación de segundo grado en C]], [[Raíces n-ésimas de un complejo]]

## Ejercicio 5 · Coseno de 5α y de π entre 10
> [!question] Enunciado (10)
> Expresa $\cos5\alpha$ en función de $\cos\alpha$ y $\sin\alpha$. Deduce $\cos\frac\pi{10}$.

> [!success]- Solución
> Por [[Fórmula de De Moivre|De Moivre]] y el binomio, la parte real de $(\cos\alpha+i\sin\alpha)^5$ es
> $$\cos5\alpha=\cos^5\alpha-10\cos^3\alpha\sin^2\alpha+5\cos\alpha\sin^4\alpha.$$
> Con $\alpha=\frac\pi{10}$: $\cos5\alpha=\cos\frac\pi2=0$. Dividiendo por $\cos\alpha\neq0$ y llamando $c=\cos^2\alpha$ ($\sin^2\alpha=1-c$):
> $$c^2-10c(1-c)+5(1-c)^2=0\iff16c^2-20c+5=0\iff c=\frac{5\pm\sqrt5}8.$$
> Como $\cos\frac\pi{10}$ es cercano a 1, se toma el signo $+$: $\cos\frac\pi{10}=\sqrt{\dfrac{5+\sqrt5}8}=\dfrac{\sqrt{10+2\sqrt5}}4\approx0{,}951$.

## Ejercicio 6 · Raíces de la unidad: suma y producto
> [!question] Enunciado (12 y 13)
> a) Prueba que $(U_n,\cdot)\cong(\mathbb Z/n,+)$. b) Halla la suma y el producto de las raíces $n$-ésimas de la unidad.

> [!success]- Solución
> a) $\bar k\mapsto z_1^k$ ($z_1=e^{2\pi i/n}$) está bien definida y es inyectiva porque $z_1^k=1\iff n\mid k$; es sobreyectiva porque $z_k=z_1^k$; y $z_1^{k+l}=z_1^kz_1^l$.
> b) Suma ($n\ge2$): $\sum_{k=0}^{n-1}z_1^k=\frac{1-z_1^n}{1-z_1}=0$.
> Producto: $\prod z_1^k=z_1^{0+1+\cdots+(n-1)}=e^{\frac{2\pi i}n\cdot\frac{n(n-1)}2}=e^{i\pi(n-1)}=(-1)^{n-1}$.

Repasa: [[Raíces de la unidad]]

## Ejercicio 7 · Identidad del paralelogramo
> [!question] Enunciado (8)
> Prueba $|z+z'|^2+|z-z'|^2=2(|z|^2+|z'|^2)$ e interprétala.

> [!success]- Solución
> $|z\pm z'|^2=(z\pm z')(\bar z\pm\bar z')=|z|^2\pm2\operatorname{Re}(z\bar z')+|z'|^2$. Sumando, los términos con $\pm$ se cancelan.
> **Interpretación:** en un paralelogramo de lados $z,z'$, las diagonales son $z+z'$ y $z-z'$: **la suma de los cuadrados de las diagonales es la suma de los cuadrados de los cuatro lados**.

Repasa: [[Módulo y argumento]], [[Aplicaciones geométricas de los complejos]]

## Ejercicio 8 · ¿Raíces reales?
> [!question] Enunciado (17)
> A cada punto $(b,c)$ del plano se le asocia $z^2-2bz+c=0$. ¿Para qué puntos las raíces no son reales? ¿Reales distintas? ¿Iguales?

> [!success]- Solución
> $\Delta=4(b^2-c)$.
> - No reales: $c>b^2$ (por **encima** de la parábola $c=b^2$).
> - Reales distintas: $c<b^2$ (por debajo).
> - Iguales: $c=b^2$ (sobre la parábola).

## Ejercicio 9 · Enteros de Gauss
> [!question] Enunciado (18)
> $\mathbb Z[i]=\{a+ib\mid a,b\in\mathbb Z\}$. a) Prueba que es un anillo. b) Halla sus elementos inversibles.

> [!success]- Solución
> a) Es [[Subanillo]] de $\mathbb C$: contiene a 1, y es cerrado para restas y productos ($(a+ib)(c+id)=(ac-bd)+i(ad+bc)$).
> b) Si $zw=1$, tomando módulos al cuadrado: $|z|^2|w|^2=1$ con $|z|^2=a^2+b^2\in\mathbb N$. Luego $a^2+b^2=1$: $z\in\{1,-1,i,-i\}$. Forman un grupo ($=U_4$).

## Ejercicio 10 · Raíces conjugadas
> [!question] Enunciado (19)
> Si $p$ tiene coeficientes reales y $p(z_1)=0$, prueba que $p(\bar z_1)=0$.

> [!success]- Solución
> $p(\bar z_1)=\sum a_k\bar z_1^k=\sum\overline{a_kz_1^k}=\overline{p(z_1)}=\bar0=0$ (se usa $\bar a_k=a_k$ porque son reales). Consecuencia en [[Teorema fundamental del álgebra]].
