# Project Charter - Entendimiento del Negocio

## Nombre del Proyecto

NLP - Recomendación de películas

## Objetivo del Proyecto

Dar la opción a personas de obtener recomendaciones de películas a partir de una descripción ingresada

## Alcance del Proyecto

### Incluye:

- Descripción de los datos disponibles
    Se cuenta con datos de 1750 títulos y descripciones de películas, extraídos desde IMDB por medio de web scraping
- [Descripción de los resultados esperados]
    El usuario del aplicativo ingresara una pequeña descripción y seleccionara la cantidad de recomendaciones que desea obtener 
- [Criterios de éxito del proyecto]

### Excluye:

- Solo se cuenta con descripciones de películas en español
- Se cuentan con datos extraídos hasta el día 3 de junio de 2023
- La descripción ingresada por el usuario no debe superar los 250 caracteres 
- La App admitirá máxima 10 recomendaciones y mínima 1

## Metodología

Para el desarrollo de este proyecto se utilizará la metodología **TDSP** debido a que proporciona una estructura para el ciclo de vida completo para proyectos de machine learning, lo aplicaremos desde la concepción hasta la implementación y mantenimiento. Se va a tratar las siguientes actividades en las 7 fases que componen la metodología:

1. Definición del problema: Comprender los objetivos del proyecto, identificar las necesidades del negocio y definir el problema de ciencia de datos a resolver.
2. Adquisición y exploración de datos: Generar el algoritmo de web scraping y tratamiento inicial de datos 
3. Modelado de datos: Diseñar, desarrollar y evaluar modelos de NLP para identificar verosimilitud.
4. Desarrollo de soluciones: Construir y validar la API utilizando los modelos y algoritmos desarrollados.
5. Evaluación: Evaluar el rendimiento de la API desarrollada y realizar mejoras si es necesario.
6. Despliegue: Desplegar la solución en un entorno de cloud.
7. Operaciones y mantenimiento: Monitorear y mantener la solución en el ambiente desplegado.

## Cronograma

| Etapa | Duración Estimada | Fechas |
|------|---------|-------|
| Entendimiento del negocio y carga de datos | 2 semanas | del 20 de mayo al 3 de junio |
| Preprocesamiento, análisis exploratorio | 1 semanas | del 4 de mayo al 11 de mayo |
| Modelamiento y extracción de características | 1 semanas | del 12 de junio al 19 de mayo |
| Despliegue | 2 semanas | del 20 de mayo al 4 de junio |
| Evaluación y entrega final | 1 semanas | del 5 de junio|

Hay que tener en cuenta que estas fechas son de ejemplo, estas deben ajustarse de acuerdo al proyecto.

## Equipo del Proyecto

- Leonardo Rubio ingeniero de datos

## Presupuesto

| Concepto   | precio |
|---------------|-------|
| Salario gerente de proyectos (tiempo parcial) | 3.500.000 |
| Salario desarrolladores | 4.500.000 |
| Infraestructura | 2.500.000 |
| Costos logísticos| 800.000 |

## Stakeholders

- [Nombre y cargo de los stakeholders del proyecto]
- [Descripción de la relación con los stakeholders]
- [Expectativas de los stakeholders]

## Aprobaciones

- [Nombre y cargo del aprobador del proyecto]
- [Firma del aprobador]
- [Fecha de aprobación]
