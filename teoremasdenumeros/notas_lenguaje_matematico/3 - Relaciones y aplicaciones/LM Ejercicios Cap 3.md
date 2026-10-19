---
tipo: ejercicios
tags: [ejercicios, relaciones, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Ejercicios propuestos · pp. 115-119"
---
# Ejercicios · Cap 3 · Relaciones y aplicaciones

> [!tip] Cómo usar esta nota
> Intenta cada ejercicio en papel antes de desplegar la solución. Entre paréntesis, el número del ejercicio en el libro.

## Ejercicio 1 · Propiedades de relaciones
> [!question] Enunciado (1)
> En $\mathbb N^*$, estudia si son reflexivas, simétricas, antisimétricas o transitivas:
> a) $x\neq y$  b) $x+y=20$  c) $x-y=1$  d) $x\mid y$  e) $xy$ es un cuadrado perfecto

> [!success]- Solución
> | | Refl. | Sim. | Antisim. | Trans. |
> |---|:-:|:-:|:-:|:-:|
> | a) $x\neq y$ | ✗ ($1\neq1$ es falso) | ✓ | ✗ ($1\neq2$, $2\neq1$) | ✗ ($1\neq2\neq1$ pero $1=1$) |
> | b) $x+y=20$ | ✗ ($1+1\neq20$) | ✓ | ✗ ($1,19$) | ✗ ($1\mathcal R19\mathcal R1$, pero $1\not\mathcal R1$) |
> | c) $x-y=1$ | ✗ | ✗ | ✓ (por vacuidad) | ✗ ($3\mathcal R2\mathcal R1$, $3-1=2$) |
> | d) $x\mid y$ | ✓ | ✗ | ✓ | ✓ → **orden parcial** |
> | e) $xy=\square$ | ✓ ($x\cdot x=x^2$) | ✓ | ✗ ($1\cdot4=4$) | ✓ → **equivalencia** |
>
> Transitividad de e): si $xy=a^2$ e $yz=b^2$, entonces $xz\,y^2=a^2b^2$, luego $xz=\left(\frac{ab}{y}\right)^2$. Un entero que es cuadrado de un racional es cuadrado de un entero, así que $xz$ es un cuadrado. Las clases agrupan los números con la misma "parte libre de cuadrados" ($2\sim8\sim18\sim\dots$).

Repasa: [[Propiedades de una relación]]

## Ejercicio 2 · Una relación de equivalencia
> [!question] Enunciado (3)
> En $\mathbb R^*$ se define $x\,\mathcal E\,y\iff xy>0$. Prueba que es de equivalencia y halla el cociente.

> [!success]- Solución
> - Reflexiva: $x\cdot x=x^2>0$ porque $x\neq0$.
> - Simétrica: $xy=yx$.
> - Transitiva: si $xy>0$ e $yz>0$, entonces $(xy)(yz)=xz\,y^2>0$ y como $y^2>0$, $xz>0$.
>
> $xy>0$ significa "mismo signo". Hay dos clases: $[1]=(0,\infty)$ y $[-1]=(-\infty,0)$. $\ \mathbb R^*/\mathcal E=\{[1],[-1]\}$.

Repasa: [[Relación de equivalencia]], [[Conjunto cociente]]

## Ejercicio 3 · Cotas en el plano
> [!question] Enunciado (Ejercicio 3.35 del texto)
> $A=\{(x,y)\in\mathbb R^2\mid x\ge0,\ y\ge0,\ x+y\le1\}$ (triángulo). Halla cotas, supremo, ínfimo, máximo, mínimo, maximales y minimales con el orden lexicográfico y con el orden producto.

> [!success]- Solución
> **Lexicográfico** (orden total):
> - Cotas superiores: puntos con $x>1$, o $(1,y)$ con $y\ge0$. $\ \sup=(1,0)\in A$ ⇒ $\max=(1,0)$.
> - Cotas inferiores: $x<0$, o $(0,y)$ con $y\le0$. $\ \inf=(0,0)\in A$ ⇒ $\min=(0,0)$.
> - Maximal = máximo, minimal = mínimo (orden total).
>
> **Producto** (orden parcial):
> - Cotas superiores: $\{(a,b)\mid a\ge1,\ b\ge1\}$. $\ \sup=(1,1)\notin A$ ⇒ **no hay máximo**.
> - **Maximales:** todos los puntos de la hipotenusa $x+y=1$.
> - $\inf=\min=(0,0)$, único minimal.

Repasa: [[Orden lexicográfico y orden producto]], [[Supremo e ínfimo]], [[Elementos maximales y minimales]]

## Ejercicio 4 · Relaciones entre sucesiones
> [!question] Enunciado (11)
> En las sucesiones reales: a) $(a_n)\preceq(b_n)$ si $a_n\le b_n$ salvo para un número finito de $n$. b) $(a_n)\sim(b_n)$ si $a_n=b_n$ salvo para un número finito de $n$. c) $a_n\le b_n$ para todo $n$. ¿Orden o equivalencia?

> [!success]- Solución
> a) Reflexiva y transitiva (la unión de dos conjuntos finitos de excepciones es finita), pero **no antisimétrica**: $(0,0,0,\dots)$ y $(1,0,0,\dots)$ se relacionan en los dos sentidos y son distintas. **Ni orden ni equivalencia.**
> b) **Equivalencia.** Cada clase es "el comportamiento final" de la sucesión: dos sucesiones son equivalentes si a partir de un momento coinciden.
> c) **Orden parcial** (el orden producto con infinitas coordenadas).

## Ejercicio 5 · Ejemplos de aplicaciones en ℕ
> [!question] Enunciado (13)
> Da una aplicación $\mathbb N\to\mathbb N$: a) inyectiva no sobreyectiva; b) sobreyectiva no inyectiva; c) ni una ni otra; d) biyectiva distinta de la identidad.

