---
tipo: teorema
tags: [teorema, reales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "Ejercicio 6.8 · p. 220"
aliases: [Raíz cuadrada, Existencia de raíces cuadradas, √d]
---
# Existencia de la raíz cuadrada

> [!important] Teorema (Ejercicio 6.8)
> Todo número real $d\ge0$ tiene **una única** raíz cuadrada positiva: existe un único $a\ge0$ con $a^2=d$. Se escribe $a=\sqrt d$.

> [!tip] En palabras sencillas
> En $\mathbb Q$ no existe $\sqrt2$; en $\mathbb R$ sí, y **la fabrica el axioma del supremo**: $\sqrt d$ es el techo de los números cuyo cuadrado no pasa de $d$.

> [!abstract] Demostración (idea y pasos)
> 1. Sea $d>0$ y $A=\{x\ge0\mid x^2\le d\}$. No vacío ($0\in A$) y acotado superiormente.
> 2. Por el [[Axioma del supremo]], existe $a=\sup A$. Hay que ver $a^2=d$ por [[Reducción al absurdo|reducción al absurdo]].
> 3. **Si $a^2>d$:** con $\varepsilon=\frac{a^2-d}{2a}>0$, $(a-\varepsilon)^2>a^2-2a\varepsilon=d$, así $a-\varepsilon$ sería una cota superior **menor** que $a$. Contradicción.
> 4. **Si $a^2<d$:** con un $\varepsilon>0$ pequeño (del orden de $\frac{d-a^2}{2a+1}$), $(a+\varepsilon)^2<d$, así $a+\varepsilon\in A$ y $a$ no sería cota. Contradicción.
> 5. **Unicidad:** si $\beta\ge0$ y $\beta^2=d$, entonces $\beta\in A$ (luego $\beta\le a$) y $\beta$ es cota de $A$ (luego $a\le\beta$).

> [!warning] Ojo
> La ecuación $x^2=d$ tiene **dos** soluciones $\pm\sqrt d$ (si $d>0$); el símbolo $\sqrt d$ designa **la positiva**. Por eso $\sqrt{x^2}=|x|$, no $x$.

## Conexiones
- **Usa:** [[Axioma del supremo]], [[Supremo e ínfimo]], [[Reducción al absurdo]]
- **Se usa en:** módulo de un complejo ([[Forma binómica y conjugado]]), [[Raíces n-ésimas de un complejo]]
- **Contraste:** [[Irracionalidad de raíz de 2]], [[Insuficiencia de los racionales]]
