# EANT - Grupo 1
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/84/Open_data_large_color_%28vector%29.svg/193px-Open_data_large_color_%28vector%29.svg.png" align="right"
     alt="Size Limit logo by Anton Lovchikov" width="160" height="178">
2021 Python Data Analytics (pda-lm-n-294)

## Tabla de Contenidos

- [Introducción](#introducción)
   
- [Conclusiones](#conclusiones)
    - [Punto 1](#c-uno)
    - [Punto 2](#c-dos)
- [Metodología](#metodo)
- [Problemas Encontrados](#problemas)
- [Herramientas](#herramientas)
- [Nosotros](#nosotros)

<h3> Introducción:
<a name="introducción"></a>
</h3>

¿Qué nos proponemos con este proyecto?

En el marco del desafío final del programa de Data Analytics de EANT, nos planteamos las siguiente pregunta:

¿Cómo se vieron afectados los indicadores de contaminantes y transporte por el COVID-19 en el año 2020?

Para responder esta pregunta analizamos los set de datos provistos por el gobierno de la ciudad de buenos aires.

<h3> Conclusiones:
<a name="conclusiones"></a>
</h3>
<a name="c-uno"></a>
1 – De acuerdo a los indicadores observados podemos decir que durante el año 2020 tomando como referencia el incio y fin del periodo hay transportes como el subte que sufrieron una disminución de un 77% en su uso, otros como los vehiculos se reducieron en un 10% pero la buena noticia para el medio ambiente es que las bicicletas duplicaron sus valores.


<a name="c-dos"></a>
2 – De hecho, el cambio en el uso del transporte favorece al medio ambiente con una reducción del 28% para los contaminantes.

<img src="https://github.com/jonatrios/proyecto-final-EANT-pda-lm-n-294/blob/main/dash_application/assets/pda-lm-n-294-1%20(1)_page-0001.jpg">

<h3> Metodología:
<a name="metodo"></a>
</h3>

- La fuente de datos corresponde al gobierno de la ciudad de Buenos Aires, puntualmente el sitio Buenos Aires Data:

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

1 – No todos los sets de datos se encuentran actualizados a la fecha o bien en los mismos periodos de tiempo, por lo que decidimos focalizar el análisis en el año 2020

2 – Por tratarse de un trabajo en equipo donde necesitábamos avanzar en forma colaborativa adoptamos el uso de la herramienta GitHub

3 – El set de datos de origen cuenta con información dispar en distintas escalas por lo que en la normalización elegimos una escala del 1 al 10 y de esa forma facilitamos la posterior comparación.

<h3> Herramientas:
<a name="herramientas"></a>
</h3>

#### Librerías:

```python
import matplotlib.pyplot as plt
import numpy as np
import plotly.express as px
import pandas as pd
import seaborn as sns
```

**[GitHub]** como gestor de versiones para nuestros analisis

**[Dash]** para la representacion de las graficas obtenidas gracias al procesamiento y entendimiento de los datos

**[Flask]** como server, ya que app de Dash esta montada sobre Flask permiento que ambas se mantengan separadas, haciendo mas robusta la aplicacion


<h3> Nosotros:
<a name="nosotros"></a>
</h3>

Les dejamos los links hacia nuestros perfiles de LinkedIn!

**[Ezequiel Mariani]**

**[Fernando Gonzalez]**

**[Jonathan Rios]**

**[Paula Arrigoni]**

**[Pablo Capozzi]**

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














