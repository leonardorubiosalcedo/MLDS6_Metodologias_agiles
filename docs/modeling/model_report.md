# Reporte del Modelo Final

## Resumen Ejecutivo

- Se desarrollaron modelos de similitud de texto los cuales fueron:
    * TF-IDF: Es un modelo basado en la frecuencia con la que un termino aparece en el documento 
    * Distancia de Levenshtein: Es un modelo que utiliza la medida para cuantificar la diferencia entre dos cadenas de texto

## Descripción del Problema

El modelo busca encontrar el titulo de la pelicula mas similar a la descripcion ingresada por el usuario

## Descripción del Modelo

El modelo que obtuvo el mejor resultado fue el TF-IDF, el cual se entreno con las descripciones de las peliculas. Se realizo una limpieza de estas descripciones y se genero una clase con dos funciones, una encargada de el entrenamiento del modelo y la otra encargada de la busqueda del texto mas similar. 
Tambien se genero una funcion que consume esta clase y antes realiza la traduccion del texto a ingles.

## Evaluación del Modelo

Se evaluo el modelo con la busqueda de 2 peliculas y la evidencia se encuentra en el [notebook](/../../scripts/training/Modelamiento_y_extraccion_.ipynb)

## Conclusiones y Recomendaciones

EL modelo cuenta con la limitante de depender de la funcion de traduccion del texto de español a ingles, tambien se evidencia que se obtuvo un mejor resultado con el modelo TF-IDF que el que se basa en el calculo de Distancia de Levenshtein 

## Referencias

[notebook](/../../scripts/training/Modelamiento_y_extraccion_.ipynb)