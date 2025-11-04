# Prediccion-Precios-Inmobiliarios-ML
Este proyecto se centra en construir y evaluar un modelo de Regresión para predecir con precisión el precio final de venta de propiedades (ej. en la zona de Iowa, EEUU). El objetivo es identificar los factores más influyentes en la valoración de una vivienda, proporcionando una herramienta para la optimización de precios en el sector inmobiliario.

## Objetivo del Proyecto
El objetivo principal es predecir el valor de venta de una propiedad con alta precisión, ayudando a agentes inmobiliarios o compradores a:
<ol>
  <li>Establecer precios competitivos rápidamente.</li>
  <li>Identificar propiedades infravaloradas (oportunidades de compra) o sobrevaloradas.</li>
  <li>Optimizar las decisiones de inversión en el sector inmobiliario.</li>
</ol>

## Problema de Datos a Resolver
El problema es de Regresión, que es predecir un valor numérico continuo (el precio de la casa) basándose en un conjunto de características (tamaño, año de construcción, número de dormitorios, ubicación, etc.).
**Pregunta Clave:** ¿Cuál es la combinación óptima de características de la propiedad que maximiza la precisión en la predicción de su precio final de venta?

## Criterios de Éxito
Para que el proyecto se considere exitoso, el modelo debe cumplir con los siguientes criterios:
<ol>
  <li>Criterio Técnico Principal (Métricas): El modelo debe alcanzar un valor de RMSE (Root Mean Squared Error) que sea razonablemente bajo y competitivo con otros modelos de referencia (ej: un RMSE inferior al 15% de la media del precio de las viviendas).</li>
  <li>Criterio Técnico Secundario (Interpretación): El modelo debe ser capaz de identificar y cuantificar las variables más importantes que influyen en el precio (ej: demostrar que el área habitable tiene un peso mucho mayor que el número de baños).</li>
  <li>Criterio de Negocio: La predicción del modelo debe estar, en promedio, a no más de un ±5% del precio de venta real.</li>
</ol>


