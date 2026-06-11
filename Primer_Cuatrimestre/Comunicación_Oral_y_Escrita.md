# MCO002 – Comunicación Oral y Escrita
**Universidad Tecnológica de México (UNITEC)**

**Créditos:** 5  
**Cuatrimestre:** 24-2  
**Calificación:** 10

---

## Objetivo de la materia
Esta materia desarrolla tus habilidades para comunicar ideas de forma clara, profesional y efectiva, tanto en forma escrita como oral. Es clave para tu carrera porque en ciencia de datos no basta con saber analizar: debes saber explicar tus hallazgos a equipos técnicos y no técnicos.

---

## ¿Qué vas a aprender?
- Redacción clara y profesional
- Estructura de textos académicos y técnicos
- Presentaciones efectivas
- Escucha activa y trabajo en equipo
- Comunicación en entornos digitales y laborales
- Técnicas para hablar en público

---

## Temas principales
1. Fundamentos de la comunicación
2. Escritura formal y profesional
3. Redacción de reportes técnicos
4. Presentaciones con apoyo visual (diapositivas)
5. Uso del lenguaje técnico y no técnico según la audiencia
6. Trabajo colaborativo y retroalimentación
7. Ética en la comunicación

---

## Aplicación en Ciencia de Datos
En tu carrera, usarás estas habilidades para:
- Escribir informes ejecutivos
- Hacer presentaciones de dashboards y análisis
- Explicar modelos de machine learning a personas no técnicas
- Documentar tu código y proyectos
- Trabajar en equipo y defender tus resultados

---

## Ejemplo de código (comunicación técnica en un proyecto)

```python
# INFORME DE ANÁLISIS EXPLORATORIO DE DATOS (EDA)
# Proyecto: Análisis de Salarios en Ciencia de Datos

# Descripción:
# Este análisis explora un dataset de salarios con variables como experiencia,
# ubicación, y lenguajes de programación. El objetivo es identificar tendencias
# que expliquen las diferencias salariales.

import pandas as pd

# Leer los datos
df = pd.read_csv("salarios_cd.csv")

# Mostrar primeras filas para ver la estructura
print("Primeras 5 filas:")
print(df.head())

# Resumen estadístico
print("\nResumen estadístico:")
print(df.describe())
```

--- 

## Explicación del código
# Este ejemplo no es técnico puro, sino una demostración de cómo integrar buena comunicación dentro del código:
- Los comentarios explican qué se hace y por qué
- El print() incluye títulos claros
- La estructura es lógica y fácil de seguir
- Se anticipa qué información necesita el lector

---

## Consejos
- Siempre documenta tu código como si lo fuera a leer alguien ajeno al proyecto
- Practica resumir hallazgos en una o dos frases claras
- Usa diapositivas limpias: menos texto, más visual
- Entrena hablar en público (puedes grabarte o practicar frente al espejo)
- No uses tecnicismos con ejecutivos: explica con analogías

---

## Recursos
- Libro: "Colegio de Escritores: Redacción Técnica y Profesional"
- Coursera: Business Communication (University of Colorado)
- Herramienta: Canva (para presentaciones claras y visualmente atractivas)
- Plantillas de informe de datos (Google "data analysis report template")
# Conteo de lenguajes más usados
print("\nTop 5 lenguajes más comunes:")
print(df['lenguaje_principal'].value_counts().head())
