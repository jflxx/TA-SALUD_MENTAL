# 🧠 Análisis de Factores Socioeconómicos en Salud Mental mediante Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-sklearn-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)

## 📊 Descripción del Proyecto

Este proyecto de investigación académica utiliza técnicas de Machine Learning para analizar factores socioeconómicos en la detección de riesgos de salud mental en el Perú. El estudio combina datos demográficos del censo nacional con registros de atenciones en salud mental para identificar patrones y factores de riesgo a nivel distrital.

### 🎯 Objetivos

- **Objetivo Principal**: Desarrollar modelos predictivos para identificar distritos con mayor riesgo de problemas de salud mental
- **Objetivos Específicos**:
  - Analizar la correlación entre factores socioeconómicos y demanda de atención en salud mental
  - Comparar el rendimiento de diferentes algoritmos de Machine Learning
  - Proporcionar insights para la asignación de recursos de salud pública

## 📂 Estructura del Proyecto

```
TA-SALUD_MENTAL/
├── 📊 DAT SALUD MENTAL - ATENDIDOS.csv    # Dataset principal de atenciones
├── 🗺️ GeoPeru-peru_distritos.xlsx        # Datos geográficos y demográficos
├── 📋 diccionario_censo.docx              # Diccionario de variables del censo
├── 📓 TA_IA.ipynb                         # Notebook principal del análisis
├── 📄 Grupo07-TA-Final.pdf                # Reporte final del proyecto
└── 📖 README.md                           # Este archivo
```

## 🔍 Metodología

### 1. **Preprocesamiento de Datos**
- Limpieza y integración de datasets
- Tratamiento de valores faltantes

### 2. **Selección de Variables**
- **Método Filtro**: SelectKBest con f_classif
- **Método Wrapper**: RFECV (Recursive Feature Elimination with Cross-Validation)

### 3. **Modelos Implementados**
- 🌲 **Random Forest Classifier**
- 📈 **Logistic Regression**  
- 🎯 **Support Vector Machine (SVM)**
- 🌳 **Decision Tree Classifier**

### 4. **Evaluación y Validación**
- Validación cruzada estratificada
- Métricas de accuracy, precision, recall y F1-score
- Análisis de importancia de características

## 📈 Resultados Principales
*Los resultados detallados se encuentran en el notebook `TA_IA.ipynb` y el reporte final `Grupo07-TA-Final.pdf`*

### Hallazgos Clave:
- **Variable Target**: Número de atenciones por problemas de salud mental por distrito
- **Mejores Predictores**: primaria incompleta, alumbrado eléctrico, un solo ambiente, edad 30 a 44, económicamente activa, dificultad para hablar, económicamente desocupada, edad 15 a 29 y dificultad para relacionarse.
- **Modelo Óptimo**: Random Forest

## 📊 Datasets

### 1. **DAT SALUD MENTAL - ATENDIDOS.csv**
- **Descripción**: Registros de atenciones en salud mental por distrito
- **Tamaño**: 52,613 registros

### 2. **GeoPeru-peru_distritos.xlsx**
- **Descripción**: Datos demográficos y socioeconómicos del censo nacional
- **Nivel**: Distrital
- **Variables**: Características poblacionales, económicas y sociales

## 📄 Documentación Adicional

- 📋 **Diccionario de Variables**: `diccionario_censo.docx`
- 📊 **Reporte Final**: `Grupo07-TA-Final.pdf`
- 💻 **Código Fuente**: `TA_IA.ipynb`

## 🎓 Aplicaciones Prácticas

Este proyecto puede ser utilizado para:

- **Políticas Públicas**: Identificación de zonas prioritarias para intervención
- **Asignación de Recursos**: Optimización de recursos en salud mental
- **Investigación Académica**: Base para estudios epidemiológicos
- **Prevención**: Desarrollo de programas preventivos focalizados

## 📈 Impacto y Contribuciones

- Identificación de factores de riesgo socioeconómicos
- Modelo predictivo para planificación de servicios de salud
- Metodología replicable para otros contextos geográficos
- Contribución a la literatura en salud pública digital