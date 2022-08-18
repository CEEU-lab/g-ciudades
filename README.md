# g-ciudades
Este repositorio condensa los 4 módulos dictados en el marco de la diplomatura en "Gestión de Ciudades" de la Escuela de Economía y Negocios de la Universidad de San Martín


GUIA DE USO DE LOS MATERIALES

La metodología propuesta para el curso consiste en recorrer conceptos fundamentales de la ciencia de datos a partir del análisis de distintos fenómenos urbanos.

Cada clase condensa recursos, estrategias e interpretaciones sobre código escrito en Python alrededor de una temática urbana.

Hay 4 directorios (1 por clase). En cada uno de ellos, se facilitarán los notebooks o cuadernos con el material de trabajo de las clases.

En los directorios “Material complementario” se disponibilizará material de apoyo, repaso o temáticas afines a lo trabajado en clase.


Clase 1 - Manipulación de datos

Temas
    • carga de datos,
    • data types (str, int, float, bool)
    • for loops y listas por comprensión,
    • colecciones (data frames, Series, listas, tuplas y diccionarios)
    • sentencias if, elif, else
    • indexing y slicing
    • groupby
    • valores nulos e imputación
    • funciones regulares y anónimas
    • Views y copies
    • Errores y warnings

	El listado de temas se trabajará sobre una base de datos censal.
Disponible en notebook clase 1

En el material complementario se ofrecen algunos ejemplos sobre cómo trabajar computacionalmente problemas de accesibilidad. También se facilita material de repaso sobre manejo de arrays, funciones y estructuras de datos nativas de Python.

Clase 2 - Principios generales de visualización

Temas
    • Matplotlib:
        ◦ método plot
        ◦ pyplot + figuras/ejes,
        ◦ histogramas y distribuciones (densidad y chi cuadrado)
        ◦ Tests de asociación
        ◦ barras, líneas y tortas  
Disponible en  notebook clase 2 - matplotlib

    • Seaborn:
        ◦ series de tiempo,
        ◦ FacetGrid
        ◦ Análisis multidimensional.
        ◦ relplots, regplots y heatmaps  
Disponible en  notebook clase 2 - seaborn

El listado de temas se trabajará sobre la base de datos de una encuesta focalizando en aspectos de vivienda.
Se agregan casos de uso adicionales con ejemplos de visualizaciones sobre una red de transporte - aquí notebook -

El material complementario ofrece una revisión profunda sobre “funciones regulares y anónimas” en el siguiente cuaderno de repaso. También se facilitan instrucciones para trabajar con el libro scientific-visualization en este cuaderno de repaso.
También se ofrece material complementario con ejemplos y ejercicios prácticos aplicados a análisis de mercado inmobiliario en este directorio.

Clase 3 - Análisis espacial

Temas
    • Shapely (Line, Polygon, Point geom)
    • CRS proyectados y geográficos
    • Operaciones con geometrías: join, overlay y dissolve
    • El método plot de una GeoSerie
    • Mapas estáticos con contextily
    • mapas dinámicos con folium y leaflet
    • mapas dinámicos con  plotly express
    • Geocoding

El listado de temas se trabajará sobre un registro de usuarios del servicio público “Ecobici” de la Ciudad de Buenos Aires - disponible en notebook clase 3. Asimismo, se facilitan ejemplos con visualizaciones dinámicas en los cuadernos de visualizaciones I y II.

En el material complementario podrán encontrar ejemplos de uso para normalizar, geocodificar direcciones y enriquecer entidades geográficas en este y este cuaderno.

Clase 4 - Machine learning

Temas

    • sklearn (logistic regression + train/test split)
    • statsmodels (linear regression)
    • h3 (geometrías hexagonales)
    • Clustering DBSCAN

El listado de temas se trabajará sobre un caso de zonificación en este cuaderno y otro de economías de aglomeración en este cuaderno.

Bibliografía sugerida

    • Arribas Bel, Dani. Geographic Data Science, the course. 2021 - link
    • Ciudad Hub - El podcast de las ciudades - link
    • Comunidad argentina de Inteligencia Artificial - link
    • Boeing, Geoff. Advanced Urban Analytics - link
    • Duarte & Desouza. Data Science and Cities: A critical approach, 2020 - link
    • Forrest, Matt. 75+ Geospatial Python and Spatial Data Science Resources and Guides, 2021 - link
    • Python for Data Science Handbook, O’Reilly - link
    • Rougier, Nicolas. Scientific visualization book: Python + Matplotlib, 2021 - link
    • Sosa Escudero, Walter. Conferencia sobre Big Data. 2021 - link
    • Zed A. Shaw. Learning Python, the hard way, 2018 - link
Ejercicios resueltos en por Barton Poulson acá
