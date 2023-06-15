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
