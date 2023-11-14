# PROYECTO DE VISUALIZACIÓN-TABLEAU
# El impacto de la violencia de género en España
![](https://github.com/NoeRoson/Project_Visualization/blob/main/img/Portada_readme.png)


## Introducción

La **violencia de género** continúa siendo un fenómeno preocupante en la sociedad actual, tal y como reflejan las alarmantes cifras a las que tenemos acceso. 

Gracias a la investigación y accesibilidad de las mismas, se pueden llevar a cabo diversos proyectos de investigación y análisis de datos, los cuales impulsan el avance en este ámbito y ayudan a que, desde las instituciones públicas y privadas, se puedan llevar a cabo acciones de educación y prevención contra la violencia de género. 

El objetivo de este proyecto es, a través de la creación de gráficos sencillos y visuales, ayudar a comprender este fenómeno y fomentar la sensibilización y concienciación sobre el mismo.

## Proyecto de visualización

En primer lugar, se realiza una extracción de los [datos](https://github.com/NoeRoson/Project_Visualization/tree/main/data/output) que contienen la información necesarios para llevar a cabo las visualizaciones. Estos se obtienen del [Portal Estadístico Delegación del Gobierno contra la Violencia de Género](https://estadisticasviolenciagenero.igualdad.gob.es/) donde se consigue información acerca de:

- Denuncias interpuestas.
- Órdenes de protección decretadas.
- Víctimas mortales por violencia de género.
- Llamadas recibidas por el 016.


Asimismo, en el proyecto anterior se realiza scrapeo de la web del **Ministerio de Igualdad** con el objetivo de crear una tabla que contuviese las fechas de las campañas de prevención llevadas a cabo por este organismo. Tras una [limpieza](https://github.com/NoeRoson/Project_Visualization/blob/main/notebooks/Limpieza_datos.ipynb) sencilla de los datos extraídos, se importan a **Tableau Desktop** donde se iniciará el proceso de visualización.

Todos los datos obtenidos se relacionan a través del trimestre, mes y año, así como de la provincia en que sucede cada fenómeno. También se registran datos acerca de las edades de las víctimas y los agresores para conocer la correlación existente entre las mismas. 

Las visualizaciones creadas aportan una **visión a nivel global** del fenómeno de la violencia de género en nuestro país entre los años 2009 y 2023, aunque también permite **profundizar** en un estudio más concreto de cada una de las variables descritas anteriormente para cada año, trimestre, mes y provincia.

Para llevarlas a cabo, se ha utilizado la herramienta Tableau Desktop, con la que se pueden elaborar visualizaciones interactivas que permiten comprender el dato y aportar valor al análisis.

### [Dashboard mapas:](https://public.tableau.com/app/profile/noelia.roson/viz/Impacto_violencia_mapas/Mapas?publish=yes)
![](https://github.com/NoeRoson/Project_Visualization/blob/main/img/Dashboard1_maps.png)

Con esta visualización podemos observar para cada provincia, el total de órdenes de protección decretadas, llamadas al 016, víctimas mortales y denuncias interpuestas por violencia de género, filtrando en la ciudad, al igual que en los gráficos siguientes. 

### [Dashboard gráficos](https://public.tableau.com/app/profile/noelia.roson/viz/Impacto_violencia_genero/Grficos?publish=yes)
![](https://github.com/NoeRoson/Project_Visualization/blob/main/img/Dashboard2_graphics.png)

Estos gráficos nos aportan información sobre las campañas llevadas a cabo para la prevención de la violencia de género y las denuncias registradas por trimestre, donde se puede observar que el tercer trimestre siempre es el que mayores datos registra.

Por otro lado, tenemos una comparativa de las denuncias, llamadas al 016, órdenes de protección y víctimas mortales, según el año, siendo destacados los datos máximos y mínimos para cada una de ellas. 

Finalmente, podemos observar la correlación existente entre las edades víctima-agresor, viendo cómo aumentan los datos y la coincidencia en las edades centrales, especialmente entre los 30 y los 50.


## Recursos utilizados:

- [Tableau Desktop](https://www.tableau.com/es-es)
- [Pandas](https://pandas.pydata.org/)
- [Portal Estadístico Delegación del Gobierno contra la Violencia de Género](https://estadisticasviolenciagenero.igualdad.gob.es/)


