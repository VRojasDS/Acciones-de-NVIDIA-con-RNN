# Predicción de Acciones de NVIDIA (NVDA)

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo de *Machine Learning* orientado a la predicción del precio de las acciones de **NVIDIA (NVDA)** utilizando datos históricos del mercado bursátil. El enfoque principal es el análisis de series temporales y la experimentación con modelos de regresión y/o aprendizaje profundo para estimar el comportamiento futuro del precio.

El proyecto tiene fines analíticos y educativos, y no constituye asesoramiento financiero.

## Objetivos

* Analizar el comportamiento histórico de las acciones de NVIDIA.
* Aplicar técnicas de preprocesamiento para series temporales.
* Entrenar modelos predictivos para estimar precios futuros.
* Evaluar el desempeño de los modelos mediante métricas apropiadas.

## Conjunto de Datos

El dataset contiene información histórica diaria de las acciones de NVIDIA obtenida de mercados financieros. Las variables comúnmente utilizadas incluyen:

* **Date**: Fecha de cotización
* **Open**: Precio de apertura
* **High**: Precio máximo del día
* **Low**: Precio mínimo del día
* **Close**: Precio de cierre
* **Adj Close**: Precio de cierre ajustado
* **Volume**: Volumen de transacciones

## Metodología

1. **Preprocesamiento de Datos**

   * Conversión de fechas y ordenamiento temporal
   * Manejo de valores faltantes
   * Normalización / escalado de datos
   * Generación de *features* (ventanas temporales, medias móviles, retornos)

2. **Análisis Exploratorio (EDA)**

   * Evolución histórica del precio

3. **Entrenamiento del Modelo**

   * División temporal en conjuntos de entrenamiento y prueba
   * Modelo utilizado:
     * LSTM / redes neuronales para series temporales

4. **Evaluación del Modelo**

   * MAE (Mean Absolute Error)
   * RMSE (Root Mean Squared Error)
   * Comparación visual entre valores reales y predichos

## Tecnologías Utilizadas

* Python
* NumPy
* Pandas
* Scikit-learn
* PyTorch 
* Matplotlib / Seaborn
* Seaborn
* Joblib

## Resultados
R2: 96%
Error absoluto: 5.24

