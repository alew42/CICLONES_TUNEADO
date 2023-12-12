# CICLONES_TUNEADO
**FACULTAD**** DE INGENIERIA CIVIL**
<br>**INGENIERO**** TOPOGRAFO ****GEOMATICO**
<br>**"categoría de los ciclones en los últimos 3 años basada en la velocidad de sus vientos****"**
<br>**Autores** :
<br>Hernán Córdova Araiza
<br>Rene Antonio Alfaro Ríos
<br>Edgar Oswaldo Sebastián López
<br>**Alejandra Atanacio Mancilla**
<br> **Grado y**** Grupo**: 3ºB
<br>**Asesor** :Sebastián Gonzales Zepeda

**Abstrac**

En este proyecto se buscó resolver la problemática de clasificar una gran cantidad de datos sobre ciclones, con respecto a la velocidad de sus vientos.

Estos datos fueron tomados entre los años 2020 a 2023 donde se recaudaron 101 datos que fueron clasificados por un programa creado con anterioridad para resolver esta problemática.

**Resumen**

Las clasificaciones de los ciclones según la velocidad de sus vientos proporcionan una manera crucial de evaluar su potencial impacto por lo que en el presente proyecto realizamos un programa para obtener las categorías de cada ciclón con base a la velocidad de sus vientos registrada en los últimos tres años. Obtuvimos la información en páginas confiables donde se nos proporcionaban el nombre del ciclón y sus velocidades, generando una tabla de Excel con estos siendo 101 datos entre ciclones y tormentas tropicales en el transcurso de estos últimos 3 años.

También se investigaron las diversas categorías y su clasificación en velocidad de los vientos para que el programa pudiera clasificarlos con base a esos datos.

**Introducción**

Los ciclones son fenómenos meteorológicos de gran escala caracterizados por vientos fuertes. Estos fenómenos pueden ser extremadamente poderosos y están asociados con una variedad de condiciones climáticas, como lluvias intensas, tormentas, marejadas ciclónicas, etc.

La clasificación de los ciclones en función de la velocidad de sus vientos es fundamental para comprender su potencial destructivo y su impacto en las áreas afectadas. Se dividen principalmente en categorías según la velocidad del viento que van desde 1 hasta 5, siendo esta última la más devastadora.

**Desarrollo**

Empezamos obteniendo los datos de internet a cerca de las velocidades en Km/h de los ciclones durante los últimos 3 años y agruparlos en una tabla de datos de Excel ordenados, realizamos un código que nos determine la categoría de cada uno

En este programa primero importamos librerías como pandas para el manejo de datos que nos definirá la función "categorizar\_ciclon" donde agregamos la velocidad de los vientos con respecto a su categoría.

Para poder cargar los datos utilizamos la librería files que nos permitirá ingresar un documento Excel con las velocidades de viento en los ciclones.

Finalmente, el programa nos entregara un listado del nombre del ciclón, su velocidad y su categoría.

**Manejo de datos**

Generamos una tabla con los 101 datos agrupados de manera ordenada en una tabla de Excel a la que mediante el programa con la librería de files tendrá acceso para realizar la categorización de cada uno.

| DANIELLE | 110 |
| --- | --- |
| EARL | 110 |
| BLANCA | 110 |
| CARLOS | 115 |
| DT 17 | 120 |
| PATRICIA | 120 |
| BORIS | 120 |
| OOLIE | 120 |
| TRUDY | 120 |
| AGATHA | 120 |
| KAY | 130 |
| LESTER | 130 |
| ORLENE | 130 |
| ROSLYN | 130 |
| CUATRO | 130 |
| USA | 140 |
| DOLORES | 140 |
| NORA | 140 |
| OLAF | 150 |
| PAMELA | 150 |
| RICK | 150 |
| GRACE | 155 |
| HERNAN | 160 |
| CRISTOBAL | 165 |
| HANNA | 165 |
| NANA | 165 |
| GAMMA | 165 |
| DELTA | 175 |
| ZETA | 185 |
| LORENA | 195 |
| NARDA | 195 |
| DIECICIETE-E | 205 |
| PRICILLA | 240 |
| FERNAND | 260 |

|

| **Nombre del ciclon** | **Velocidad**** Viento** |
| --- | --- |
| BUD | 25 |
| --- | --- |
| DIECINUEVE | 45 |
| --- | --- |
| ROSA | 45 |
| --- | --- |
| SERGIO | 45 |
| --- | --- |
| VICENTE | 45 |
| --- | --- |
| WILLA | 45 |
| --- | --- |
| BEATRIZ | 55 |
| --- | --- |
| CALVIN | 55 |
| --- | --- |
| LIDIA | 55 |
| --- | --- |
| MAX | 55 |
| --- | --- |
| FRANKLIN | 55 |
| --- | --- |
| KATIA | 55 |
| --- | --- |
| UNO E | 55 |
| --- | --- |
| JAVIER | 55 |
| --- | --- |
| NEWTON | 55 |
| --- | --- |
| COLIN | 55 |
| --- | --- |
| DANIELLE | 55 |
| --- | --- |
| EARL | 55 |
| --- | --- |
| BLANCA | 55 |
| --- | --- |
| CARLOS | 55 |
| --- | --- |
| DT 16 | 55 |
| --- | --- |
| PATRICIA | 55 |
| --- | --- |
| BORIS | 55 |
| --- | --- |
| OOLIE | 55 |
| --- | --- |
| TRUDY | 65 |
| --- | --- |
| AGATHA | 65 |
| --- | --- |
| KAY | 65 |
| --- | --- |
| LESTER | 65 |
| --- | --- |
| ORLENE | 65 |
| --- | --- |
| ROSLYN | 65 |
| --- | --- |
| CUATRO | 65 |
| --- | --- |
| USA | 65 |
| --- | --- |
| DOLORES | 65 |
| --- | --- |

