# Universidad Galileo #
# Instituto de Investigación de Operaciones #
# Ciencia de Datos con Python #

----------

## *Proyecto Final* ##
# DATAWAREHOUSE #

## Oscar Melchor i59201 ##
## Walter Najera 9630850 ##


## SCOPE DEL PROYECTO ##
Analizar el comportamiento de clientes y el volumen de operaciones en las agencias de una institución bancaria del pais.
Los datos han sido enmascarados para mantener confidencialidad.

Los datos utilizados fueron recibidos en un archivo de excel conteniendo 

~450K filas  

y 46 columnas.  

Parte del esfuerzo ha sido:

- analizar la calidad de los datos recibidos, identificando nulos  
- utilizar DataGrip para implementar todo un modelo relacional en RDS en base a los datos del excel.
- utilizar Python para implementar el  modelo relacional en RDS en base a los datos ya incorporados con DataGrip

Siguiendo los requerimientos establecidos en el proyecto se habilitó:


- una base de datos en RDS 
- un Bucket en AWS S3 desde el cual se leen dos archivos de excel.
- un cluster en Redshift desde el cual se habilita el DataWarehouse


## Exploración de los datos ##

El data set cuenta con información transaccional de clientes de uan entidad financiera a quienes se les otorgó uno o varios creditos durante un periodo de tiempo y sobre los cuales tambien contamos con sus datos generales. Se obtiene información de la producción de venta de la geografia operativa de la institución desde los puntos de venta donde se originan las transacciones y los volumenes que estas generan en su estructura organizacional. 


## Modelo de datos ##

El modelo de datos sobre el cual se estará trabajando se muestra en el directorio de GitHub DCPythonProyFinal

## Procesamiento ##

Los Scripts utilizados para el desarrollo del proyecto están depositados en el directorio de GitHub DCPythonProyFinal

## Analitica ##

Con el modelo desarrollado se responden las siguientes preguntas:

1. ¿cuál es el top 5 de clientes por número de compras en el primer trimestre del año 2021?
1. ¿cuál es el departamento geografico que már operaciones realiza?
1. ¿cuál es la sucursal que más intereses generó y con que producto?
1. ¿cual es el top 5 de los clientes con más crédito otorgado?
1. ¿qué gerente de territorio ha generado más ventas en el año?

