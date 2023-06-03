# Definición de los datos

## Origen de los datos

- [ ] Los datos se optuvieron desde la pagina dee IDMB(https://www.imdb.com) y se obtuvo por medio de web Scraping. 

## Especificación de los scripts para la carga de datos

- [ ] Los Script utilizados se encuentran en este repositorio en la parte de Scripts data_acquisition [WebScraping](/../../scripts/data_acquisition/WebScraping.ipynb). 
 
## Referencias a rutas o bases de datos origen y destino

- [ ] El origen de los datos son https://www.imdb.com/search/title/?title_type=feature&countries=us&languages=en&count=250&start=1&ref_=adv_nxt. desde la pagina inicial hasta la septima pagina 

### Rutas de origen de datos

- [ ] Especificar la ubicación de los archivos de origen de los datos.
- [ ] Debido a que los datos son extraidos por web Scraping las paginas se encuentran en formato html, por lo que se analiza con python BeautifulSoup
- [ ] Se ingresan las url de cada una de las paginas de imdb, se castean los datos por medio de la libreria imdb y se extraen los contenidos de los componentes de la pagina que contienen la informacion, luego se realiza una limpieza de texto por medio de expresiones regulares quitando todo lo que no sea texto y numeros

### Base de datos de destino

- [ ] Los datos una vez luego de extraidos y procesados se almacenaran en un storage en formato csv.
- [ ] Los datos para entrenar el modelo de guardaran en formato csv separado por comas(,).
