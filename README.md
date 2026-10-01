# Análisis de sesgos demográficos en modelos de scoring crediticio

**Autora:** Diana Marcela López Cerón  
**Máster Universitario en Big Data y Ciencia de Datos — Universidad Internacional de Valencia (VIU)**

## Objetivo

Evaluar la presencia de sesgos demográficos en modelos de scoring crediticio mediante el análisis conjunto del desempeño predictivo y de las métricas de equidad, considerando la estabilidad de las brechas observadas ante diferentes umbrales de clasificación, así como explorar una estrategia orientada a su mitigación.

## Datos utilizados

Se utiliza el conjunto de datos público *Default of Credit Card Clients*, disponible en el repositorio UCI Machine Learning Repository, con 30.000 registros de clientes de tarjetas de crédito de Taiwán.

La variable objetivo identifica el incumplimiento de pago. Los atributos demográficos analizados son sexo, edad, nivel educativo y estado civil.

## Contenido

El archivo `TFM.ipynb` incluye:

- Análisis exploratorio y preparación de los datos.
- Entrenamiento y optimización de Regresión Logística, Random Forest, XGBoost y LightGBM, con y sin variables demográficas.
- Selección del umbral de clasificación.
- Evaluación del desempeño predictivo.
- Evaluación de la equidad entre grupos.
- Comparación entre desempeño y equidad.
- Análisis de sensibilidad.
- Análisis de mitigación.

## Consulta y ejecución

El notebook contiene el código y los resultados guardados, que pueden consultarse directamente en GitHub.

Para ejecutarlo, es necesario descargar la base de datos, instalar las librerías utilizadas y ajustar la ruta de lectura del Excel a su ubicación en el equipo.

## Finalidad

Este repositorio reúne el código desarrollado para el Trabajo Final de Máster y permite consultar los análisis que respaldan sus resultados.
