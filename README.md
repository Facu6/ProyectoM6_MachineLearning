# Descripción del Proyecto
Este proyecto tiene como objetivo realizar un análisis de mercado para una importante automotriz china que desea ingresar al mercado de automóviles. Nuestro objetivo es analizar las características de los vehículos presentes en el mercado actual para ayudar a la automotriz a ajustar su oferta a la demanda y cotizar correctamente sus vehículos. Para ello, hemos implementado dos modelos de machine learning: uno de clasificación y uno de regresión.

# Estructura del Proyecto
## El proyecto se divide en las siguientes secciones:

- Análisis Exploratorio de Datos (EDA): Incluye la exploración y visualización de las características de los vehículos y sus precios de venta.
- Preprocesamiento de Datos: Limpieza y preparación de los datos para ser utilizados en los modelos predictivos.
### Modelos Predictivos:
- Modelo de Clasificación: Utiliza regresión logística para clasificar los vehículos en baratos y caros, basándose en la mediana de los precios.
- Modelo de Regresión: Utiliza regresión lineal para predecir el precio final de los vehículos.

### Archivos de Predicción
Los resultados de las predicciones se entregan en dos archivos de texto plano:

- y_pred_clasificación.txt: Contiene las predicciones del modelo de clasificación.
- y_pred_regresión.txt: Contiene las predicciones del modelo de regresión.
### Instrucciones para Reproducir el Proyecto
Requisitos Previos:

Python 3.x
Bibliotecas: pandas, numpy, scikit-learn, matplotlib, seaborn

### Cargar y Preprocesar los Datos:

- Cargar los datos desde un archivo CSV utilizando pandas.
- Realizar un análisis exploratorio de los datos para entender las características y la distribución de los precios.
- Preprocesar los datos: manejo de valores nulos, codificación de variables categóricas, escalado de características, etc.
## Modelo de Clasificación:

Dividir los datos en conjuntos de entrenamiento y prueba.
Implementar un modelo de regresión logística para clasificar los vehículos en baratos y caros.
Entrenar el modelo con los datos de entrenamiento.
Evaluar el modelo con los datos de prueba.
Guardar las predicciones en y_pred_clasificación.txt.

## Modelo de Regresión:
Dividir los datos en conjuntos de entrenamiento y prueba.
Implementar un modelo de regresión lineal para predecir el precio de los vehículos.
Entrenar el modelo con los datos de entrenamiento.
Evaluar el modelo con los datos de prueba.
Guardar las predicciones en y_pred_regresión.txt.