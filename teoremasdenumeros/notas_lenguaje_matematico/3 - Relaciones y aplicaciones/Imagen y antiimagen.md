---
tipo: definición
tags: [definicion, aplicaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.37 · p. 94; Ejercicio 21 · p. 119"
aliases: [Imagen inversa, Antiimagen, Preimagen, Imagen directa, f^-1(B), Original de un elemento]
---
# Imagen y antiimagen

> [!tip] En palabras sencillas
> - **Imagen** $f(C)$: a dónde van a parar los elementos de $C$.
> - **Antiimagen** $f^{-1}(E)$: quiénes van a parar a $E$.
>
> La antiimagen existe **siempre**, aunque $f$ no tenga inversa.

> [!note] Definición
> Sea $f:A\to B$, $C\subseteq A$, $E\subseteq B$:
> $$f(C)=\{f(x)\mid x\in C\}\subseteq B\qquad f^{-1}(E)=\{x\in A\mid f(x)\in E\}\subseteq A$$
> Para un punto: $f^{-1}(y)=\{x\in A\mid f(x)=y\}$ (puede ser vacío o tener muchos elementos).

> [!important] Propiedades
> | Imagen | Antiimagen |
> |---|---|
> | $C\subseteq D\Rightarrow f(C)\subseteq f(D)$ | $E\subseteq F\Rightarrow f^{-1}(E)\subseteq f^{-1}(F)$ |
> | $f(C\cup D)=f(C)\cup f(D)$ | $f^{-1}(E\cup F)=f^{-1}(E)\cup f^{-1}(F)$ |
> | $f(C\cap D)\subseteq f(C)\cap f(D)$ | $f^{-1}(E\cap F)=f^{-1}(E)\cap f^{-1}(F)$ |
> | (igualdad si $f$ es inyectiva) | $f^{-1}(\bar E)=\overline{f^{-1}(E)}$ |
>
> **La antiimagen respeta todas las operaciones; la imagen no respeta la intersección.**

> [!failure] Contraejemplo: $f(C\cap D)\neq f(C)\cap f(D)$
> $f(x)=x^2$, $C=\{-1\}$, $D=\{1\}$: $C\cap D=\emptyset$, así que $f(C\cap D)=\emptyset$, pero $f(C)\cap f(D)=\{1\}$.

> [!warning] Errores típicos
> - Escribir $f^{-1}(E)$ y creer que exige que $f$ sea biyectiva. Es solo notación.
> - $f(f^{-1}(E))\subseteq E$ (igualdad si $f$ es sobreyectiva) y $C\subseteq f^{-1}(f(C))$ (igualdad si es inyectiva).

## Conexiones
- **Necesitas antes:** [[Aplicación]], [[Unión e intersección]]
- **Lleva a:** [[Factorización canónica de una aplicación]] (las fibras $f^{-1}(y)$ son clases de equivalencia)
- **Practica:** [[LM Ejercicios Cap 3#Ejercicio 7 · Imagen y antiimagen]]
