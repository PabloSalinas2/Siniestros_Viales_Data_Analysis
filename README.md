# Siniestros_Viales_Data_Analysis

## Siniestros viales en la Ciudad de Buenos Aires 

Mediante el siguiente proyecto se busca realizar un analisis de los Siniestros Viales en la Ciudad de Buenos Aires, expresando las principales observaciones mediante un Dashboard realizado en Power Bi.

El analisis será realizado entorno a 2 KPI's principales, estos son reducir un 10% la tasa de homicidios en siniestros viales de los ultimos 6 meses en CABA y Reducir un 7% la cantidad de accidentes mortales de motociclistas en el último año en CABA

## Procedimiento
El proyecto consta de 3 etapas principales:
### 1) EDA
`Procedimiento`

Se extraen los datos de siniestros viales en CABA, durante la primera etapa del proyecto se realiza un analisis exploratorio de los mismos, con la finalidad de entende los datos, las variables que los componene y la relacion existente enter cada una las mencionadas. Además se revisan nulos , valores duplicados y outliers. Este proceso se lleva a cabo en un Notebook de Jupyter, una vez finalizado el analizis exporto los datos a una base de datos construida en MySql.

`Herramientos utlizadas`

Para el analisis exploratorio de los datos su utilizaron las librerias Pandas y Numpy para el manejo de dataframe y Matplolib y Seaborn para la construcción de graficos.

`Archivos`

Datos_extra.ipynb - EDA.ipynb

### 2) BASE DE DATOS
`Procedimiento`

Luego de la exploración de los datos procedi a la construccion de una base de datos utilizando como herramienta el motor de base de datos MySql, donde se construyeron las tablas necesarias para el proyecto,dichas tablas fueron completadas con los datos de los dataframes resultantes del proceso EDA

`Herramientos utlizadas`

Para esta etapa se utilizo MySql para la construccion de la base de datos , libreria PyMysql para establecer conexion entre python y Mysql

`Archivos`

creacion_DB&tablas_mysql.sql

### 3) VIZUALIZACIONES 

`Procedimiento`

FInalmente luego de haber realizado el analisis exploratorio de los datos (EDA) y la construccion de la base datos con los datos finales cargados con los que voy a trabajar procedo realizar un dashboard interactivo en Power Bi con la finalidad de transformar los datos en informacion grafuca util para el cliente, dichas visualizaciones tienen como finalidad mostrar al cliente un panorama amplio de la situacion de siniestros viales en la Ciudad de Buenos Aires, mosrandole informacion tal como evolucion de  las muertes a causa de sinestros viales a lo largo del tiempo, cuales son las principales victimas de los hechos, zonas con mayor numero de victimas registrados. et

<<Mostrar visualizaciones parciales?>>

`Herramientos utlizadas`

Para esta etapa se utlizó como herramienta de  viusalización Power Bi.

`Archivos`

dashboard.pbix

Como resultado final presento el Dashboard desarrollado en Power Bi 

<<Insertar imagen del Dashboard>>




