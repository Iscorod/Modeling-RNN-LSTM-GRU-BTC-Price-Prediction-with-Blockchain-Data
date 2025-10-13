Estudio de la capacidad de las redes neuronales recurrentes para predecir Bitcoin. 
Evaluación del rendimiento de redes recurrentes (RNN, LSTM y GRU) en la estimación del precio de Bitcoin.


Autor: Francisco Rodriguez
Universidad: Master Data Science y Big Data de la Universidad de Sevilla
Fecha: Octubre 2025

Este repositorio contiene el código y los datos empleados en el Trabajo Fin de Máster (TFM) titulado:

"Estudio de la capacidad de las redes neuronales recurrentes para predecir Bitcoin. 
Evaluación del rendimiento de redes recurrentes (RNN, LSTM y GRU) en la estimación del precio de Bitcoin"

El objetivo del proyecto es evaluar la capacidad predictiva de las redes neuronales para variables volátiles como el Bitcoin (BTC_Close), integrando variables exógenas procedentes de métricas de bloackchain del BTC.

Fuentes de datos

Variable objetivo (BTC_Close):
Obtenida a través de la API oficial de Binance, con datos diarios entre el 1 de enero de 2018 y el 30 de junio de 2024.

Variables exógenas (on-chain):
Descargadas desde la API de bitcoin-data.com
, en formato JSON, y transformadas a formato tabular mediante pandas para su integración con el resto del dataset.

Tecnologías utilizadas

Lenguaje: Python 3.10

Principales librerías:

  -  pandas, numpy, matplotlib, seaborn

  -  scikit-learn

  -  requests (para conexión con APIs)

  -  statsmodels

  -  tensorflow o keras (redes neuronales)

Los resultados obtenidos se describen en el documento principal del TFM (no incluido en el repositorio).
Este repositorio incluye los notebooks con las gráficas y métricas generadas, así como los archivos CSV utilizados durante el modelado.

Licencia y uso

El contenido de este repositorio se distribuye únicamente con fines académicos y de investigación.
Cualquier uso comercial o reproducción parcial debe contar con la autorización del autor.

Para cualquier consulta o colaboración:
Francisco Rodriguez
https://www.linkedin.com/in/iscorod/
