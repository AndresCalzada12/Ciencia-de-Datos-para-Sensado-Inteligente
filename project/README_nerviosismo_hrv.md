# 🧠 Nervousness Detection via HRV Signal Analysis / Detección de Nerviosismo mediante Análisis de Señales HRV

This project explores the identification of nervousness states through the analysis of Heart Rate Variability (HRV) signals under cognitive stress conditions using mathematical challenges. Signals were collected from 22 participants using a Polar H10 chest strap and processed using a range of signal analysis techniques in the time, frequency, and time-frequency domains.

Este proyecto explora la identificación de estados de nerviosismo a través del análisis de señales de Variabilidad de Frecuencia Cardíaca (HRV) bajo condiciones de estrés cognitivo utilizando desafíos matemáticos. Las señales fueron recolectadas de 22 participantes con una banda torácica Polar H10 y procesadas con diversas técnicas de análisis de señales en los dominios del tiempo, frecuencia y tiempo-frecuencia.

---

## 🎯 Objective / Objetivo

🇬🇧 To evaluate nervousness in individuals by analyzing their HRV signals during timed mathematical tasks and validate it with self-reported stress levels.

🇪🇸 Evaluar el nerviosismo en individuos analizando sus señales HRV durante tareas matemáticas cronometradas y validarlo mediante autoinformes de estrés.

---

## 🧪 Methodology / Metodología

- 📋 22 participants were subjected to math tasks of increasing difficulty.
- 🎥 Each session was recorded and participants completed a nervousness survey (levels 1–3).
- ❤️ HRV signals were collected using Elite HRV app with a Polar H10 monitor.
- 🧼 Signals were preprocessed: filtering, baseline correction, and noise reduction.
- 📊 Three analyses were performed:
  - Time domain
  - Frequency domain (FFT, spectral entropy)
  - Time-frequency domain (Wavelet Transform)
- 🔬 Results were compared against a reference subject who did not show signs of nervousness.

---

## 🔍 Results / Resultados

🇬🇧 While time-domain analysis showed limited insight, frequency-domain analysis revealed stronger correlations between nervousness and high-frequency components. Spectral entropy and wavelet spectrograms clearly distinguished the nervousness states in comparison to the reference subject.

🇪🇸 Aunque el análisis en el dominio del tiempo mostró información limitada, el análisis en el dominio de la frecuencia reveló fuertes correlaciones entre el nerviosismo y los componentes de alta frecuencia. La entropía espectral y los espectrogramas wavelet permitieron distinguir claramente los estados de nerviosismo en comparación con el sujeto de referencia.

---

## 📦 Technologies / Tecnologías

- Python
- HeartPy
- NumPy / Pandas
- SciPy
- Matplotlib / Seaborn
- Signal Processing (FFT, Wavelet)
- Spectral Entropy

---

## 📚 Learning Outcomes / Resultados de Aprendizaje

- 🇬🇧 Design and execute physiological experiments for emotional state detection.
- 🇬🇧 Preprocess and analyze HRV signals using advanced signal processing techniques.
- 🇬🇧 Validate physiological findings with behavioral surveys and interviews.

- 🇪🇸 Diseñar y ejecutar experimentos fisiológicos para la detección de estados emocionales.
- 🇪🇸 Preprocesar y analizar señales HRV usando técnicas avanzadas de procesamiento de señales.
- 🇪🇸 Validar hallazgos fisiológicos mediante encuestas y entrevistas conductuales.

---

## 📝 Author / Autor

**Calzada Jasso Andres Geovani**  
Centro de Investigación Científica y de Educación Superior de Ensenada (CICESE)  
📧 andres.calzada@cicese.edu.mx