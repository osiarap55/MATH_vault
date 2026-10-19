---
tipo: teorema
tags: [definicion, teorema, racionales, reales]
capitulo: "[[LM Cap 6 - Números racionales y reales]]"
ref: "§6.2 · pp. 215-217; §6.4-6.5 · pp. 222, 226"
aliases: [Números decimales, Decimal periódico, Fracción generatriz, Aproximación decimal, Truncamiento, Desarrollo decimal]
---
# Expresión decimal

> [!note] Números decimales
> Un **número decimal** (exacto) es un racional con algún representante de denominador $10^n$: $71223{,}145=\frac{71223145}{10^3}$.
> **Proposición:** una fracción irreducible $\frac ab$ es decimal $\iff b=2^n5^p$.
> *Idea:* $10^m=2^m5^m$; usa el [[Lema de Euclides|teorema de Gauss]].
> Ej.: $\frac15=0{,}2$ es decimal; $\frac13$ **no** (3 no divide a ninguna potencia de 10).

> [!important] Racionales ⇔ decimales finitos o periódicos
> Al dividir $a$ entre $b$ añadiendo ceros, los restos son $<b$, así que **alguno se repite** antes de $b$ pasos ([[Principio del palomar]]) y desde ahí las cifras se repiten.
> - **Periódico puro:** $\frac17=0{,}\overline{142857}$. **Periódico mixto:** $\frac76=1{,}1\overline6$.
> - Y al revés, todo decimal periódico es racional (**fracción generatriz**):
> $$x=1{,}0\overline{25}\ \Rightarrow\ 1000x-10x=1025{,}\overline{25}-10{,}\overline{25}=1015\ \Rightarrow\ x=\frac{1015}{990}=\frac{203}{198}.$$

> [!note] Aproximación decimal de un real
> Con la [[Parte entera]] $E$:
> $$\frac{E(10^nx)}{10^n}\le x<\frac{E(10^nx)+1}{10^n}$$
> Son las **aproximaciones de orden $n$ por defecto y por exceso** (el truncamiento). Ej.: $e\approx2{,}7182818$.
> Para pasar de orden $n$ a $n+1$, "se añade un cero al dividendo y se sigue dividiendo".

> [!important] Todo decimal infinito define un real
> Una expresión $x=a_0{,}a_1a_2a_3\dots$ significa: $x$ es **el único** real en todos los intervalos $[t_n,\,t_n+10^{-n}]$, donde $t_n$ es el truncamiento. Existe y es único por los [[Intervalos encajados]].

> [!warning] Ojo
> - $0{,}999\dots=1$: un mismo real puede tener **dos** expresiones decimales.
> - Por eso el libro **no** define $\mathbb R$ como "expresiones decimales": sumar y multiplicar decimales infinitos es engorroso (un cambio en la cifra mil puede alterar todas las anteriores).

## Conexiones
- **Necesitas antes:** [[Números racionales]], [[División euclídea]]
- **Usa:** [[Parte entera]], [[Intervalos encajados]]
- **Se usa en:** [[R no es numerable]] (biyección $[0,1)\simeq\mathcal P(\mathbb N)$)
