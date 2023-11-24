# Proyecto Integrador de Análisis y Predicción de Precios de Vehículos

Este proyecto tiene como objetivo analizar y predecir los precios de los vehículos en el mercado automotor. Se han utilizado técnicas de análisis exploratorio de datos y machine learning para clasificar vehículos en categorías de gama alta y baja, así como predecir los precios finales de los vehículos.

## Contenido del repositorio
- notebook.ipynb: Jupyter Notebook que contiene todo el código del proyecto, desde la carga de datos hasta la evaluación de los modelos.
- dataset.csv: Archivo CSV que contiene los datos utilizados en el proyecto.
- README.md: Este archivo.

## Estructura del Proyecto
1. Análisis Exploratorio de Datos
En esta fase, se exploraron las características de los vehículos presentes en el mercado. Se realizaron visualizaciones y análisis estadísticos para comprender la distribución de precios y las relaciones entre variables clave.

2. Preparación de Datos
Se llevaron a cabo procesos de limpieza de datos, manejo de variables categóricas y selección de características relevantes. Los datos se dividieron en conjuntos de entrenamiento y prueba, y se escaló las características cuando fue necesario.

3. Modelamiento y Evaluación
Se implementaron dos modelos de machine learning:
- Modelo de Regresión: Para predecir el precio final de los vehículos.
- Modelo de Clasificación: Para clasificar vehículos en categorías de gama alta y baja.

## Variables utilizadas
- citympg: Consumo en ciudad en millas por galón de combustible.
- highwaympg: Consumo en ruta en millas por galón de combustible.
- fueltype_encoded: Variable categórica codificada para el tipo de combustible.
- horsepower_encoded: Variable categórica codificada para la potencia del vehículo en caballos de fuerza (HP).

Estas variables se seleccionaron después de un análisis detallado y fueron consideradas relevantes para la predicción de precios y la clasificación de la gama de vehículos.
