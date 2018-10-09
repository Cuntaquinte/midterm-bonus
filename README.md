# Visual-A
datasets VA
## README

Midterm Bonus (Oct 9, 2018)

Autor: 
## Carlos Moreno Ibarguen  

La visualización se encuentra disponible en Github en el siguiente enlace:


Requisitos
-https://d3js.org/d3.v5.min.js


# Contexto
Datos suministrados por la NASA referentes a las anomalias (σ) respecto a la media climatica registradas entre los años 1880 hasta la actualidad.

Los datos originales estan disponibles en:

- https://data.giss.nasa.gov/gistemp/tabledata_v3/GLB.Ts+dSST.csv

PreProcesados:  
- https://github.com/Cuntaquinte/midterm-bonus/blob/master/data/dataQ.csv


# Objetivos del proyecto (Tarea Principal) y tecnologías usadas:
El objetivo del proyecto es generar una herramienta que permita ver las variaciones anomalas (desviaciones de la temperatura promedio) en datos de temperaturas en el periodo 1880 - 2018.
La técnologia utilizada fue html, css,javascript + libreria D3 V3. Los datos se manipularon en los formatos csv.


# Tareas Secundarias:
- Determinar en que temporada del año hubo mas afectación climatica.


# Analisis de los datos
## Preprocesamiento de datos. 
Se organizaron los datos por resumen de temporadas en el siguiente formato
date	Anual(Enero-Diciembre)	Anual(Diciembre-Noviembre)	Summer(Dic-Ene-Feb)	Autumn(Mar-Abr-May)	Winter(Jun-Jul-Ago)	Spring(Sep-Oct-Nov)

## What?
Los datos se obtuvieron de un Dataset tipo Tabla.
### Tipos de atributos
DATE:		Ordenado - Ordinal - Secuencial  (Representa los años durante los datos fueron registrados)
Anual(J-D):	Ordinal - divergente (Representa las anomalias de temperaturas respecto a la media de ese periodo.)
Anual(D-N):	Ordinal - divergente (Representa las anomalias de temperaturas respecto a la media de ese periodo.)
Summer:		Ordinal - divergente (Representa las anomalias de temperaturas respecto a la media de ese periodo.)
Autumn:		Ordinal - divergente (Representa las anomalias de temperaturas respecto a la media de ese periodo.)
Winter:		Ordinal - divergente (Representa las anomalias de temperaturas respecto a la media de ese periodo.)
Spring:		Ordinal - divergente (Representa las anomalias de temperaturas respecto a la media de ese periodo.)


## Why?
Analyze - Consume- Discover >> Similarity/Trends
Search - Browse >> Outliers

## How?
### Marcas y Canales
Marca	  Canales
Line	  Color-Hue
-- --	  Pos X
-- --     Pos Y

## Explore  el gráfico!!!.
Al PASAR el mouse sobre las lineas de las diferentes temporadas puede observar información refernte al comportamiento de temperatura.
Al hacer CLICK sobre cada uno de los chekbox de las temporadas al lado derecho de la gráfica podra ver los datos referente a cada temporada con distinto color para apreciar las diferencias, los datos de cada momento y en comparación de todas las temporadas se mostraran junto a las leyendas de la gráfica. (podrá escoger datos anuales de Enero a diciembre o diciembre a noviembre asi como cada una de las estaciones (bloques trimestrales del año))
En la barra exploratoria de abajo podra hacer zoom en difrentes momentos par apreciar el comportamiento mas detallado, por ejemplo ver el comportamiento climatico en un año en particular.

## Licencia MIT
[MIT Licence] https://github.com/Cuntaquinte/midterm-bonus/blob/master/LICENSE

