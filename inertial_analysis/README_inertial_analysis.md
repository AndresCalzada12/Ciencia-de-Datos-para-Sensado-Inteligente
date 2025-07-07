## 🏃 Inertial Sensor Analysis for Exercise Classification / Análisis de Sensores Inerciales para Clasificación de Ejercicios

This module presents a complete pipeline for collecting, processing, and analyzing inertial sensor data (IMUs) to assess the quality of physical exercises. It integrates signal segmentation, feature extraction, and machine learning classification.

Este módulo presenta un flujo completo para la recolección, procesamiento y análisis de datos de sensores inerciales (IMUs) para evaluar la calidad de rutinas de ejercicio físico. Integra segmentación de señales, extracción de características y clasificación con aprendizaje automático.

---

### 📘 `exercise_quality_classification.ipynb`

#### 🇬🇧 English  
This notebook walks through the following stages:

- Data collection using 5 IMUs placed on the lower limbs and lower back.
- Video recording to enable manual labeling and comparison with a gold standard (expert performance).
- Signal segmentation by exercise repetition.
- Feature extraction using the TSFEL library.
- Model training and evaluation using cross-validation.

> 📊 The final goal is to classify whether an exercise repetition was performed correctly or not.

#### 🇪🇸 Español  
Este notebook desarrolla las siguientes etapas:

- Recolección de datos con 5 sensores inerciales colocados en extremidades inferiores y espalda baja.
- Grabación de video para etiquetado manual y comparación con un estándar experto.
- Segmentación de señales por repetición del ejercicio.
- Extracción de características utilizando la librería TSFEL.
- Entrenamiento y evaluación del modelo usando validación cruzada.

> 📊 El objetivo final es clasificar si una repetición del ejercicio fue realizada correctamente o no.

---

### 🛠️ Technologies / Tecnologías

- Python
- TSFEL
- NumPy / Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

### 🎯 Learning Outcomes / Resultados de Aprendizaje

- 🇬🇧 Understand how to collect and analyze inertial data for activity classification.
- 🇬🇧 Apply feature extraction techniques for time-series sensor data.
- 🇬🇧 Build ML models to assess exercise performance.

- 🇪🇸 Comprender cómo recolectar y analizar datos inerciales para clasificación de actividades.
- 🇪🇸 Aplicar técnicas de extracción de características para datos de sensores tipo series temporales.
- 🇪🇸 Construir modelos de ML para evaluar la ejecución de rutinas físicas.