# Proyecto de estudio climático

El objetivo del proyecto es generar un dashboard para realizar un análisis de la situación climática en España en los últimos años. Para ello se ha partido de información obtenida a través de la API de AEMET y tratada con Python, que posteriormente se ha cargado a Tableau para analizarla.


![](Images/gvb.jpg)


Las principales métricas de estudio son las precipitaciones y la temperatura, y el rango temporal que abarca la información se sitúa entre el año 2000 y el 2023.


# Estructura

Este repositorio cuenta con la siguiente estructura:

- Data: En esta carpeta se almacena el fichero inicial obtenido de la API de AEMET `AEMET_2000-2023.csv`, así como el fichero obtenido tras la limpieza y que se utilizará en Tableau `CLIMA_2000_2023_COMPLETO`.
- Images: Las imágenes utilizadas para el readme
- AEMET_data: Fichero con la llamada a la API de AEMET.
- AEMET_cleaning: Fichero con la limpieza de datos que genera la información final que será objeto del análisis.


# Análisis y visualización

![](Images/tableau.png)

El análisis realizado con Tableau se divide en 3 bloques reflejados en 3 dashboard:

- **Resumen**: Resumen de las métricas objeto de estudio; valores máximos, ranking..
- **Precipitaciones**: Permite profundizar en el estudio concreto de las precipitaciones
- **Temperatura**: Permite profundizar en el estudio concreto de las temperaturas


[Enlace al dashboard](https://public.tableau.com/app/profile/miriam.paramio.lorenzo/viz/Dashboard_clima_Espaa_2000_2023/Resumen?publish=yes)
