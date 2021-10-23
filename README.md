# EANT

Python Data Analytics - pda-lm-n-294 - Grupo 1

## Tabla de Contenidos

- [Introducción](#introducción)   
- [Metodología](#metodo)
- [Problemas Encontrados](#problemas)
- [Herramientas](#herramientas)
- [Conclusiones](#conclusiones)
    - [Punto 1](#c-uno)
    - [Punto 2](#c-dos)
- [Quiénes somos?](#quienes_somos)

<h3> Introducción:
<a name="introducción"></a>
</h3>

¿Qué nos proponemos con este proyecto?

La llegada del COVID-19 implica un antes y un después en distintos ámbitos, entre ellos el medio ambiente y transporte, dicho esto, en el marco del desafío final del programa Python Data Analytics en EANT nos planteamos la siguiente pregunta:

¿Cómo se vieron afectados los indicadores de contaminantes y transporte por el COVID-19 en el año 2020?

Para responder este interrogante analizamos los datos provistos por el gobierno de la ciudad de Buenos Aires.

<h3> Metodología:
<a name="metodo"></a>
</h3>

- La fuente de datos corresponde al sitio Buenos Aires Data:

https://data.buenosaires.gob.ar/dataset/

Bicicletas:

https://cdn.buenosaires.gob.ar/datosabiertos/datasets/transporte/bicicletas-publicas/recorridos-realizados-2020.zip

Contaminantes:

https://cdn.buenosaires.gob.ar/datosabiertos/datasets/agencia-de-proteccion-ambiental/calidad-aire/calidad-aire.csv

Casos de Covid:

https://sisa.msal.gov.ar/datos/descargas/covid-19/files/Covid19Casos.zip

Subte:

https://cdn.buenosaires.gob.ar/datosabiertos/datasets/sbase/subte-viajes-molinetes/molinetes-2020.zip

Vehículos:

https://cdn.buenosaires.gob.ar/datosabiertos/datasets/ausa/flujo-vehicular-por-unidades-peaje-ausa/flujo-vehicular-2020.csv

- En lo que respecta a la limpieza y normalización de datos elegimos utilizar una notebook por cada uno de los datasets:

**[bicicletas.ipynb]**

**[contaminantes.ipynb]**

**[covid.ipynb]**

**[subte.ipynb]**

**[vehiculos.ipynb]**


- Una vez concluida la limpieza y normalización avanzamos con la carga de los datos ya procesados para su posterior visualización en la siguiente notebook:

**[pda-lm-n-294-1.ipynb]**

<h3> Problemas Encontrados:
<a name="problemas"></a>
</h3>

1 – No todos los datos se encuentran actualizados a la fecha o bien en los mismos periodos de tiempo, por lo que decidimos focalizar el análisis en el año 2020.

2 – Por tratarse de un trabajo en equipo donde necesitábamos avanzar en forma colaborativa nos encontramos con la necesidad de contar con una herramienta donde cada uno pueda ir desarrollando en paralelo una función y/o notebook, para solventar tal problemática adoptamos el uso de GitHub.

3 – En lo que respecta a la limpieza de los datos, normalizamos las fechas, filtramos nulos e imputamos a los valores una escala del 1 al 10 facilitando su posterior comparación.

<h3> Herramientas:
<a name="herramientas"></a>
</h3>

<img src="https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/herramientas.jpg">

<h3> Conclusiones:
<a name="conclusiones"></a>
</h3>
<a name="c-uno"></a>
1 – De acuerdo a los indicadores observados en la ciudad de Buenos Aires durante el año 2020, el subte sufrió una caída del 77%, los vehículos se redujeron en un 10% y de manera sorprendente las bicicletas duplicaron sus valores.

<a name="c-dos"></a>

2 – Respecto al medio ambiente la buena noticia es que se presentó una reducción del 28% para los contaminantes del tipo PM10 en la estación ambiental Córdoba (partículas sólidas de polvo).

<img src="https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/pda-lm-n-294-1.jpeg">

<img src="https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/comparacion.jpg">

<h3> Quiénes somos?
<a name="quienes_somos"></a>
</h3>

**[Ezequiel Mariani]**

**[Fernando Gonzalez]**

**[Jonathan Rios]**

**[Pablo Capozzi]**

**[Paula Arrigoni]**

[GitHub]: https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto
[Dash]: https://plotly.com/dash/
[Flask]: https://flask.palletsprojects.com/en/2.0.x/
[Ezequiel Mariani]: https://www.linkedin.com/in/ezequiel-mariani/
[Fernando Gonzalez]: https://www.linkedin.com/in/fernandorodolfogonzalez/
[Jonathan Rios]: https://www.linkedin.com/in/jonathanrios11/
[Paula Arrigoni]: https://www.linkedin.com/in/maría-paula-arrigoni-6a306592
[Pablo Capozzi]: https://www.linkedin.com/in/ing-pablo-capozzi-3a347012/
[contaminantes.ipynb]: https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/contaminantes.ipynb
[covid.ipynb]: https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/covid.ipynb
[bicicletas.ipynb]: https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/bicicletas.ipynb
[subte.ipynb]: https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/subte.ipynb
[vehiculos.ipynb]: https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/vehiculos.ipynb
[pda-lm-n-294-1.ipynb]: https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/pda-lm-n-294-1.ipynb














