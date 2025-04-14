# Proyecto de Análisis de Datos para ABC Corporation

## Resumen Ejecutivo
En un entorno empresarial competitivo, **retener talento y mejorar la satisfacción laboral** son claves para el éxito organizacional.
ABC Corporation nos ha encargado el desarrollo de un análisis de datos con el objetivo de:

- Identificar factores clave que afectan la satisfacción laboral.
- Mejorar la retención de empleados.
- Proveer insights estratégicos basados en datos reales.

## 🔍 Fases del Proyecto
### 📁 1. Análisis Exploratorio de Datos (EDA)
Antes de cualquier análisis profundo, exploramos el dataset para comprender:

- La estructura de los datos 
- Patrones generales y anomalías 
- Distribución de variables y correlaciones iniciales 

### 🛠️ 2. Transformación de los Datos
Se realizaron limpiezas y correcciones en el dataset, incluyendo:

- 🔁 Conversión de valores numéricos a etiquetas:`Gender` → `"M"` y `"F"`
- 🔢 Conversión de columnas tipo string a numéricas: `DailyRate` → tipo `float`
- 🧹 Eliminación o análisis de valores duplicados e inconsistencias:
    - `DistanceFromHome` tenía valores negativos ❗
    - `MaritalStatus`: corrección de errores como "`Marreid`" → "`Married`"
- 🧾 Eliminación de columnas redundantes

### 📊 3. Visualización de Datos
Visualizamos patrones clave y relaciones entre variables con:

- 📦 Boxplots: Salario anual por género y por departamento
- 📈 Histogramas: Distribución de salario según horas estándar
- 📊 Barplots: Años trabajados vs. nivel laboral y escala salarial
- 🧮 Countplots: Satisfacción laboral vs. distancia al hogar


## ✅ Conclusión
Este proyecto permite:
- Entender los patrones de satisfacción laboral
- Detectar áreas de mejora en la gestión de RRHH
- Apoyar decisiones estratégicas basadas en datos reales
- Ofrecer visualizaciones claras y accionables

##  📂 Archivos incluidos
```
text
📁 files/
    └── hr_raw_data_v0.csv
    ├── hr_raw_data_v1.csv
    └── hr_raw_data_v2.csv
📁 notebooks/
    └── 1-structural_data_analysis_&_cleaning.ipynb
    ├── 2-data-cleaning.ipynb
    ├── 3-data-analysis.ipynb
    └── 4-ddbb-connector.ipynb
📄 documentation.md
📄 README.md
```

### 🚀 Herramientas utilizadas
- Python 🐍
- Pandas & NumPy
- Seaborn & Matplotlib
- Jupyter Notebooks
- Git & GitHub

