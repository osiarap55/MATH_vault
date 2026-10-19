---
tipo: inicio
tags: [indice]
---
# Inicio · Mis matemáticas

## Libros con notas
| Libro | Estado | Índice |
|---|---|---|
| Lenguaje matemático, conjuntos y números | Completo (7 capítulos) | [[LM - Lenguaje matemático, conjuntos y números]] |

Mapa general de las ramas: [[ramas_matematicas]] · Método de estudio: [[tecnicas_estudio_matematicas]]

## Cómo leer las notas
Cada nota es **una idea**: una definición, un teorema o un método. Todas siguen el mismo esquema:

> [!tip] En palabras sencillas
> La intuición, antes de lo formal.

> [!note] Definición
> El enunciado preciso.

> [!important] Teorema / Proposición
> Lo que se demuestra.

> [!abstract] Demostración (idea y pasos)
> Por qué es cierto, en pocos pasos, citando lo que se usa.

> [!example] Ejemplos
> Casos que sí cumplen.

> [!failure] Contraejemplos
> Casos que no cumplen: marcan el límite del concepto.

> [!warning] Errores típicos
> Las confusiones habituales.

> [!question] Ejercicio
> Inténtalo primero en papel…

> [!success]- Solución (plegada: haz clic para verla)
> …y luego compara.

Al final de cada nota, la sección **Conexiones** dice:
- **Necesitas antes:** qué tienes que saber para entenderla.
- **Lleva a / Se usa en:** qué resultados posteriores dependen de ella.
- **Practica:** ejercicios concretos.

Además, el panel de **enlaces entrantes** (backlinks) te enseña automáticamente qué otras notas usan la que estás leyendo.

## Propiedades y etiquetas
Cada nota tiene en sus propiedades:
- `tipo`: definición · teorema · método · ejercicios · índice
- `capitulo`: enlace al índice del capítulo
- `ref`: dónde está en el libro (sección y página)
- etiquetas por tema (`#logica`, `#conjuntos`, `#relaciones`, `#algebra`, `#naturales`, `#enteros`, `#reales`, `#complejos`…) y por tipo (`#definicion`, `#teorema`, `#metodo`, `#ejercicios`, `#indice`)

## Colores del grafo
En el grafo global y en el **grafo local** (barra derecha, primera pestaña) cada nodo tiene el color de su tipo:

| Color | Tipo de nota |
|---|---|
| Oro | índices (libro, capítulos) |
| Naranja | teoremas, proposiciones y leyes |
| Azul | definiciones |
| Verde | métodos (cómo demostrar, cómo calcular) |
| Violeta | ejercicios |
| Turquesa | tus resúmenes (`resumen_…`) |

El **grafo local** enseña solo la nota abierta y sus vecinas, **con flechas**: una flecha de A a B significa "A enlaza a B". En el control *Depth* (profundidad) puedes pasar de 1 a 2 para ver también las vecinas de las vecinas.

## Plugins instalados
- **Spaced Repetition:** repaso espaciado (el pilar 2 de tu [[tecnicas_estudio_matematicas|método]]). Dos formas de usarlo:
  - Añade la etiqueta `#review` a una nota y repásala desde el icono del plugin; él decide cuándo te toca volver a verla.
  - Crea tarjetas en cualquier nota con `Pregunta::Respuesta` (una línea) y repásalas con *Review flashcards*.
- **Excalidraw:** pizarra para dibujar diagramas, figuras y esquemas a mano alzada (pilar "Dibujar" de tu método). Se crea un dibujo con el icono del lápiz o desde la paleta de comandos.

> [!tip] Trucos útiles
> - **Buscar todos los teoremas de un tema:** en la búsqueda escribe `tag:#teorema tag:#reales`.
> - **Repaso rápido:** cada índice de capítulo empieza con un *Resumen en 5 minutos*, pensado para la rutina de tu [[tecnicas_estudio_matematicas|método de estudio]].
> - **Estilo:** solo tres bloques llevan color (definición en azul, teorema en ámbar, errores típicos en rojo); el resto va en gris. Viene del fragmento CSS `matematicas-color` (*Ajustes → Apariencia → Fragmentos CSS*).
