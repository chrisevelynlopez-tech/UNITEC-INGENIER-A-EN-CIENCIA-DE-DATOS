# CDO003 – Álgebra para Ciencias
**Universidad Tecnológica de México (UNITEC)**

**Créditos:** 6  
**Cuatrimestre:** 24-2  
**Calificación:** 10

---

## Objetivo de la materia
Esta materia refuerza tus conocimientos de álgebra y los aplica al contexto de ciencias y datos. Es muy importante porque muchas técnicas de ciencia de datos (regresiones, machine learning, matrices, etc.) se basan en álgebra.

---

## ¿Qué vas a aprender?
- Operaciones con polinomios y fracciones algebraicas
- Ecuaciones y sistemas de ecuaciones
- Funciones y sus representaciones
- Matrices y determinantes (muy usado en datos)
- Desigualdades
- Aplicaciones prácticas en problemas de ciencias

---

## Temas principales
1. Repaso de álgebra básica
2. Ecuaciones lineales y sistemas de ecuaciones
3. Funciones y gráficas
4. Matrices y operaciones matriciales
5. Determinantes
6. Desigualdades y valor absoluto
7. Aplicaciones a problemas reales

---

## Matemáticas que se usan (explicadas fácil)

### Sistema de ecuaciones 2x2
Se resuelve por sustitución, eliminación o usando matrices.

### Matriz
Es una tabla de números organizada en filas y columnas.

**Ejemplo de matriz 2x2:**
$$
\begin{bmatrix}
a & b \\
c & d
\end{bmatrix}
$$

### Determinante de una matriz 2x2
**Fórmula:**
$$
\text{det} = ad - bc
$$

---

## Ejemplo de código en Python

```python
import numpy as np

# Definimos dos matrices
A = np.array([[2, 3],
              [1, 4]])

B = np.array([[5, 6],
              [7, 8]])

# Multiplicamos las matrices
resultado = np.dot(A, B)
print("Multiplicación de matrices:\n", resultado)

# Calculamos el determinante de la matriz A
determinante = np.linalg.det(A)
print("Determinante de A:", determinante)

```

--- 

## Explicación del código
- np.array([[2, 3], [1, 4]]) → Crea una matriz de 2 filas y 2 columnas
- np.dot(A, B) → Multiplica las dos matrices
- np.linalg.det(A) → Calcula el determinante de la matriz A

---

## Consejos
- Practica mucho la multiplicación de matrices a mano antes de usar Python
- Usa calculadora o Python para verificar tus resultados
- Entiende bien el concepto de determinante, se usa mucho después
- Haz muchos ejercicios de sistemas de ecuaciones

---

## Recursos
- Khan Academy – Álgebra
- 3Blue1Brown – “Essence of Linear Algebra” (videos muy recomendados)
- Documentación de NumPy (álgebra lineal)
