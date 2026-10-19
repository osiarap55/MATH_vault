---
tipo: ejercicios
tags: [ejercicios, racionales, reales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Ejercicios propuestos · pp. 236-239"
---
# Ejercicios · Cap 6 · Racionales y reales

> [!tip] Cómo usar esta nota
> Intenta cada ejercicio en papel antes de desplegar la solución. Entre paréntesis, el número del ejercicio en el libro.

## Ejercicio 1 · ¿Es decimal?
> [!question] Enunciado (2)
> Prueba que $\frac1n+\frac1{n+1}+\frac1{n+2}$ no es un número decimal ($n\ge1$).

> [!success]- Solución
> La suma es $\dfrac{3n^2+6n+2}{n(n+1)(n+2)}$. Entre $n,n+1,n+2$ uno es múltiplo de 3, así que **3 divide al denominador**. El numerador es $\equiv2\pmod3$, luego **3 no lo divide**: al simplificar, el 3 sigue en el denominador. Una fracción irreducible es decimal solo si su denominador es $2^a5^b$. No es decimal.

Repasa: [[Expresión decimal]]

## Ejercicio 2 · Desigualdades
> [!question] Enunciado (6)
> Resuelve: a) $|x+1|<2$  b) $|x|>|x+1|$  c) $|x+2|+|x-2|<12$  d) $x<x^2-12<4x$  e) $\big||x+1|-|x-1|\big|<1$

> [!success]- Solución
> a) $-2<x+1<2\iff x\in(-3,1)$.
> b) Elevando al cuadrado (ambos lados $\ge0$): $x^2>x^2+2x+1\iff x<-\frac12$.
> c) Por casos (ver [[Valor absoluto]]): $(-6,6)$.
> d) $x^2-x-12>0\iff(x-4)(x+3)>0\iff x<-3$ o $x>4$. $x^2-4x-12<0\iff(x-6)(x+2)<0\iff-2<x<6$. Intersección: $(4,6)$.
> e) Si $x\ge1$ o $x\le-1$, la expresión vale 2. Si $-1\le x\le1$, vale $|2x|$, y $|2x|<1\iff|x|<\frac12$. Solución: $\left(-\frac12,\frac12\right)$.

Repasa: [[Valor absoluto]]

## Ejercicio 3 · Supremos e ínfimos
> [!question] Enunciado (7)
> Halla supremo e ínfimo (¿máximo, mínimo?) de: a) $\{x^2\mid-2<x<1\}$  b) $\{x\mid x^2-x+4<0\}$  c) $\left\{\frac{n+1}n\mid n\ge1\right\}$

> [!success]- Solución
> a) El conjunto es $[0,4)$: $\inf=\min=0$, $\sup=4$ (no es máximo: $x^2=4$ exige $x=\pm2$, excluidos).
> b) El discriminante es $1-16<0$, así que $x^2-x+4>0$ siempre: el conjunto es **vacío** (no tiene supremo en $\mathbb R$; por convenio $\sup\emptyset=-\infty$).
> c) $\frac{n+1}n=1+\frac1n$: $\sup=\max=2$ ($n=1$), $\inf=1$ (no es mínimo; usa la [[Propiedad arquimediana]]).

Repasa: [[Supremo e ínfimo]]

## Ejercicio 4 · Decimales periódicos
> [!question] Enunciado (9 y 10)
> a) Escribe $\frac17$ y $\frac76$ en decimal. b) Halla la fracción de $1{,}\overline2$ y $1{,}\overline{21}$.

> [!success]- Solución
> a) $\frac17=0{,}\overline{142857}$; $\frac76=1{,}1\overline6$.
> b) $x=1{,}\overline2$: $10x-x=12{,}\overline2-1{,}\overline2=11\Rightarrow x=\frac{11}9$.
> $x=1{,}\overline{21}$: $100x-x=120\Rightarrow x=\frac{120}{99}=\frac{40}{33}$.

