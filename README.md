# Predicción de Género Basada en Nombres con Naive Bayes Multinomial

### Descripción
Este proyecto utiliza el algoritmo de Naive Bayes Multinomial para predecir el género de una persona basado en sus dos primeros nombres. El modelo se entrenó con un dataset específico y se implementó en Python, usando tanto un script (Prediccion_genero.py) como un Jupyter o Colab (NOTEBOOK_GENERO.ipynb). Este repositorio busca proporcionar una herramienta accesible y fácil de usar que pueda predecir con una cierta precisión del 91.48% el género basado exclusivamente en los nombres proporcionados.

## Instalación
Para instalar y ejecutar este proyecto, sigue los siguientes pasos:

1. Clona este repositorio:

```
git clone https://github.com/JosueAVD27/Predicciones-de-Genero.git
```

2. Instala las dependencias necesarias:
```
pip install -r requirements.txt
```


## Uso
### Script
Para usar el modelo para predecir el género a través del script, ejecuta:

```
python Prediccion_genero.py
```

### Jupyter Notebook
Para explorar el proceso de construcción del modelo y realizar predicciones interactivas:

```
jupyter notebook NOTEBOOK_GENERO.ipynb
```

Abre el archivo NOTEBOOK_GENERO.ipynb en Jupyter Notebook o JupyterLab para ver el código, las explicaciones, y ejecutarlo por ti mismo.

### Google Colab
Solo importa el archivo de NOTEBOOK_GENERO.ipynb


## Contenido del Notebook
El notebook incluye varias secciones importantes:

- Carga de Datos: Importación de datos y visualización inicial.
- Preprocesamiento de Datos: Preparación y limpieza de datos para el modelado.
- Vectorización: Conversión de los nombres a vectores numéricos que pueden ser utilizados por el modelo.
- Entrenamiento del Modelo: Detalles sobre cómo el modelo es entrenado, incluyendo la selección de parámetros.
- Evaluación del Modelo: Evaluación del modelo usando métricas estándar como la precisión y la matriz de confusión.
- Predicción: Cómo hacer predicciones con el modelo entrenado.

## Cómo funciona
Este modelo utiliza el algoritmo Naive Bayes Multinomial, apropiado para la clasificación con características discretas (como palabras en textos). Detalles adicionales sobre la implementación y la teoría del modelo se pueden encontrar dentro del Notebook proporcionado.



## Contribuir
Si deseas contribuir a este proyecto, por favor sigue los siguientes pasos:

- Fork el repositorio.
- Crea una nueva rama para tus cambios.
- Implementa tus cambios y escribe pruebas cuando sea posible.
- Envía un pull request con tus cambios.


## Licencia
Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE en este repositorio para más información.

