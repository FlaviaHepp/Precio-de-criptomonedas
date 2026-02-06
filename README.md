# 📊Análisis y Visualización de Criptomonedas

Este proyecto realiza un análisis exploratorio y visualización de datos históricos de criptomonedas utilizando datos a nivel de minuto y diario obtenidos desde la API de Binance y archivos históricos en formato CSV.

El objetivo principal es explorar el comportamiento del mercado cripto, analizar precios, volúmenes y correlaciones, y visualizar la información en diferentes marcos temporales.

## 📁Descripción del conjunto de datos

El dataset contiene datos de precios de criptomonedas a nivel de minuto con las siguientes variables:

- timestamp: fecha y hora (minuto)
- open: precio de apertura
- high: precio máximo
- low: precio mínimo
- close: precio de cierre
- volume: volumen de operaciones
- close_time: marca de tiempo de cierre
- quote_asset_volume: volumen negociado en valor
- number_of_trades: número de operaciones
- taker_buy_base_asset_volume: volumen de compra del tomador
- taker_buy_quote_asset_volume: valor de compra del tomador
- ignore: campo no utilizado

Además, se utilizan datos diarios para múltiples criptomonedas como:
- BTC, ETH, BCH, XRP, SOL, DOGE, USDT, XMR y BNB.

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
