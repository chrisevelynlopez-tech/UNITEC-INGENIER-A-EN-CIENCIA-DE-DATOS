# CDO002 – Geometría Analítica Vectorial en 2D
**Universidad Tecnológica de México (UNITEC)**

**Créditos:** 6  
**Cuatrimestre:** 24-2  
**Calificación:** 10

---

## Objetivo de la materia
Esta materia te enseña a trabajar con vectores en el plano (2D). Es fundamental para entender cómo se representan y manipulan datos espaciales, lo cual se usa mucho en machine learning, gráficos y análisis de datos.

---

## ¿Qué vas a aprender?
- Concepto de vector y sus componentes
- Operaciones básicas con vectores (suma, resta, multiplicación por escalar)
- Producto punto (dot product)
- Magnitud y dirección de un vector
- Ecuación de la recta
- Ángulo entre vectores
- Aplicaciones básicas en el plano

---

## Temas principales
1. Introducción a los vectores
2. Operaciones con vectores
3. Producto punto y aplicaciones
4. Magnitud y normalización de vectores
5. Ecuaciones de rectas en el plano
6. Ángulo entre dos vectores
7. Representación gráfica de vectores

---

## Matemáticas que se usan (explicadas fácil)

### Magnitud de un vector
Mide la longitud del vector.

**Fórmula:**
$$
\|\vec{v}\| = \sqrt{x^2 + y^2}
$$

### Producto punto
Mide qué tan alineados están dos vectores.

**Fórmula:**
$$
\vec{a} \cdot \vec{b} = x_1 x_2 + y_1 y_2
$$

### Ángulo entre dos vectores
Se calcula usando el producto punto.

**Fórmula:**
$$
\cos \theta = \frac{\vec{a} \cdot \vec{b}}{\|\vec{a}\| \|\vec{b}\|}
$$

---

## Ejemplo de código en Python

```python
# Importamos numpy para trabajar con vectores
import numpy as np

# Definimos dos vectores en 2D
v1 = np.array([3, 4])
v2 = np.array([1, 2])

# Calculamos la magnitud del primer vector
magnitud_v1 = np.linalg.norm(v1)
print("Magnitud de v1:", magnitud_v1)

# Calculamos el producto punto entre v1 y v2
producto_punto = np.dot(v1, v2)
print("Producto punto:", producto_punto)

# Calculamos el ángulo entre los dos vectores (en radianes)
cos_theta = producto_punto / (np.linalg.norm(v1) * np.linalg.norm(v2))
```
---

## Explicaión del código
- np.array([3, 4]) → Crea un vector con componentes x=3, y=4
- np.linalg.norm(v1) → Calcula la magnitud (longitud) del vector
- np.dot(v1, v2) → Calcula el producto punto
- np.arccos() y np.degrees() → Convierten el coseno del ángulo a grados

---

## Consejos 
- Dibuja los vectores en papel o usa herramientas como GeoGebra para visualizar
- Practica mucho las operaciones básicas (suma, producto punto)
- Usa Python y NumPy desde el principio
- Entiende bien la diferencia entre magnitud y dirección

## Recursos
- Khan Academy – Vectores (sección de Preálgebra / Álgebra)
- GeoGebra (herramienta para graficar vectores)
- Documentación de NumPy (sección de álgebra lineal)
angulo = np.arccos(cos_theta)
print("Ángulo en radianes:", angulo)
print("Ángulo en grados:", np.degrees(angulo))
