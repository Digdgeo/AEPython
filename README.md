# AEPython

Repositorio para el contenido del curso de Análisis Espacial con Python del Gabinete de Fromación del CSIC (Estación Biológica de Doñana, Sevilla. 12-16/06/2023).

**Temario**:

# Día 1: Introducción al entorno Jupyter y a Python

En la primera parte del día hemos visto una introducción al entorno del ecosistema Jupyter (*Notebooks*, *Labs*, *Google Colabs* y *Jupyter Hubs*).   
En la segunda mitad hemos visto una (muy) breve introducción a Python en la que hemos visto los tipos de datos principales:  


* Creación de variables
* Strings
* Numbers
* Booleans
* Listas
* Tuplas
* Sets
* Diccionarios
* Bucles while y for
* Condicionales
* Manejo de errores
* Funciones
* Modulos
* Lectura y creación de archivos de texto

Y, como siempre ha sido, hemos terminado creando un script con el que jugar al juego popularizado por The Big Bang Theory  ***Rock, Paper, Scissors, Lizard, Spock***. En el archivo .ipynb se añade un ejemplo con un par de funciones más para seguir jugando sin tener que volver a ejecutar la celda. También se ha añadido la opción de sustituir los condicionales por un diccionario (+ pythonic). 

[Enlace al notebook completo del día 1](https://github.com/Digdgeo/AEPython/blob/main/Dia1/Day1_Completo.ipynb)


![](https://i.imgur.com/IZD1dlL.png)


# Día 2: Teledetección y Análisis Raster

En el segundo día del curso hemos visto una introducción a las clases en Python en primer lugar, para crear luego una clase Landsat soobre la que iremos trabajando en los próximos días para añadirle nuevos métodos y atributos.
Hemos visto también una breve introduccióna a la teledetección y a los Numpy Arrays que son la base para trabajar con datos raster (bandas de Landsat en nuestro caso) en Rasterio.   
Finalmente, comenzamos a ver Rasterio y creamos nuestro primer índice NDVI desde Python.

Notebooks:

[Python Classes](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%202/Python_Clasess.ipynb)   
[Clase Landsat](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%202/Clase_Landsat.ipynb)     
[Numpy Arrays](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%202/Intro_to_Numpy_Arrays.ipynb)     
[Introducción a Rasterio](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%202/Intro_to_Rasterio.ipynb)   

![](https://i.imgur.com/BxfFDfd.jpg)

# Día 3: Teledetección y Análisis Raster

Hemos ido avanzando (más despacio) en el análisis de imágenes de satélite y en nuestra clase Landsat en la que hemos introducido 2 métodos para calcular el NDVI y la Inundación. También hemos visto como aplicar una máscara de nubes a los productos obtenidos
Finalmente, hemos añadido otro método para aplicar los coeficientes para obtener los valores correctos d reflectividad de las bandas. 

[Enlace al notebook con la clase Landsat completa](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%203/Clase%20Landsat_completa.ipynb))

![](https://i.imgur.com/qg9QHlN.png)

# Día 4: Análisis Vectorial 

En el cuarto día (que ha ido regulinchis :_()) hemos visto una introducción a las librerías Shapely y Geopandas, y hemos estado jugando con las geometrías y los GeoDataFrames. También hemos visto como leer y escribir disintos tipos de archivos espaciales y como plotear los GeoDataframes directamente en el entorno de Jupyter en un mapa de Folium.

[Enlace al notebook del día 4](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%204/Dia_4_completo.ipynb)

![](https://i.imgur.com/lxGJ9yD.jpg)


# Día 5: Geemap

Sobrevivimos al final del curso más o menos bien. La primera mitad del día consisitó en repasar la clase del día anterior sobre operaciones vectoriales a las cuales se añadieron Spatial Join, Sampling points vector to raster, clip geometries y raster mask with polygons.   
También se vieron algunos ejemplos de la librería [osmnx](https://pypi.org/project/osmnx/) y terminamos el día y el curso curso aprendiendo un poco sobre [geemap](https://geemap.org/) y [ndvi2gif](https://pypi.org/project/ndvi2gif/). 

Notebooks:

[Análisis Vectorial Día 5](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%205/Dia_5_Vectorial.ipynb)   
[OSMNX](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%205/osmnx_aep.ipynb)     
[Geemap](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%205/SDM_geemap_course_day4.ipynb)     
[Ndvi2Gif](https://github.com/Digdgeo/AEPython/blob/main/D%C3%ADa%205/ndvi2gif.ipynb) 

![](https://i.imgur.com/GVyBwx1.jpg)


# Last Comments

A pesar de haber sido la primera edición y haber detectado varias cosas a corregir, hemos visto una introducción a Python y a el entorno de Jupyter, y hemos aprendido a trabajar con datos espaciales y a realizar análisis vectoriales y raster. La creación de la clase Landsat puede ser el punto de partida para muchos casos similares, cambiando tan solo breves fragmentos de código para adaptarlo a vuestras necesidades.

Sobre los datos vectoriales hemos visto como realizar con Python la mayoría de operaciones de Geoproceso que se suelen hacer en un GIS de escritorio, y sobre todo lo importante creo que es, el entender que hay detrás de esos datos, que no es más que la columna Geometry que hemos visto en mucho ejemplos con Shapely.

La presentación está en pdf en el repositorio y en [este enlace](https://slides.com/diegogarciadiaz/deck-9c545b/fullscreen) podéis encontrar la versión web, que es más completa ya que mantiene todo el html y los iframes que se pierden al pasarla a pdf.

Espero que os haya servido como una primera introducción a Geo-Python y que os pueda servir de algo en vuestro trabajo. Un placer haber compartido el curso con vosotros!


