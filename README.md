# TFM --- MUDAB2G1 --- Grupo 3

Este repositorio contiene los archivos utilizados para el desarrollo del Trabajo de Fin de Máster del Máster Universitario en Data Analytics for Business. 
El objetivo principal del proyecto es analizar el impacto de diferentes fuentes de información tanto numéricas como textuales en la predicción del precio de la accion de la empresa Tesla 
mediante modelos de aprendizaje automático.

---

## Estructura del repositorio

- `TFM-MUDAB2G1-G3_pipeline_procesamiento_datos.ipynb`  
  Notebook responsable de la carga, limpieza y transformación de datos. Incluye el preprocesamiento de variables tanto numéricas como textuales.

- `TFM-MUDAB2G1-G3_modelos_clasificacion.ipynb`  
  Contiene modelos de clasificación que predicen la dirección del cambio en el precio de las acciones (subida o bajada), usando distintos enfoques de machine learning.

- `TFM-MUDAB2G1-G3_modelos_regresion.ipynb`  
  Notebook con modelos de regresión para series temporales orientados a predecir el precio futuro de las acciones, aplicando técnicas como regresión lineal,
  árboles de decisión y modelos avanzados.

- `Datasets_Finales.zip`  
   Archivo comprimido que contiene los siguientes datasets utilizados en el proyecto:
  
  - `tesla_sentiment.csv`  
    Dataset con análisis de sentimiento de noticias relacionadas con Tesla, generado mediante modelos de NLP (FinBERT).
  
  - `tesla_stock.csv`  
    Dataset con datos históricos del precio de las acciones de Tesla (apertura, cierre, volumen, etc.).

  - `macroeconomic_variables.csv`  
    Contiene variables macroeconómicas relevantes obtenidas desde la FRED (Federal Reserve Economic Data), una plataforma del Federal Reserve Bank of St. Louis.


---

## Autores

##### Grupo 3 — Máster Universitario en Data Analytics for Business:
- Sebastian Carrillo
- Yaros Cifuentes
- Javier Donoso


---

