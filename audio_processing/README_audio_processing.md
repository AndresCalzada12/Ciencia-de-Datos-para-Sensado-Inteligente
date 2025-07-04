##  Audio Signal Processing and Classification / Procesamiento y Clasificación de Señales de Audio

Este módulo explora técnicas fundamentales de procesamiento de señales de audio digital y clasificación usando machine learning. Está dividido en dos componentes principales:

This module explores fundamental techniques in digital audio signal processing and classification using machine learning. It is divided into two main components:

---

###  `signal_processing_audio.ipynb`

#### 🇪🇸 Español  
Este notebook se enfoca en el preprocesamiento y análisis de señales de audio utilizando bibliotecas de Python como `librosa`, `numpy` y `matplotlib`. Entre las actividades principales se encuentran:

- Carga y visualización de formas de onda y espectrogramas.
- Aplicación de la Transformada de Fourier para analizar frecuencias.
- Extracción de características como MFCCs (coeficientes cepstrales en las frecuencias de Mel).

>  Esta sección ayuda a comprender cómo los datos de audio pueden transformarse en características útiles.

####  English  
This notebook focuses on preprocessing and analyzing audio signals using Python libraries such as `librosa`, `numpy`, and `matplotlib`. Key steps include:

- Loading and visualizing waveforms and spectrograms.
- Applying Fourier Transform to explore frequency components.
- Extracting key features such as MFCCs (Mel-Frequency Cepstral Coefficients).

> This section builds intuition around transforming raw audio data into meaningful features.

---

###  `classification_audio_signals.ipynb`

####  Español  
Este notebook implementa un pipeline de aprendizaje supervisado para clasificar señales de audio. Las etapas clave incluyen:

- Extracción de características desde archivos de audio.
- Preprocesamiento y normalización de los datos.
- Entrenamiento de un clasificador (SVM, k-NN, etc.) con etiquetas.
- Evaluación del modelo con métricas como exactitud y matriz de confusión.

>  Este apartado conecta el procesamiento de señales con la clasificación automática.

####  English  
This notebook demonstrates a supervised learning pipeline for classifying audio signals. Key components include:

- Feature extraction from audio files.
- Data normalization and preprocessing.
- Training a classifier (SVM, k-NN, etc.) with labeled audio data.
- Model evaluation using metrics such as accuracy and confusion matrix.

>  This section bridges signal processing with supervised learning.

---

###  Technologies / Tecnologías

- Python
- Librosa
- Scikit-learn
- Matplotlib / Seaborn
- NumPy / Pandas

---

###  Learning Outcomes / Resultados de Aprendizaje

- 🇪🇸 Comprender la estructura y propiedades de los datos de audio digital.  
- 🇪🇸 Aplicar transformaciones tiempo-frecuencia para extraer características relevantes.  
- 🇪🇸 Implementar modelos de clasificación y evaluar su desempeño.  

- 🇬🇧 Understand the structure and properties of digital audio data.  
- 🇬🇧 Apply time-frequency transformations to extract relevant features.  
- 🇬🇧 Train and evaluate classification models.