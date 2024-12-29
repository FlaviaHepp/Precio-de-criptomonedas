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