> [!success]- Solución
> a) $n\mapsto n+1$ (el 0 no se alcanza). También $n\mapsto2n$.
> b) $n\mapsto\lfloor n/2\rfloor$ ($0,0,1,1,2,2,\dots$).
> c) $n\mapsto0$.
> d) Intercambiar 0 y 1 y dejar el resto fijo.
>
> **Fíjate:** en conjuntos **finitos** del mismo tamaño, inyectiva ⇔ sobreyectiva. En $\mathbb N$ **no**: es una característica de los [[Conjunto infinito|conjuntos infinitos]].

Repasa: [[Aplicación inyectiva]], [[Aplicación sobreyectiva]]

## Ejercicio 6 · Composición e inyectividad
> [!question] Enunciado (20)
> Sean $f:A\to B$, $g:B\to C$. ¿Verdadero o falso?
> a) $g\circ f$ inyectiva ⇒ $f$ inyectiva  b) $g\circ f$ inyectiva ⇒ $g$ inyectiva
> c) $g\circ f$ sobreyectiva ⇒ $f$ sobreyectiva  d) $g\circ f$ sobreyectiva ⇒ $g$ sobreyectiva

> [!success]- Solución
> a) **V.** Si $f(x)=f(y)$, entonces $g(f(x))=g(f(y))$, y como $g\circ f$ es inyectiva, $x=y$.
> d) **V.** Dado $z\in C$, existe $x$ con $g(f(x))=z$; luego $y=f(x)$ cumple $g(y)=z$.
> b) y c) **F.** Contraejemplo: $A=C=\{1\}$, $B=\{1,2\}$, $f(1)=1$, $g(1)=g(2)=1$. Entonces $g\circ f=I_A$ es biyectiva, pero $g$ no es inyectiva y $f$ no es sobreyectiva.
>
> **Regla:** la de dentro hereda la inyectividad; la de fuera, la sobreyectividad.

Repasa: [[Composición de aplicaciones]], [[Aplicación inyectiva]], [[Aplicación sobreyectiva]]

## Ejercicio 7 · Imagen y antiimagen
> [!question] Enunciado (21)
> $f:A\to B$, $C,D\subseteq A$, $E,F\subseteq B$. ¿Son ciertas?
> a) $f(C\cup D)=f(C)\cup f(D)$  b) $f(C\cap D)=f(C)\cap f(D)$  c) $f^{-1}(E\cap F)=f^{-1}(E)\cap f^{-1}(F)$

> [!success]- Solución
> a) **Sí.** $y\in f(C\cup D)\iff\exists x\in C\cup D,\ f(x)=y\iff(\exists x\in C,\dots)\lor(\exists x\in D,\dots)\iff y\in f(C)\cup f(D)$.
> b) **Solo $\subseteq$.** Falla con $f(x)=x^2$, $C=\{-1\}$, $D=\{1\}$. Es igualdad si $f$ es inyectiva.
> c) **Sí.** $x\in f^{-1}(E\cap F)\iff f(x)\in E\land f(x)\in F\iff x\in f^{-1}(E)\cap f^{-1}(F)$.

Repasa: [[Imagen y antiimagen]]

## Ejercicio 8 · Una potencia que es la identidad
> [!question] Enunciado (17)
> Si $f:A\to A$ cumple $f^n=I_A$ para algún $n\ge1$, prueba que $f$ es biyectiva.

> [!success]- Solución
> $f\circ f^{n-1}=f^n=I_A$ y $f^{n-1}\circ f=f^n=I_A$. Por el [[Aplicación inversa|Teorema 3.59]], $f$ es biyectiva con $f^{-1}=f^{n-1}$.
> (Si $n=1$, $f=I_A$ y $f^0=I_A$.)

## Ejercicio 9 · Partes y biyecciones
> [!question] Enunciado (19)
> a) Da una inyección $U\to\mathcal P(U)$. b) Da una sobreyección $\mathcal P(U)\to U$ ($U\neq\emptyset$). c) ¿Son equipotentes $U$ y $\mathcal P(U)$?

> [!success]- Solución
> a) $x\mapsto\{x\}$.
> b) Fija $u_0\in U$. $A\mapsto a$ si $A=\{a\}$ es unitario, y $A\mapsto u_0$ en otro caso.
> c) **No**, nunca: es el [[Teorema de Cantor]].

## Ejercicio 10 · Propiedades que se conservan
> [!question] Enunciado (2)
> Sean $\mathcal R,\mathcal S$ relaciones en $A$. ¿Verdadero o falso?
> a) $\mathcal R,\mathcal S$ transitivas ⇒ $\mathcal R\cup\mathcal S$ transitiva
> b) $\mathcal R,\mathcal S$ transitivas ⇒ $\mathcal R\cap\mathcal S$ transitiva
> c) $\mathcal R,\mathcal S$ antisimétricas ⇒ $\mathcal R\cup\mathcal S$ antisimétrica
> d) $\mathcal R$ simétrica ⇒ $\mathcal R^{-1}$ simétrica

> [!success]- Solución
> a) **F.** $\mathcal R=\{(1,2)\}$, $\mathcal S=\{(2,3)\}$: la unión tiene $(1,2),(2,3)$ pero no $(1,3)$.
> b) **V.** Si $(x,y),(y,z)\in\mathcal R\cap\mathcal S$, están en ambas, y por transitividad $(x,z)$ está en ambas.
> c) **F.** $\mathcal R=\{(1,2)\}$, $\mathcal S=\{(2,1)\}$.
> d) **V.** Si $\mathcal R$ es simétrica, $\mathcal R^{-1}=\mathcal R$.

Repasa: [[Propiedades de una relación]]
