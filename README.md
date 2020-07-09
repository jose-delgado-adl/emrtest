# pyspark-emr-workshop

## config
Inlcuye los archivos de configuración para la creación del cluster en EMR.
``` 
  configuracion-emr: incluye un json que se utiliza para configurar python en el cluster. Este no es necesario para la versión 6.0 de EMR
  bootstrap.sh: los clusters de EMR permiten utilizar acciones bootstrap, en este caso la usaremos para instalar las librerías de pandas y pyarrow
```  
## data
Contiene el archivo con la data que se usará en el workshop

## notebooks
Inlcuye los notebooks de EMR con los que se trabajará durante el workshop

## step-function
Tiene un template de una step-function que permite levantar un cluster, correr una aplicación de pyspark y terminar el cluster.

