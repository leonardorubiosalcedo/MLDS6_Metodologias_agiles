# Reporte del Modelo Baseline

Este documento contiene los resultados del modelo baseline.

## Descripción del modelo

El modelo contruido se vasa en TF-IDF (Term Frequency-Inverse Document Frequency) es una técnica utilizada en el procesamiento de texto y la recuperación de información. Se utiliza para evaluar la importancia relativa de una palabra (término) en un documento dentro de una colección de documentos.

## Variables de entrada

El modelo se entreno con las descripciones de las peliculas sin palabras vacias y en minusculas 

## Variable objetivo

El resultado del modelo objetivo es el titulo de la pelicula mas similar a la descripcion ingresada por el usuario 

## Evaluación del modelo

|modelo|descipcion ingresada|resultado esperado| resultado obtenido|
|-----------|-----------|-----------|-----------|
|TF-IDF|Gamoray Peter Quill tienen que defender el universo|Guardians of the Galaxy Vol. 3| Guardians of the Galaxy Vol. 3|
|TF-IDF|la historia de Indiana Jones| Indiana Jones and the Dial of Destiny|Indiana Jones and the Dial of Destiny|
|Levenshtein|Gamoray Peter Quill tienen que defender el universo|Guardians of the Galaxy Vol. 3| Saw X|
|Levenshtein|la historia de Indiana Jones| Indiana Jones and the Dial of Destiny|Mortal Kombat 2|


### Métricas de evaluación

La principal metrica de evaluacion son las pruebas integrales y unitarias realizadas al modelo 


## Análisis de los resultados

Con el modelo TF-IDF se obtienen resultados mejores que el entrenado basandose en el calculo de la distancia de Levenshtein

## Conclusiones

Conclusiones generales sobre el rendimiento del modelo baseline y posibles áreas de mejora.

## Referencias

[notebook](/../../scripts/training/Modelamiento_y_extraccion_.ipynb)
