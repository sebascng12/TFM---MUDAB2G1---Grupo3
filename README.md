# TFM --- MUDAB2G1 --- Grupo 3

Este repositorio contiene los archivos utilizados para el desarrollo del Trabajo de Fin de Máster del Máster Universitario en Data Analytics for Business de la Universitat Pompeu Fabra - Barcelona School of Management. 
Este proyecto analiza la relación entre datos financieros estructurados y contenido textual de noticias económicas, con el objetivo de evaluar su valor conjunto como predictor del comportamiento del mercado bursátil mediante modelos de aprendizaje automático.

---

## Estructura del repositorio

- `TFM-MUDAB2G1-G3_pipeline_procesamiento_datos.ipynb`  
  Notebook responsable del scrapping, limpieza y transformación de datos. Incluye el preprocesamiento de variables tanto numéricas como textuales (Yahoo Finance y Google News).

- `TFM-MUDAB2G1-G3_modelos_clasificacion.ipynb`  
  Contiene modelos de clasificación que predicen la dirección del cambio en el precio de las acciones (subida o bajada), usando distintos enfoques de machine learning.

- `TFM-MUDAB2G1-G3_modelos_regresion.ipynb`  
  Notebook con modelos de regresión para series temporales orientados a predecir el precio futuro de las acciones, aplicando técnicas de aprendizaje automático, específicamente modelos de aprendizaje profundo como ARIMA y LSTM.

- `Datasets_Finales.zip`  
   Archivo comprimido (.zip) que contiene los siguientes datasets utilizados en el proyecto:
  
  - `tesla_news_raw.csv`  
    Dataset sin tratar con las noticias scrappeadas de 2019-2025 de Tesla Inc.
    
  - `tesla_sentiment.csv`  
    Dataset con puntuacion de sentimientos y embeddings de noticias relacionadas con Tesla agrupado por la media diaria, generado mediante modelos de NLP (FinBERT).
  
  - `tesla_stock.csv`  
    Dataset con datos históricos del precio de las acciones de Tesla (apertura, cierre, volumen, etc.).

  - `macroeconomic_variables.csv`  
    Contiene variables macroeconómicas relevantes obtenidas desde la FRED (Federal Reserve Economic Data), una plataforma del Federal Reserve Bank of St. Louis.


---

## Autores

##### MUDAB2G1 - Grupo 3 — Máster Universitario en Data Analytics for Business:
- Sebastian Carrillo
- Yaros Cifuentes
- Javier Donoso


---

