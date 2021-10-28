# EANT

Python Data Analytics - pda-lm-n-294 - Grupo 1

## Tabla de Contenidos

- [Introducción](#introducción)
- [Datasets](#datasets)
- [Problemas Encontrados](#problemas)
- [Metodología](#metodo)
- [Herramientas](#herramientas)
- [Conclusiones](#conclusiones)
- [Dash](#dash)
- [Quiénes somos?](#quienes_somos)

<br>
<br>

<h3> Introducción:
<a name="introducción"></a>
</h3>

¿Qué nos proponemos con este proyecto?

La llegada del COVID-19 implica un antes y un después en distintos ámbitos, entre ellos el medio ambiente y transporte, dicho esto, en el marco del desafío final del programa Python Data Analytics en EANT nos planteamos la siguiente pregunta:

¿Cómo se vieron afectados los indicadores de contaminantes y transporte por el COVID-19 en el año 2020?

Para responder este interrogante analizamos los datos provistos por el gobierno de la ciudad de Buenos Aires.

https://data.buenosaires.gob.ar/dataset/

<h3> Datasets:
<a name="datasets"></a>
</h3>

- Bicicletas:

https://cdn.buenosaires.gob.ar/datosabiertos/datasets/transporte/bicicletas-publicas/recorridos-realizados-2020.zip

- Contaminantes:

https://cdn.buenosaires.gob.ar/datosabiertos/datasets/agencia-de-proteccion-ambiental/calidad-aire/calidad-aire.csv

- Casos de Covid:

https://sisa.msal.gov.ar/datos/descargas/covid-19/files/Covid19Casos.zip

- Subte:

https://cdn.buenosaires.gob.ar/datosabiertos/datasets/sbase/subte-viajes-molinetes/molinetes-2020.zip

- Vehículos:

https://cdn.buenosaires.gob.ar/datosabiertos/datasets/ausa/flujo-vehicular-por-unidades-peaje-ausa/flujo-vehicular-2020.csv

<h3> Problemas Encontrados:
<a name="problemas"></a>
</h3>

1 – No todos los datos se encuentran actualizados a la fecha o bien en los mismos periodos de tiempo, por lo que decidimos focalizar el análisis en el año 2020.

2 – Por tratarse de un trabajo en equipo donde necesitábamos avanzar en forma colaborativa nos encontramos con la necesidad de contar con una herramienta donde cada uno pueda ir desarrollando en paralelo una función y/o notebook, para solventar tal problemática adoptamos el uso de GitHub.

3 – En lo que respecta a la limpieza de los datos, normalizamos fechas, filtramos nulos e imputamos a los valores una escala del 1 al 10 facilitando su posterior comparación.

<br>

<h3> Metodología:
<a name="metodo"></a>
</h3>

- En lo que respecta a la limpieza y normalización de datos elegimos utilizar una notebook por cada uno de los datasets:

**[bicicletas.ipynb]**

**[contaminantes.ipynb]**

**[covid.ipynb]**

**[subte.ipynb]**

**[vehiculos.ipynb]**


- Una vez concluida la limpieza y normalización avanzamos con la carga de los datos ya procesados para su posterior visualización en la siguiente notebook:

**[pda-lm-n-294-1.ipynb]**

<br>
<br>

<h3> Herramientas:
<a name="herramientas"></a>
</h3>

<img src="https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/herramientas.jpg">

<br>
<br>

<h3> Conclusiones:
<a name="conclusiones"></a>
</h3>

- Por medio del análisis y visualización de datos confirmamos que la llegada del COVID-19 modificó los hábitos en el uso del transporte durante el año 2020, a partir de la cuarentena estricta, en el mes de abril se observa una caída total de la actividad y desde ese momento en adelante si bien hay un rebote en forma de V no todos los servicios volvieron a sus valores normales.

<img src="https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/pda-lm-n-294-1.jpeg">

<br>
<br>

<img src="https://github.com/fernandorgonzalez/cursos-eant-python_data_analytics-proyecto/blob/main/comparacion.jpg">

<br>

<h3> Dash:
<a name="dash"></a>
</h3>

- **[Heroku]**

<br>

<h3> Quiénes somos?
<a name="quienes_somos"></a>
</h3>

- **[Ezequiel Mariani]**

- **[Fernando Gonzalez]**

- **[Jonathan Rios]**

- **[Pablo Capozzi]**

- **[Paula Arrigoni]**

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
[Heroku]: https://proyecto-final-eant-2021.herokuapp.com/dash/
[GitHub]: https://github.com/jonatrios/proyecto-final-EANT-pda-lm-n-294













