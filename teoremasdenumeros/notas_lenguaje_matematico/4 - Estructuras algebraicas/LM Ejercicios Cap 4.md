---
tipo: ejercicios
tags: [ejercicios, algebra]
capitulo: "[[LM Cap 4 - Operaciones y estructuras algebraicas]]"
ref: "Ejercicios propuestos · pp. 154-157"
---
# Ejercicios · Cap 4 · Estructuras algebraicas

> [!tip] Cómo usar esta nota
> Intenta cada ejercicio en papel antes de desplegar la solución. Entre paréntesis, el número del ejercicio en el libro.

## Ejercicio 1 · Grupo de tres elementos
> [!question] Enunciado (1)
> Completa la tabla de un grupo $G=\{e,a,b\}$ con neutro $e$. ¿Cuántas soluciones hay?

> [!success]- Solución
> Fila y columna de $e$ son fáciles. En cada fila y columna cada elemento aparece **una sola vez** (las ecuaciones $x*y=z$ tienen solución única).
> - Si $a*a=e$, entonces la fila de $a$ sería $a,e,?$ y el $?$ tendría que ser $b$: $a*b=b$, que obliga a $a=e$. Imposible. Luego **$a*a=b$**.
> - Entonces $a*b=e$ y $b*b=a$.
>
> | $*$ | $e$ | $a$ | $b$ |
> |---|---|---|---|
> | $e$ | $e$ | $a$ | $b$ |
> | $a$ | $a$ | $b$ | $e$ |
> | $b$ | $b$ | $e$ | $a$ |
>
> **Una única solución**: es el grupo cíclico de orden 3 (igual que $\mathbb Z/3$ con $+$).

Repasa: [[Grupo]]

## Ejercicio 2 · Intersección de subgrupos
> [!question] Enunciado (2)
> Si $H_1,H_2$ son subgrupos de $G$, prueba que $H_1\cap H_2$ es subgrupo. ¿Y $H_1\cup H_2$?

> [!success]- Solución
> No es vacío ($e$ está en ambos). Si $a,b\in H_1\cap H_2$, entonces $a*b^{-1}\in H_1$ y $a*b^{-1}\in H_2$ (cada uno es subgrupo). Por el criterio, es subgrupo.
> La unión **no**: $2\mathbb Z\cup3\mathbb Z$ contiene $2$ y $3$ pero no $2+3=5$.

Repasa: [[Subgrupo]]

## Ejercicio 3 · El cociente es un grupo
> [!question] Enunciado (3)
> $(G,*)$ abeliano, $H$ subgrupo. a) Si $a\,\mathcal R_H\,a'$ y $b\,\mathcal R_H\,b'$, prueba que $a*b\ \mathcal R_H\ a'*b'$. b) Deduce que $[a]*[b]=[a*b]$ hace de $G/H$ un grupo.

> [!success]- Solución
> a) $(a*b)*(a'*b')^{-1}=a*b*b'^{-1}*a'^{-1}=(a*a'^{-1})*(b*b'^{-1})\in H$ (se usa que $G$ es **abeliano** para reordenar, y que $H$ es cerrado).
> b) Por a), $[a]*[b]$ **no depende de los representantes**: está bien definida. La asociativa se hereda de $G$, el neutro es $[e]$ y el simétrico de $[a]$ es $[a^{-1}]$.

Repasa: [[Teorema de Lagrange]], [[Conjunto cociente]]

## Ejercicio 4 · El grupo afín
> [!question] Enunciado (6)
> En $\mathbb R^2$: $(a,b)*(a',b')=(aa',\,ab'+b)$. Sea $G=\{(a,b)\mid a\neq0\}$.
> a) ¿Es $(\mathbb R^2,*)$ un grupo? b) Prueba que $(G,*)$ es grupo. ¿Es abeliano? c) ¿Son subgrupos $H=\{a>0\}$, $F=\{a=1\}$, $J=\{a,b\in\mathbb Z,\ a\neq0\}$?

> [!success]- Solución
> **Idea:** $(a,b)$ representa la función $f_{ab}(x)=ax+b$, y $*$ es la **composición**: $f_{ab}\circ f_{a'b'}(x)=a(a'x+b')+b=aa'x+(ab'+b)$.
> a) **No:** $(0,b)$ no tiene simétrico (una función constante no es invertible).
> b) Neutro $(1,0)$ (la identidad). Simétrico de $(a,b)$: $\left(\frac1a,-\frac ba\right)$. Comprueba: $(a,b)*\left(\frac1a,-\frac ba\right)=\left(1,\,a\cdot(-\frac ba)+b\right)=(1,0)$. Asociativa: la composición lo es.
> **No abeliano:** $(2,0)*(1,1)=(2,2)$ pero $(1,1)*(2,0)=(2,1)$.
> c) $H$ sí, $F$ sí (las traslaciones). $J$ **no**: el simétrico de $(2,0)$ es $(\frac12,0)\notin J$.

