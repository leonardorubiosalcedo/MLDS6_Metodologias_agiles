# Reporte de Datos

Este documento contiene los resultados del análisis exploratorio de datos.

## Resumen general de los datos

Se cuenta con la descripcion de 1.750 peliculas de diversos generos, con un corpues de 31.784 palabras que al momento de ser agrupadas por su origen generan un corpus de 5.706 palabras. 

## Resumen de calidad de los datos

- Antes de la limpieza del texto se contaba con un corpus de datos de 51.452 palabras y despues de la limpieza de palabras vacias se convierte en 31.784. 

- Al momento de analizar los origenes de las palabras se encontraron solo 5.706 origenes de palabras.

- Las palabras mas repetidas expresan el genero de las peliculas analizadas.

- En la nube de palabras se muestra la misma tendencia a los tipo de peliculas y expresiones como life, must, become.
<br>

## Variable objetivo

La variable objetivo es simplificar los textos y encontrar una convergencia de temas y expresiones, simplificando el lenguaje

## Variables individuales
<br>

- Se aplico la limpieza de los datos quitando las palabras vacias y se genero un corpus a partir de ella.<br>
    ![Nube de palabras](nube.PNG)
    <br>
- Al momento de analizar el corpus y el origen de los datos se obtuvo el top 10 de las palabras mas <br>
    <br>

| Corpus  Palabras  | Conteo |	Corpus  Origen palabras| Conteo	|		
|-------------------|--------|-------------------------|--------|		
|	drama	        |810	|	drama	               |810	|
|	action	        |659	|	action	               |664	|
|	adventure	    |562	|	adventur               |577	|
|	comedy	        |537	|	comedi	               |537	|
|	thriller	    |354	|	thriller	           |354	|
|	crime	        |317	|	crime	               |320	|
|	family	        |222	|	mysteri	               |252	|
|	horror	        |218	|	famili	               |237	|
|	scifi	        |217	|	horror	               |218	|
|	romance	        |196	|	scifi	               |217	|

Para mas informacion el notebook de exploracion y limpieza de los datos ingresar [aqui](../../scripts/preprocessing/Preprocesamiento_y_analisis_exploratorio.ipynb)
<br>

## Ranking de variables

Al momento de solo contar con dos variables, descripcion de la pelicula y titulo de la pelicula no se puede realizar una correlacion o reduccion de variables
<br>

## Relación entre variables explicativas y variable objetivo

Al momento de solo contar con dos variables, descripcion de la pelicula y titulo de la pelicula no se puede realizar una correlacion de las variables
