# 📊Análisis y Predicción de Precios de Acciones de MasterCard y Visa (2008–2024)

Este proyecto realiza un análisis financiero integral y la predicción de precios de acciones de MasterCard (MA) y Visa (V) utilizando datos históricos diarios desde 2008 hasta 2024.

Se combinan técnicas de Análisis Exploratorio de Datos (EDA), estadística, Machine Learning, Deep Learning (LSTM) y modelos econométricos (ARIMA) para estudiar el comportamiento del precio, la volatilidad y la dinámica temporal de ambas acciones.

## 🎯Objetivos del proyecto
- Analizar la evolución histórica de los precios de MasterCard y Visa.
- Comparar el desempeño y la correlación entre ambas acciones.
- Explorar distribuciones, volatilidad y rendimientos.
- Aplicar técnicas de limpieza, normalización y tratamiento de outliers.
- Entrenar modelos de Machine Learning para predicción de precios.
- Implementar Deep Learning (LSTM) para series temporales.
- Modelar la dinámica temporal mediante ARIMA.
- Realizar pronósticos futuros y visualizarlos de forma interactiva.

## 📁Descripción del dataset
El dataset contiene precios históricos diarios de acciones:
- Variables incluidas
- Date: fecha de negociación
- Open, High, Low, Close, Adj Close para MasterCard y Visa
- Volume: volumen negociado
- Aspectos destacados
   - Más de 15 años de datos históricos

Ideal para:
- Series temporales financieras
- Análisis comparativo
- Modelado predictivo
- Fines educativos y de investigación 


## 📊Análisis Exploratorio de Datos (EDA)
- Evolución temporal de precios de cierre.
- Histogramas y distribuciones KDE.
- Análisis de correlación y mapas de calor.
- Gráficos de regresión entre precios de cierre.
- Distribución comparativa de volúmenes.
- Diagramas de caja para detección de outliers.
- Medias móviles (30, 50 y 200 días).
- Volatilidad móvil (rolling standard deviation).
- Rendimientos diarios y acumulados.

## 🧪Análisis estadístico
- Prueba de normalidad (Shapiro–Wilk).
- Transformación de potencia para normalización.
- Prueba ADF (Dickey–Fuller aumentada) para estacionariedad.
- Descomposición estacional:
  -- Tendencia
  -- Estacionalidad
  -- Residuo

## 🤖Modelos de Machine Learning
🔹 Random Forest Regressor

Predicción del precio de cierre para:

**MasterCard

**Visa

Features:
- Precios Open, High, Low
- Volúmenes de ambas acciones

Métricas:
- MSE
- R²

Comparación visual de valores reales vs. predichos.

🔹 Regresión Lineal
- Modelo base para evaluar relaciones lineales.
- Análisis de error y dispersión real vs. predicho.

## 🧠Deep Learning – LSTM
- Normalización con MinMaxScaler.
- Ventanas temporales de 60 días.
- Arquitectura:
  -- Capas LSTM apiladas
  -- Capas Dense

Entrenamiento independiente para:
- MasterCard
- Visa
- Evaluación con RMSE.

Visualización de:
- Datos de entrenamiento
- Datos de validación
- Predicciones del modelo.

## ⏱️Modelado econométrico – ARIMA
- Modelos ARIMA(5,1,0) para MasterCard y Visa.
- Predicción fuera de muestra.
- Pronósticos extendidos a 3 años (2025–2027).
- Visualización de precios históricos y futuros.
- Gráficos de velas interactivos con Plotly.

## 🛠️Tecnologías utilizadas
- Python
- pandas / numpy
- Matplotlib / `Seaborn`
- Plotly
- scikit-learn
- TensorFlow / Keras
- statsmodels

## 📂Estructura del proyecto

├── 1.py
├── MVR.csv
└── README.md


## 📌Resultados clave
- Alta correlación entre los precios de MasterCard y Visa.
- Tendencias de largo plazo claramente identificables.
- Random Forest mejora modelos lineales básicos.
- LSTM captura dependencias temporales complejas.
- ARIMA permite pronósticos interpretable de corto y mediano plazo.
- El enfoque híbrido combina interpretabilidad + performance.

# ⚠️Disclaimer

Este proyecto tiene fines educativos y analíticos.
No constituye asesoramiento financiero ni recomendaciones de inversión.

## 👤Autor

**Flavia Hepp**
Data Science en formación · Machine Learning · Deep Learning · Finanzas
