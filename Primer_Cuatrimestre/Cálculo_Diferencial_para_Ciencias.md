# CDO005 – Cálculo Diferencial para Ciencias
**Universidad Tecnológica de México (UNITEC)**

**Créditos:** 6  
**Cuatrimestre:** 24-3  
**Calificación:** 9

---

## Objetivo de la materia
Esta materia introduce los conceptos básicos del cálculo diferencial aplicados a problemas de ciencias y datos. Es fundamental para entender tasas de cambio, optimización y cómo varían las funciones.

---

## ¿Qué vas a aprender?
- Límites y continuidad
- Derivadas y sus aplicaciones
- Reglas de derivación
- Derivadas de funciones comunes
- Aplicaciones de la derivada (máximos, mínimos, tasas de cambio)
- Introducción a la optimización

---

## Temas principales
1. Límites y continuidad
2. Definición de derivada
3. Reglas de derivación (producto, cociente, cadena)
4. Derivadas de funciones polinómicas, exponenciales y trigonométricas
5. Aplicaciones de la derivada
6. Problemas de optimización
7. Análisis de funciones con derivadas

---

## Matemáticas que se usan (explicadas fácil)

### Derivada
Mide la tasa de cambio instantánea de una función.

**Fórmula básica:**

$$
f'(x) = \lim_{h \to 0} \frac{f(x+h) - f(x)}{h}
$$


### Derivada de una potencia

$$
\frac{d}{dx} x^n = n \cdot x^{n-1}
$$


### Regla de la cadena
Se usa cuando una función está compuesta dentro de otra.

---

## Ejemplo de código en Python

```python
import sympy as sp

# Definimos la variable
x = sp.symbols('x')

# Definimos una función
f = x**3 + 2*x**2 - 5*x + 7

# Calculamos la derivada
derivada = sp.diff(f, x)
print("Función:", f)
print("Derivada:", derivada)

# Evaluamos la derivada en un punto (x=2)
valor = derivada.subs(x, 2)
print("Valor de la derivada en x=2:", valor)

```

## Explicación del código
- import sympy as sp → Importa la librería SymPy para cálculo simbólico
- sp.symbols('x') → Crea la variable simbólica x
- sp.diff(f, x) → Calcula la derivada de la función respecto a x
- .subs(x, 2) → Sustituye x por el valor 2 para evaluar

---

## Consejos
- Practica primero las derivadas a mano antes de usar Python
- Usa SymPy para verificar tus resultados
- Entiende bien la regla de la cadena, se usa mucho después
- Relaciona los conceptos con problemas reales (velocidad, crecimiento, optimización)

---

## Recursos
- Khan Academy – Cálculo Diferencial
- 3Blue1Brown – “Essence of Calculus”
- Documentación de SymPy
