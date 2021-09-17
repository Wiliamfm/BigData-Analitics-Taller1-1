# BigData & Analitics-Taller1-1

Integrantes:
William Fonseca
-Moisés Salcedo

## Parte 1:
Instalamos Hadoop en ubuntu

![image](https://user-images.githubusercontent.com/53981601/133567064-cd29a7d5-7bba-4259-b060-c0ce1c1d10e2.png)

Podemos ver como se puede ejecutar desde el browser
![image](https://user-images.githubusercontent.com/65041178/133100101-c15f0097-9687-4b2b-b431-a6a4f0ebc985.png)

![image](https://user-images.githubusercontent.com/65041178/133100348-c702709e-f092-4a1a-b6b6-8e57628b6134.png)

![image](https://user-images.githubusercontent.com/65041178/133100447-1597637f-5524-4a03-ad94-990c20a9e733.png)

También podemos ver los nodos que se estan corriendo con el comando jps

![image](https://user-images.githubusercontent.com/53981601/133572880-0d71b9cf-10f5-4714-9db8-b657b097b69e.png)




## Parte 2:
#### 4. Creamos los directorios HDFS que se neesitan para ejecutar tareas de MapReduce
![image](https://user-images.githubusercontent.com/53981601/133671605-7748332a-5fc2-4efb-8570-21973abe2f3a.png)
![image](https://user-images.githubusercontent.com/53981601/133672111-f6f58fe0-9930-47a1-8830-c39a3dbc3a19.png)

#### 5. Copiamos los archivos en el sistema de archivos distribuido
![image](https://user-images.githubusercontent.com/53981601/133672440-1f428256-f96d-4264-9294-e52c57b857ca.png)
![image](https://user-images.githubusercontent.com/53981601/133672523-bca9e7b4-083f-47a4-b31d-5402c9947d9a.png)

#### 6. Corremos algunos de los ejemplos dados
![image](https://user-images.githubusercontent.com/53981601/133672613-2bd049bb-eac6-48eb-8ccb-a236e6722b63.png)

####  Vemos los archivos cargados en la carpeta input:
![image](https://user-images.githubusercontent.com/65041178/133121517-4aee3314-12ff-413d-b104-50e19e7388a2.png)

#### ¿Qué resultados generó el programa y cuales son los pasos MapReduce que implementa?
  El programa genera la cantidad de archivos de entrada que van a ser ejecutados por MapReduce, lo que hacer MapReduce es mapear
  y reducir, mapear se encarga de producir los pares clave valor de los archivos y a partir de estas los archivos de entrada
  se dividen en en varias tareas o FileSplit.
  Por su parte las tareas de reducir toman los nodos mapeados y estos son ordenados de forma que los pares clave valor sean continuos.
  Esto lo que logra es que al final de cada tarea de reduce solo se obtenaga un archivo combinado.

## Parte 3:

#### Instalación de Spark (1):
![image](https://user-images.githubusercontent.com/65041178/133153072-c106a634-1af7-4097-94fe-0b92de69d8a0.png)

#### WordCount (2):
##### Ejecución normal: 
![image](https://user-images.githubusercontent.com/65041178/133466180-d46b7f41-f007-4c36-88cb-8cece5058dde.png)
![image](https://user-images.githubusercontent.com/65041178/133153247-92bf8f0b-c37a-4f8f-960f-3d57873c0b5b.png)
##### Ejecución modificada ():

## Parte 4:

1. Para este punto clonamos el repositorio unicado en la url https://github.com/bigdata-unbosque/SparkTutorial
A la vez hicimos la descarga y la descompresión de los archivos de la URL https://www.kaggle.com/dinnymathew/usstockprices

2.  Para la ejecución de este archivo hicimos el descargue de la distribución de python anaconda, para esto accedimos
a la siguiente URL https://www.anaconda.com/products/individual

4. Despues de haber instlado el paquete de Anaconda se pudo hacer uso de Jupyter Notebook despues de dirigirnos 
a la siguiente URL  http://<puerto>:8888/lab/
 ![image](https://user-images.githubusercontent.com/53981601/133722844-dc4d5175-a1a0-4ee9-a0c3-89c07dd06891.png)
5. Por pultimo se ejecutaron los dos scripts indicados en el punto 4 de la parte 4 del taller. A continuación mostramos el paso a paso del desarrollo. 
  
  
### Pyspark basics:
![image](https://user-images.githubusercontent.com/65041178/133351761-4a31e612-4360-402b-8dc4-21d4aa4c87c6.png)
![image](https://user-images.githubusercontent.com/65041178/133463000-753e6408-cc3c-4a1e-9e86-2ef3d6af833e.png)
-
![image](https://user-images.githubusercontent.com/65041178/133463067-3605c5bd-879d-4864-8d3b-288a83256b38.png)
-
![image](https://user-images.githubusercontent.com/65041178/133463133-d7f0a965-a867-4040-8805-a0cff57b5e6f.png)
-
![image](https://user-images.githubusercontent.com/65041178/133463213-8c5f0e3b-93b1-431b-9677-b9e0d977f205.png)
-
![image](https://user-images.githubusercontent.com/65041178/133463266-e7fc059f-bb39-4c43-be80-a295341f60cc.png)
-
![image](https://user-images.githubusercontent.com/65041178/133463311-ba78f740-6e4e-4e73-ab84-014079be399e.png)
-
![image](https://user-images.githubusercontent.com/65041178/133463802-461900d9-2640-400e-b36e-aa167f2ac044.png)
-

### Pyspark data analysis:

![image](https://user-images.githubusercontent.com/65041178/133465351-8cdceaff-c565-4d26-9d89-51d21be13a61.png)
-
![image](https://user-images.githubusercontent.com/65041178/133465401-2243b2b5-50f4-48aa-a3f9-bea75ea66a7a.png)
-
![image](https://user-images.githubusercontent.com/65041178/133465479-4dec174b-8550-4747-b593-5a7e4707609b.png)
-
![image](https://user-images.githubusercontent.com/65041178/133465598-c2064c47-38f5-4b52-aaf5-238d3cc361dc.png)
-
![image](https://user-images.githubusercontent.com/65041178/133465664-f14d5edb-7104-422c-b941-585d77360db6.png)
-
![image](https://user-images.githubusercontent.com/65041178/133465701-abf0b752-f0b6-4e55-9545-5c6daf58b489.png)
-
![image](https://user-images.githubusercontent.com/65041178/133466399-c89e91ac-4c90-48a6-9179-e61c2f79c273.png)
