# Precio-de-criptomonedas
Proyecto: predicción de Precios de Criptomonedas (Bitcoin y Binance Coin)

Este archivo realiza un análisis y predicción de precios para criptomonedas como Bitcoin (BTC) y Binance Coin (BNB). A continuación, se detalla lo que se hizo:

**1. Descripción del conjunto de datos**
Se analiza un conjunto de datos con información diaria de precios de criptomonedas, incluyendo:
Precios de apertura (open), máximos (high), mínimos (low), y cierre (close).
Fechas y otros indicadores relacionados.
**2. Análisis Exploratorio de Datos**
Visualización de precios históricos: Se generan gráficos de velas (candlestick) para visualizar cómo han fluctuado los precios de las criptomonedas en los últimos 300 días.
Estadísticas descriptivas: Se examinan métricas como los precios máximos, mínimos y promedios.
**3. Predicción de precios con múltiples modelos**
Se probaron diferentes métodos para predecir los precios de las criptomonedas, con los siguientes enfoques:
Modelos de series temporales
*ARIMA y SARIMA:*
Modelos estadísticos para capturar patrones estacionales y tendencias.
Predicciones realizadas y evaluadas con el RMSE (error cuadrático medio).
Suavizado exponencial (Exponential Smoothing):
Utilizado para modelar tendencias simples en los datos.
Modelos basados en aprendizaje automático
*Random Forest y redes neuronales (MLP):*
Modelos de regresión para capturar patrones complejos en los datos.
*Prophet:*
Modelo específico para series temporales desarrollado por Meta.
**4. Evaluación de los modelos**
*Se midió el rendimiento de cada modelo utilizando el RMSE:*
ARIMA, SARIMA, suavizado exponencial, modelos de aprendizaje automático y Prophet.
Se identificaron los modelos con menor error, indicando mejores predicciones.
**5. Predicción con regresión lineal**
Se aplicó un modelo de regresión lineal para predecir precios futuros basándose en las características del conjunto de datos.
*Evaluación:*
Visualización de predicciones frente a valores reales.
Cálculo del error promedio para predicciones a corto plazo (7 días) y largo plazo (1 año).
Se concluyó que el modelo tenía alta precisión para estas predicciones.

**6. Resultados y conclusiones**
Los modelos aplicados fueron efectivos para predecir precios de criptomonedas.
Se observó un desempeño sólido del modelo de regresión lineal en predicciones semanales y anuales.
Se sugirió que el enfoque podría extenderse a otras criptomonedas para evaluar su comportamiento.

# 📊Análisis y Visualización de Criptomonedas

Este proyecto realiza un análisis exploratorio y visualización de datos históricos de criptomonedas utilizando datos a nivel de minuto y diario obtenidos desde la API de Binance y archivos históricos en formato CSV.

El objetivo principal es explorar el comportamiento del mercado cripto, analizar precios, volúmenes y correlaciones, y visualizar la información en diferentes marcos temporales.

📁 Descripción del conjunto de datos

El dataset contiene datos de precios de criptomonedas a nivel de minuto con las siguientes variables:

timestamp: fecha y hora (minuto)

open: precio de apertura

high: precio máximo

low: precio mínimo

close: precio de cierre

volume: volumen de operaciones

close_time: marca de tiempo de cierre

quote_asset_volume: volumen negociado en valor

number_of_trades: número de operaciones

taker_buy_base_asset_volume: volumen de compra del tomador

taker_buy_quote_asset_volume: valor de compra del tomador

ignore: campo no utilizado

Además, se utilizan datos diarios para múltiples criptomonedas como:
BTC, ETH, BCH, XRP, SOL, DOGE, USDT, XMR y BNB.

## 🎯Objetivos del proyecto

- Analizar la evolución de precios de criptomonedas.
- Visualizar datos en distintos intervalos temporales:
- Minuto
- Horario
- Cada 4 horas
- Diario
- Realizar análisis estadístico descriptivo.
- Explorar correlaciones entre variables financieras.
- Generar visualizaciones interactivas y estáticas.

## 🛠️Tecnologías utilizadas

- Python
- Pandas – manipulación y análisis de datos
- NumPy – operaciones numéricas
- Matplotlib – visualizaciones estáticas
- Seaborn – análisis de correlaciones
- Plotly – gráficos interactivos (velas, histogramas)
- Warnings – manejo de advertencias

## 📈Funcionalidades principales

- Carga y limpieza de datos desde archivos CSV.
- Conversión de timestamps a formato datetime.
- Filtrado por rangos de fechas.
- Gráficos de velas (candlestick) para:
- Datos minuto a minuto
- Datos horarios
- Datos cada 4 horas
- Datos diarios

Análisis exploratorio:
- .describe()
- Histogramas
- Gráficos de barras
- Series temporales
- Matriz de correlación entre variables numéricas.


## 📊Casos de uso

📉 Análisis de mercado cripto

🤖 Desarrollo y evaluación de estrategias algorítmicas

📐 Modelado financiero

🎓 Proyectos educativos y de investigación

📚 Análisis exploratorio de datos (EDA)


## 🚀Futuras mejoras

- Integración directa con la API de Binance.
- Automatización de descarga de datos.
- Modelos de predicción de precios (ML / DL).
- Dashboards interactivos con Dash o Streamlit.
- Análisis multimoneda comparativo.
