---
tipo: definición
tags: [definicion, relaciones]
capitulo: "[[LM Cap 3 - Relaciones y aplicaciones]]"
ref: "Def. 3.7 · p. 79; Ejemplo 3.43"
aliases: [Cociente, Proyección canónica, U/~]
---
# Conjunto cociente  $U/\!\sim$

> [!tip] En palabras sencillas
> Es el conjunto que obtienes al **"pegar" cada clase en un solo punto**. Sus elementos son las clases. Es la manera matemática de decir "a partir de ahora, considero iguales a los que son equivalentes".

> [!note] Definición
> $$U/\!\sim\ =\{[x]\mid x\in U\}$$
> La **proyección canónica** $p:U\to U/\!\sim$, $p(x)=[x]$, manda cada elemento a su clase. Es siempre [[Aplicación sobreyectiva|sobreyectiva]].

> [!example] Los cocientes más importantes del libro
> - $\mathbb Z=(\mathbb N\times\mathbb N)/\!\sim$ con $(a,b)\sim(c,d)\iff a+d=b+c$. La clase de $(a,b)$ "es" $a-b$. **Motivación:** que $x+b=a$ siempre tenga solución. → [[Números enteros]]
> - $\mathbb Q=(\mathbb Z\times\mathbb Z^*)/\!\sim$ con $(a,b)\sim(c,d)\iff ad=bc$. La clase de $(a,b)$ se escribe $\frac ab$. **Motivación:** que $bx=a$ ($b\neq0$) siempre tenga solución. → [[Números racionales]]
> - $\mathbb Z/p=\{\bar0,\bar1,\dots,\overline{p-1}\}$, los restos módulo $p$. → [[Congruencia módulo n]]
> - $\mathbb R/2\pi$: los ángulos. Por eso las funciones periódicas de periodo $2\pi$ basta estudiarlas en $[0,2\pi)$.

> [!important] Por qué es tan útil
> Es la herramienta para **construir objetos nuevos** a partir de otros: los números enteros, racionales y reales (con [[Cortaduras de Dedekind]]), los espacios cociente en álgebra lineal, los grupos cociente…

> [!warning] Errores típicos
> - Definir una operación en el cociente usando representantes **sin comprobar que está bien definida** (que el resultado no cambia si cambias de representante).

## Conexiones
- **Necesitas antes:** [[Clase de equivalencia]]
- **Lleva a:** [[Partición de un conjunto]], [[Factorización canónica de una aplicación]]
- **Se usa para construir:** [[Números enteros]], [[Números racionales]], [[Congruencia módulo n]]
