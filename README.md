# Siniestros_Viales_Data_Analysis

## Siniestros viales en la Ciudad de Buenos Aires 

Mediante el siguiente proyecto se busca realizar un `análisis de los siniestros viales en la Ciudad de Buenos Aires`, expresando las principales observaciones mediante un Dashboard realizado en Power Bi.

El análisis fue realizado entorno a 2 KPI's (Indicador Clave de Desempeño) principales, estos son reducir un 10% la tasa de homicidios en siniestros viales de los ultimos 6 meses en CABA y reducir un 7% la cantidad de accidentes mortales de motociclistas en el último año en CABA.

## Procedimiento
El proyecto consta de 3 etapas principales:
### 1 - EDA
`Procedimiento`

Se extraen los datos de siniestros viales en CABA, durante la primera etapa del proyecto se realizó un análisis exploratorio de los mismos, con la finalidad de entender los datos, las variables que los componen y la relación existente entre cada una las mencionadas. Además se revisan valores nulos , valores duplicados y outliers. Este proceso se llevó a cabo en un Notebook de Jupyter, una vez finalizado el análizis exporto los datos a una base de datos construida en MySql.

`Herramientos utlizadas`

Para el analisis exploratorio de los datos su utilizaron las librerías Pandas y Numpy para el manejo de dataframes y Matplotlib y Seaborn para la construcción de gráficos.

`Archivos`

*Datos_extra.ipynb - EDA.ipynb*

### 2 - Base de Datos
`Procedimiento`

Luego de la exploración de los datos procedi a la construcción de una base de datos utilizando como herramienta el motor de base de datos MySql, donde se construyeron las tablas necesarias para el proyecto, dichas tablas fueron completadas con los datos de los dataframes resultantes del proceso EDA.

`Herramientos utlizadas`

Para esta etapa se utilizó MySql para la construcción de la base de datos , librería PyMysql para establecer conexión entre python y la base de datos Mysql.

`Archivos`

*creacion_DB&tablas_mysql.sql*

### 3 - Vizualizaciones/Dashboard

`Procedimiento`

FInalmente luego de haber realizado el análisis exploratorio de los datos (EDA) y la construcción de la base datos con los datos finales cargados con los que voy a trabajar, procedí a realizar un dashboard interactivo en Power Bi con la finalidad de transformar los datos en información gráfica útil para el usuario final, dichas visualizaciones tienen como finalidad mostrar al usuario un panorama amplio de la situación de siniestros viales en la Ciudad de Buenos Aires, mostrandole información tal como evolución de  las muertes a causa de sinestros viales a lo largo del tiempo, cuales son las principales victimas de los hechos, zonas con mayor numero de victimas registrados, etc.

`Herramientos utlizadas`

Para esta etapa se utlizó como herramienta de viusalización Power Bi.

`Archivos`

*dashboard.pbix*

Como resultado final presento el Dashboard desarrollado en Power Bi 