NORA | 65 |
| --- | --- |
| OLAF | 65 |
| PAMELA | 65 |
| RICK | 65 |
| GRACE | 70 |
| HERNAN | 75 |
| CRISTOBAL | 75 |
| HANNA | 75 |
| NANA | 75 |
| GAMMA | 75 |
| DELTA | 75 |
| ZETA | 75 |
| LORENA | 75 |
| NARDA | 75 |
| DIECICIETE-E | 75 |
| PRICILLA | 85 |
| FERNAND | 85 |
| BUD | 85 |
| DIECINUEVE | 85 |
| ROSA | 90 |
| SERGIO | 95 |
| VICENTE | 95 |
| WILLA | 95 |
| BEATRIZ | 95 |
| CALVIN | 95 |
| LIDIA | 95 |
| MAX | 100 |
| FRANKLIN | 100 |
| KATIA | 100 |
| UNO E | 100 |
| JAVIER | 100 |
| NEWTON | 100 |
| COLIN | 100 |

**Código**

from google.colab import files

import pandas as pd

defcategorizar\_ciclon(velocidad\_viento):

    if velocidad\_viento \< 118:

        return"Tormenta tropical"

    elif velocidad\_viento \< 153:

        return"categoria 1"

    elif velocidad\_viento \< 177:

        return"categoria 2"

    elif velocidad\_viento \< 208:

        return"categoria 3"

    elif velocidad\_viento \< 251:

        return"categoria 4"

    else:

        return"categoria 5"

archivo\_cargado = files.upload()

nombre\_archivo = list(archivo\_cargado.keys())[0]

datos\_ciclones = pd.read\_excel(nombre\_archivo)

if'VelocidadViento'in datos\_ciclones.columns and'NombreCiclon'in datos\_ciclones.columns:

    datos\_ciclones['Categoria'] = datos\_ciclones['VelocidadViento'].apply(categorizar\_ciclon)

    archivo\_salida = 'datos\_ciclones\_con\_categoria.xlsx'

    datos\_ciclones.to\_excel(archivo\_salida, index=False)

    print(f'Se ha agregado la columna de categoría y se ha guardado en {archivo\_salida}')

    lista\_info\_ciclones = list(zip(datos\_ciclones['NombreCiclon'], datos\_ciclones['VelocidadViento'], datos\_ciclones['Categoria']))

    for nombre, velocidad, categoria in lista\_info\_ciclones:

        print(f"Ciclón: {nombre} - Velocidad de viento: {velocidad} km/h - Categoría: {categoria}")

else:

    print("La columna 'VelocidadViento' y/o 'NombreCiclon' no existen en el archivo cargado.")

Este código que elaboramos para el proyecto lee los datos proporcionados en el archivo Excel sobre las velocidades de viento que generan los ciclones, calcula la categoría para cada velocidad de cada ciclón y agrega una nueva columna llamada "categoría".

**Resultados**

1. Como resultado el código funciono como esperábamos, insertando nuestro archivo Excel y generando la nueva columna con la clasificación de categoría de cada uno.

![resultados1](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/8c6f83ec-32d6-4a02-aa39-06a0f06328b2)

1. Además de entregarnos de manera visual los datos como resultado del programa nos genera un nuevo archivo Excel con una nueva columna de categorías.

![resultados2](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/1401890c-3b86-4839-aeb0-026728667e19)

1. Y como ultimo hacemos la comparación de las tablas de datos para comprobar el código ejecutado

![c 1](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/86a1d2df-9941-4076-a5f0-d2a7cc0cb9ac) 
![c 2](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/1dded80b-2d3b-42e3-8454-3973c9da099e) 
![c1](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/be790c11-c610-4be6-94be-374409e21fad)
![c1 2](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/54b2d153-ee87-4cf6-ab53-a5995cc24148)

![c2](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/a29647dc-1260-49ca-afd1-74a454456e4e)

![c2 2](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/9a4f94f7-b371-4782-a3aa-8e46bccdb0f0)



**Conclusiones**

El conocer la categoría de un ciclón puede ayudar a conocer el impacto que pude tener al tocar tierra, la creación del programa en colab nos ayuda a tener un resultado de manera más rápido de la categoría esto nos permite la manipulación eficiente de datos y facilita la automatización de tareas.
![poster](https://github.com/alew42/CICLONES_TUNEADO/assets/152411306/49055594-d054-4523-9c4c-c8482c63af05)
