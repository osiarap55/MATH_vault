# Cuerpos, Anillos y Teoría de Galois

Este documento resume los conceptos fundamentales de los cuerpos, anillos y la teoría de Galois, su estructura matemática y sus principales aplicaciones dentro y fuera de las matemáticas.

---

## 1. Anillos

### 1.1 Definición

Un **anillo** es un conjunto \(R\) equipado con dos operaciones:

- suma \(+\)
- producto \(\cdot\)

tal que:

- \((R, +)\) es un grupo abeliano
- el producto es asociativo
- el producto es distributivo respecto a la suma

Ejemplos:

- \(\mathbb{Z}\) (enteros)
- \(\mathbb{Z}/n\mathbb{Z}\)
- Anillos de polinomios \(R[x]\)
- Anillos de matrices

---

### 1.2 Tipos importantes de anillos

- **Anillo conmutativo**
- **Anillo con unidad**
- **Dominio de integridad**
- **Anillo factorial**
- **Anillo noetheriano**
- **Anillo local**

Conceptos clave:

- Ideales
- Ideales primos y maximales
- Cocientes \(R/I\)
- Homomorfismos de anillos

---

### 1.3 Aplicaciones de los anillos

- Aritmética modular
- Teoría algebraica de números
- Álgebra conmutativa
- Geometría algebraica (anillos de funciones)
- Criptografía (anillos finitos)
- Teoría de códigos

---

## 2. Cuerpos

### 2.1 Definición

Un **cuerpo** es un anillo conmutativo con unidad en el que todo elemento no nulo es invertible.

Ejemplos:

- \(\mathbb{Q}\)
- \(\mathbb{R}\)
- \(\mathbb{C}\)
- Cuerpos finitos \(\mathbb{F}\_p\)
- Cuerpos de funciones

---

### 2.2 Extensiones de cuerpos

Una **extensión de cuerpos** \(K/F\) es un cuerpo \(K\) que contiene a otro cuerpo \(F\).

Tipos:

- Extensiones algebraicas
- Extensiones trascendentes
- Extensiones finitas e infinitas
- Extensiones simples \(F(\alpha)\)

Conceptos fundamentales:

- Grado de una extensión
- Polinomio mínimo
- Cierre algebraico
- Cuerpos de descomposición

---

### 2.3 Aplicaciones de los cuerpos

- Resolución de ecuaciones polinómicas
- Cuerpos finitos en criptografía
- Teoría de números algebraica
- Geometría algebraica
- Análisis algebraico

---

## 3. Teoría de Galois

### 3.1 Idea central

La **Teoría de Galois** estudia la relación profunda entre:

- extensiones de cuerpos
- grupos de automorfismos

Permite traducir problemas algebraicos a problemas de teoría de grupos.

---

### 3.2 Grupo de Galois

Dada una extensión \(K/F\), el **grupo de Galois** es:
\[
\mathrm{Gal}(K/F) = \{ \sigma : K \to K \mid \sigma \text{ es automorfismo y fija } F \}
\]

---

### 3.3 Teorema Fundamental de Galois

Existe una correspondencia biyectiva entre:

- subgrupos del grupo de Galois
- subcuerpos intermedios de la extensión

Esta correspondencia preserva:

- inclusión
- normalidad
- grados de extensión

---

### 3.4 Consecuencias importantes

- Clasificación de ecuaciones resolubles por radicales
- Prueba de la imposibilidad de resolver el polinomio general de grado ≥ 5
- Construcciones clásicas con regla y compás
- Comprensión estructural de raíces de polinomios

---

## 4. Aplicaciones de la Teoría de Galois

### 4.1 Matemáticas puras

- Teoría algebraica de números
- Geometría algebraica
- Teoría de representaciones
- Álgebra homológica

### 4.2 Aplicaciones prácticas

- Criptografía moderna
- Teoría de códigos
- Computación algebraica
- Algoritmos simbólicos

---

## 5. Relación entre anillos, cuerpos y Galois

- Los **anillos** generalizan la aritmética
- Los **cuerpos** permiten dividir y resolver ecuaciones
- La **Teoría de Galois** describe la simetría interna de las soluciones

Juntos forman el núcleo estructural del álgebra moderna.

---

## 6. Conclusión

El estudio de cuerpos, anillos y teoría de Galois proporciona una visión profunda de la estructura algebraica de las matemáticas. Es una base esencial para teoría de números, geometría algebraica, criptografía y muchas áreas avanzadas de la matemática moderna.
