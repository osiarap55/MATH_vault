---
tipo: ejercicios
tags: [ejercicios, naturales, enteros]
capitulo: "[[LM Cap 5 - Números naturales y enteros]]"
ref: "Ejercicios propuestos · pp. 203-205"
---
# Ejercicios · Cap 5 · Naturales y enteros

> [!tip] Cómo usar esta nota
> Intenta cada ejercicio en papel antes de desplegar la solución. Entre paréntesis, el número del ejercicio en el libro.

## Ejercicio 1 · Inducción: sumas clásicas
> [!question] Enunciado (2, 3, 5, 7)
> Demuestra por inducción ($n\ge1$):
> a) $1+2+\cdots+n=\frac{n(n+1)}2$  b) $1+3+\cdots+(2n-1)=n^2$  c) $1^2+\cdots+n^2=\frac{n(n+1)(2n+1)}6$  d) $1+2+\cdots+2^n=2^{n+1}-1$ ($n\ge0$)

> [!success]- Solución
> Esquema común: **base** + **paso** $S_{n+1}=S_n+(\text{término }n+1)$, usando la hipótesis.
> a) Base $1=\frac{1\cdot2}2$. Paso: $\frac{n(n+1)}2+(n+1)=\frac{(n+1)(n+2)}2$.
> b) Base $1=1^2$. Paso: $n^2+(2n+1)=(n+1)^2$.
> c) Base $1=\frac{1\cdot2\cdot3}6$. Paso: $\frac{n(n+1)(2n+1)}6+(n+1)^2=\frac{(n+1)[n(2n+1)+6(n+1)]}6=\frac{(n+1)(2n^2+7n+6)}6=\frac{(n+1)(n+2)(2n+3)}6$.
> d) Base $1=2^1-1$. Paso: $2^{n+1}-1+2^{n+1}=2^{n+2}-1$.

Repasa: [[Principio de inducción]]

## Ejercicio 2 · Inducción con factoriales
> [!question] Enunciado (8 y 6)
> a) $\sum_{k=1}^nk\cdot k!=(n+1)!-1$  b) $1^3+2^3+\cdots+n^3=(1+2+\cdots+n)^2$

> [!success]- Solución
> a) Base $1\cdot1!=1=2!-1$. Paso: $(n+1)!-1+(n+1)(n+1)!=(n+1)!(1+n+1)-1=(n+2)!-1$.
> b) Por el ejercicio 1a, hay que ver $\sum k^3=\frac{n^2(n+1)^2}4$. Paso: $\frac{n^2(n+1)^2}4+(n+1)^3=\frac{(n+1)^2(n^2+4n+4)}4=\frac{(n+1)^2(n+2)^2}4$.

## Ejercicio 3 · Una operación nueva en ℕ
> [!question] Enunciado (1)
> En $\mathbb N$: $a*b=a+b+ab$. ¿Conmutativa, asociativa, neutro, simétricos? Halla una fórmula para $a^{(n)}=a*\cdots*a$.

> [!success]- Solución
> **Truco:** $a*b+1=(a+1)(b+1)$. Es decir, $a*b$ es el producto "trasladado una unidad".
> - Conmutativa y asociativa (las hereda del producto): $(a*b)*c+1=(a+1)(b+1)(c+1)$.
> - Neutro: $0$ ($a*0=a$).
> - Simétrico: $a*b=0\Rightarrow a+b+ab=0\Rightarrow a=b=0$. **Solo el 0** tiene simétrico.
> - $a^{(n)}=(a+1)^n-1$. Para que $a^{(m)}*a^{(n)}=a^{(m+n)}$ valga con $n=0$, hay que poner $a^{(0)}=0$.

Repasa: [[Operación interna]], [[Elemento neutro y simétrico]]

## Ejercicio 4 · Contar aplicaciones sobreyectivas
> [!question] Enunciado (10 y 11)
> a) ¿Cuántas aplicaciones sobreyectivas hay de $A$ ($n$ elementos) en $\{0,1\}$? b) ¿Y de un conjunto de 8 elementos en uno de 7?

> [!success]- Solución
> a) Todas ($2^n$) menos las dos constantes: $2^n-2$ (para $n\ge1$).
> b) Hay 8 elementos y 7 imágenes, todas usadas: exactamente **dos** elementos comparten imagen. Elige esos dos: $\binom82=28$; júntalos como si fueran uno y biyecta 7 bloques con 7 imágenes: $7!=5040$. Total: $28\cdot5040=141120$.

Repasa: [[Conjunto finito]], [[Número combinatorio]]

