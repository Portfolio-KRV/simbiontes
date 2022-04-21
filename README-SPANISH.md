# Simbiontes
Desarrollado en el curso Aprendizaje Automático UTFSM por: Diego Quezada y Kevin Reyes.
## Objetivos
- Predecir enfermedades dado un conjunto de datos asociados al microbioma humano.
- Comparar desempeño de clasificadores de aprendizaje automático.
- Inferir la importancia de los pérfiles microbiómicos para detectar las distintas enfermedades.
- Identificar sesgos presentes en los datos mediante el análisis exploratorio de datos.

## Descripción
Modelo predictivo para predecir enfermedades en base a datos de la microbiota de un paciente, utilizando métodos de aprendizaje automático en conjunto con herramientas de exploración y preprocesamiento de datos.

## Conclusiones
- Características categóricas predictoras donde una o más de sus clases están presentes exclusivamente en un subconjunto de las clases a predecir podrían introducir sesgos al modelo predictivo.
- Aplicar reducción de dimensionalidad en conjuntos de datos donde el tamaño de la muestra es acotado y la dimensionalidad del espacio de características podría mejorar la capacidad de generalización del modelo.
- Para cada enfermedad existe una especie de microorganismo de gran importancia para predecir la enfermedad, acompañado de un conjunto de cepas específicas.
- En conjunto de datos pequeños se debe evitar eliminar registros completos, en su lugar se debe busdar la forma adecuada de reemplazar estos valores y así tener una mayor cantidad de datos disponibles.

## Stack de tecnologías
- Numpy.
- Pandas.
- Matplotlib.
- Plotly.
- Scikit-learn.
- XGBoost.