Repasa: [[Expresión decimal]]

## Ejercicio 5 · sup A ≤ inf B
> [!question] Enunciado (11)
> $A,B\subseteq\mathbb R$ no vacíos con $a\le b$ para todo $a\in A$, $b\in B$. Prueba que $\sup A\le\inf B$. ¿Pueden ser distintos? ¿Iguales?

> [!success]- Solución
> Cada $b\in B$ es cota superior de $A$, luego existe $\sup A$ y $\sup A\le b$. Entonces $\sup A$ es cota inferior de $B$, luego $\sup A\le\inf B$.
> Pueden ser iguales ($A=(0,1)$, $B=(1,2)$: ambos valen 1) o distintos ($A=[0,1]$, $B=[2,3]$).

Repasa: [[Supremo e ínfimo]]

## Ejercicio 6 · Supremo de una suma
> [!question] Enunciado (12)
> Si $A,B$ están acotados superiormente, prueba $\sup(A+B)=\sup A+\sup B$, donde $A+B=\{a+b\}$.

> [!success]- Solución
> Sean $\alpha=\sup A$, $\beta=\sup B$.
> - **Cota:** $a+b\le\alpha+\beta$.
> - **La menor:** dado $\varepsilon>0$, hay $a>\alpha-\frac\varepsilon2$ y $b>\beta-\frac\varepsilon2$, así $a+b>\alpha+\beta-\varepsilon$. Ninguna cota es menor que $\alpha+\beta$.
> (Se usa la caracterización con $\varepsilon$ de [[Supremo e ínfimo]].)

## Ejercicio 7 · Un cuerpo intermedio
> [!question] Enunciado (15)
> Prueba que $K=\{a+b\sqrt2\mid a,b\in\mathbb Q\}$ es un cuerpo.

> [!success]- Solución
> Es subanillo de $\mathbb R$: cerrado para restas y productos ($(a+b\sqrt2)(c+d\sqrt2)=(ac+2bd)+(ad+bc)\sqrt2$) y contiene a 1.
> **Inversos:** si $a+b\sqrt2\neq0$, entonces $a^2-2b^2\neq0$ (si no, $\sqrt2=\pm\frac ab$ sería racional), y
> $$\frac1{a+b\sqrt2}=\frac{a-b\sqrt2}{a^2-2b^2}\in K.$$
> Por la Prop. 4.34, es un subcuerpo de $\mathbb R$.

Repasa: [[Cuerpo]], [[Irracionalidad de raíz de 2]]

## Ejercicio 8 · Intervalos equipotentes
> [!question] Enunciado (16, 17, 18)
> a) Prueba que $(0,1]\simeq[0,1]$. b) Prueba que $f(x)=\frac{x}{1-|x|}$ es una biyección $(-1,1)\to\mathbb R$.

> [!success]- Solución
> a) "Hotel de Hilbert": $f:[0,1]\to(0,1]$ con $f(0)=1$, $f\!\left(\frac1n\right)=\frac1{n+1}$ y $f(x)=x$ en el resto. Es biyectiva (desplaza la sucesión $1,\frac12,\frac13,\dots$ un lugar para hacer sitio al 0).
> O con [[Teorema de Cantor-Bernstein]]: inclusión $(0,1]\hookrightarrow[0,1]$ y $x\mapsto\frac{x+1}2$ de $[0,1]$ en $(0,1]$.
> b) La inversa es $g(y)=\frac{y}{1+|y|}$: se comprueba $f(g(y))=y$ y $g(f(x))=x$. **$\mathbb R$ es equipotente a un intervalo acotado.**

Repasa: [[Conjuntos equipotentes]], [[Aplicación inversa]]

## Ejercicio 9 · Algebraicos numerables
> [!question] Enunciado (20)
> Prueba que los algebraicos son numerables y los trascendentes no.

> [!success]- Solución
> Ver [[Números algebraicos y trascendentes]].
