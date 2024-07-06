# Proyecto: Predicción de la Cantidad de Pedidos de Taxis

## Descripción del Proyecto
La compañía Sweet Lift Taxi ha recopilado datos históricos sobre pedidos de taxis en los aeropuertos. Para atraer a más conductores durante las horas pico, necesitamos predecir la cantidad de pedidos de taxis para la próxima hora. Construye un modelo para dicha predicción.

### Objetivo
Predecir la cantidad de pedidos de taxis para la próxima hora, asegurando que la métrica RECM en el conjunto de prueba no sea superior a 48.

## Instrucciones del Proyecto
1. Descarga los datos y remuestréalos de tal forma que cada punto de datos de los datos originales caigan dentro de intervalos de una hora.
2. Analiza los datos.
3. Entrena diferentes modelos con diferentes hiperparámetros. La muestra de prueba debe ser el 10% del conjunto de datos inicial.
4. Prueba los datos usando la muestra de prueba y proporciona una conclusión.

## Descripción de Datos
- **Archivo**: `/datasets/taxi.csv`
- **Columna de Interés**: `num_orders` (Número de pedidos)

## Evaluación del Proyecto
Los revisores examinarán tu proyecto considerando los siguientes criterios:

1. ¿Seguiste todos los pasos de las instrucciones?
2. ¿Cómo preparaste los datos?
3. ¿Qué modelos e hiperparámetros consideraste?
4. ¿Conseguiste evitar la duplicación del código?
5. ¿Cuáles fueron tus hallazgos?
6. ¿Mantuviste la estructura del proyecto?
7. ¿Mantuviste el código limpio?

## Estructura del Proyecto

### 1. Preparación de los Datos
- Cargar los datos.
- Remuestrear los datos para que cada punto caiga en intervalos de una hora.
- Identificar y manejar valores nulos o inconsistencias.

### 2. Análisis de los Datos
- Descripción estadística de los datos.
- Visualización de los datos para identificar patrones y tendencias.
- Análisis de correlación entre las variables.

### 3. Entrenamiento del Modelo
- Dividir los datos en conjunto de entrenamiento y prueba (90% y 10% respectivamente).
- Entrenar varios modelos (p.ej., regresión lineal, random forest, LightGBM).
- Realizar ajuste de hiperparámetros utilizando técnicas como grid search o random search.

### 4. Evaluación del Modelo
- Evaluar los modelos en el conjunto de prueba utilizando la métrica RECM.
- Seleccionar el mejor modelo basado en la métrica y desempeño.

### 5. Conclusiones
- Resumen de los hallazgos.
- Discusión sobre el desempeño del modelo seleccionado.
- Recomendaciones para posibles mejoras.

¡Buena suerte!