Repasa: [[Grupo]], [[Subgrupo]], [[Composición de aplicaciones]]

## Ejercicio 5 · Z-n es cuerpo si y sólo si n es primo
> [!question] Enunciado (11)
> Prueba que $(\mathbb Z/n,+,\cdot)$ es un cuerpo si y sólo si $n$ es primo.

> [!success]- Solución
> **(⇒)** Si $n$ no es primo, $n=rs$ con $1<r,s<n$. Entonces $\bar r\neq\bar0$, $\bar s\neq\bar0$ y $\bar r\cdot\bar s=\bar n=\bar0$: **divisores de cero**. Un cuerpo no tiene ([[Dominio de integridad]]).
> **(⇐)** Sea $n=p$ primo y $\bar a\neq\bar0$, es decir, $p\nmid a$. Entonces $\operatorname{mcd}(a,p)=1$ y por [[Identidad de Bézout|Bézout]] existen $x,y$ con $ax+py=1$. Tomando clases: $\bar a\,\bar x=\bar1$. Todo no nulo tiene inverso.
> (Otra vía: $\mathbb Z/p$ es íntegro por el [[Lema de Euclides]] y finito; aplica el ejercicio 6.)

Repasa: [[Cuerpo]], [[Congruencia módulo n]]

## Ejercicio 6 · Íntegro y finito implica cuerpo
> [!question] Enunciado (12)
> Prueba que un anillo conmutativo unitario íntegro **finito** es un cuerpo.

> [!success]- Solución
> Sea $a\neq0$ y $\varphi(x)=ax$.
> - $\varphi$ es **inyectiva**: $ax=ay\Rightarrow a(x-y)=0\Rightarrow x=y$ (íntegro).
> - Una inyección de un conjunto **finito** en sí mismo es **biyectiva** (ver [[Conjunto finito]]).
> - Luego existe $x$ con $ax=1$: $a$ es inversible.

Repasa: [[Dominio de integridad]], [[Aplicación inyectiva]]

## Ejercicio 7 · Un anillo con divisores de cero
> [!question] Enunciado (13)
> En $\mathbb R^2$: $(a,b)+(a',b')=(a+a',b+b')$, $(a,b)*(a',b')=(aa',\,ab'+ba')$. Prueba que es un anillo conmutativo unitario **no íntegro**.

> [!success]- Solución
> Conmutativo: la fórmula es simétrica. Unidad: $(a,b)*(1,0)=(a,b)$. La asociativa y distributiva se comprueban operando.
> **No íntegro:** $(0,1)*(0,1)=(0,\,0+0)=(0,0)$ con $(0,1)\neq(0,0)$.
> (Son los "números duales" $a+b\varepsilon$ con $\varepsilon^2=0$.)

Repasa: [[Anillo]], [[Dominio de integridad]]

## Ejercicio 8 · Desigualdades con valor absoluto
> [!question] Enunciado (15, 16, 18)
> En un anillo/cuerpo totalmente ordenado, prueba:
> a) $\big||a|-|b|\big|\le|a-b|$  b) $2\max(a,b)=a+b+|a-b|$  c) $|ab|\le a^2+b^2$

> [!success]- Solución
> a) $|a|=|(a-b)+b|\le|a-b|+|b|$, luego $|a|-|b|\le|a-b|$. Cambiando papeles, $|b|-|a|\le|a-b|$. Las dos juntas dan el resultado.
> b) Si $a\ge b$: $a+b+(a-b)=2a=2\max$. Si $a<b$: $a+b+(b-a)=2b$. (Igual, $2\min(a,b)=a+b-|a-b|$.)
> c) $(a+b)^2\ge0\Rightarrow a^2+b^2\ge-2ab$ y $(a-b)^2\ge0\Rightarrow a^2+b^2\ge2ab$. Luego $a^2+b^2\ge2|ab|\ge|ab|$.

Repasa: [[Cuerpo ordenado]], [[Valor absoluto]]

## Ejercicio 9 · Sumas de combinatorios
> [!question] Enunciado (19)
> Prueba $\sum_{k=0}^n\binom nk=2^n$ y $\sum_{k=0}^n(-1)^k\binom nk=0$.

> [!success]- Solución
> [[Binomio de Newton]] con $a=b=1$: $(1+1)^n=2^n$. Con $a=1$, $b=-1$: $(1-1)^n=0$ (para $n\ge1$).

## Ejercicio 10 · Homomorfismo y conmutatividad
> [!question] Enunciado (5)
> En un grupo $(G,+)$, sea $f(a)=2a=a+a$. Prueba que $f$ es homomorfismo $\iff G$ es abeliano.

> [!success]- Solución
> $f(a+b)=a+b+a+b$ y $f(a)+f(b)=a+a+b+b$. Son iguales $\iff a+b+a+b=a+a+b+b$. Cancelando $a$ por la izquierda y $b$ por la derecha: $\iff b+a=a+b$.

Repasa: [[Homomorfismo]], [[Grupo]]