## Ejercicio 5 · Números de cuatro cifras
> [!question] Enunciado (13)
> ¿Cuántos números de 4 cifras hay? ¿Cuántos divisibles por 5, pares, por 10, y por 2 **o** por 5?

> [!success]- Solución
> - Total: $9\cdot10^3=9000$ (la primera cifra no puede ser 0).
> - Divisibles por 5 (acaban en 0 o 5): $9\cdot10\cdot10\cdot2=1800$.
> - Pares: $9\cdot10\cdot10\cdot5=4500$.
> - Por 10: $9\cdot10\cdot10\cdot1=900$.
> - Por 2 **o** por 5 (**inclusión-exclusión**): $4500+1800-900=5400$.

Repasa: [[Conjunto finito]] (fórmula de la unión)

## Ejercicio 6 · Cartas
> [!question] Enunciado (14)
> Baraja española de 40 cartas (10 valores × 4 palos). Se sacan 5. ¿Cuántas manos hay? ¿Con dobles parejas? ¿Con full (pareja + trío)? ¿Con póker?

> [!success]- Solución
> - Manos: $\binom{40}5=658008$.
> - Dobles parejas: valores de las parejas $\binom{10}2=45$; palos de cada pareja $\binom42^2=36$; quinta carta de otro valor: $8\cdot4=32$. Total $45\cdot36\cdot32=51840$.
> - Full: valor del trío $10$, sus palos $\binom43=4$; valor de la pareja $9$, sus palos $\binom42=6$. Total $10\cdot4\cdot9\cdot6=2160$.
> - Póker: valor $10$, las 4 cartas $\binom44=1$, quinta carta $36$. Total $360$.

Repasa: [[Número combinatorio]]

## Ejercicio 7 · Numerabilidad
> [!question] Enunciado (15 y 16)
> a) ¿Por qué todo subconjunto no acotado de $\mathbb N$ es numerable? b) ¿Existe $X$ con $\mathcal P(X)$ numerable?

> [!success]- Solución
> a) No acotado ⇒ infinito (Prop. 5.10). Subconjunto infinito de $\mathbb N$ ⇒ numerable (Prop. 5.29).
> b) **No.** Si $X$ es finito, $\mathcal P(X)$ es finito ($2^n$). Si $X$ es infinito, contiene una copia de $\mathbb N$, así $\operatorname{card}X\ge\aleph_0$, y por el [[Teorema de Cantor]] $\operatorname{card}\mathcal P(X)>\operatorname{card}X\ge\aleph_0$.

Repasa: [[Conjunto numerable]]

## Ejercicio 8 · mcd · mcm = producto
> [!question] Enunciado (21)
> Si $d=\operatorname{mcd}(a,b)$ y $m=\operatorname{mcm}(a,b)$, prueba que $dm=ab$.

> [!success]- Solución
> Escribe $a=da'$, $b=db'$ con $\operatorname{mcd}(a',b')=1$ (Ej. 5.47). Sea $L=da'b'=\frac{ab}d$.
> - $L=ab'=a'b$ es múltiplo común de $a$ y $b$.
> - Si $k$ es múltiplo común: $k=ar=bs\Rightarrow da'r=db's\Rightarrow a'r=b's$. Como $a'\mid b's$ y $\operatorname{mcd}(a',b')=1$, por el [[Lema de Euclides]] $a'\mid s$: $s=a't$, y $k=b\,a't=Lt$.
> Así $L$ es el mcm: $m=\frac{ab}d$.

Repasa: [[Mínimo común múltiplo]], [[Máximo común divisor]]

## Ejercicio 9 · Factorizar xⁿ − yⁿ
> [!question] Enunciado (23)
> Prueba $x^n-y^n=(x-y)(x^{n-1}+x^{n-2}y+\cdots+xy^{n-2}+y^{n-1})$.

> [!success]- Solución
> Multiplica: $x\cdot(\dots)=x^n+x^{n-1}y+\cdots+xy^{n-1}$ y $y\cdot(\dots)=x^{n-1}y+\cdots+xy^{n-1}+y^n$. Al restar se cancela todo menos $x^n-y^n$ (suma **telescópica**).
> Consecuencia: $(x-y)\mid(x^n-y^n)$ en $\mathbb Z$.

## Ejercicio 10 · Un anillo producto
> [!question] Enunciado (24)
> En $\mathbb Z^2$ con operaciones componente a componente, ¿es anillo? ¿Unitario? ¿Íntegro?

> [!success]- Solución
> Anillo conmutativo (hereda todo de $\mathbb Z$ en cada coordenada). Unidad $(1,1)$. **No íntegro:** $(1,0)\cdot(0,1)=(0,0)$.

Repasa: [[Anillo]], [[Dominio de integridad]]
