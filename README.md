# Introducción a la Ciencia de Datos con Python

* Autor: Ricardo Moya García, PhD
* Release: 3.0.0
* Fecha última actualización: 18-11-2020
* ![python versions](https://img.shields.io/badge/python-3.6%2C%203.7-blue.svg)


<hr>

En este proyecto de GitHhub podrás encontrar parte del material que utilizo para impartir las clases de Introducción a la Ciencia de Datos (Data Science) con Python.



El contenido compartido es el siguiente, dividiendose el curso en 3 módulos:


### Módulo I: Introducción a la ciencia de datos

Breve introducción al mundo de la ciencia de datos, describiendo conceptos como: Data Driven Decision Makining (DDDM), Big Data, Fases del Big Data, ¿Que es la Ciencia de Datos?, Ciclo de vida de un proyecto Data Science, Roles en un proyecto Data Science, en qué invierte el tiempo un Cientifico de Datos y por último ¿Que es Kaggle?.


	* Notebooks:
		- 00_Introduccion.ipynb


### Módulo II: Análisis de datos

* En este módulo se muestran los conceptos más importantes para conseguir conocimiento a partir de los datos: Recolección de datos, Limpieza de Datos, Analisis Exploratorio de Datos y Visualización de la información por medio de gráficas son algunas de las cosas que se muestrán en esta módulo usando librerías como Pandas, Numpy, Matplotlib y Seaborn. 

#### Tema 1: Data Wrangling

	* Notebooks:
		- 01_Data_Wrangling-Obtencion_Tweets.ipynb
		- 02_Scraping-Ejemplo.ipynb


#### Tema 2: Exploratory Data Analysis (EDA)

En Español: "Análisis Exploratorio de Datos"

	* Notebooks:
		- 03_Pandas_Objetos_Basicos.ipynb
		- 04_Pandas_Dataframe_Atributos_Metodos_Utiles.ipynb
		- 05_Pandas_Dataframe_Info_Description_Filtros_Nuevas_Columnas.ipynb
		- 06_Pandas_Dataframe_Agregaciones_Ordenaciones.ipynb
		- 07_Pandas_Dataframe_Join_Union.ipynb
		- 09_Pandas_Dataframe_Pivot_Table.ipynb

		
#### Tema 3: Visualización

	* Notebooks:
		- 11_Graficos_Matplotlib.ipynb
		- 12_Graficos_Seaborn.ipynb

#### Tema 4: Limpieza de Datos

	* Notebooks:
		- 13_Limpieza_de_Datos_Imputacion_Valores_Faltantes.ipynb



### Módulo III: Desarrollo de modelos

* En este módulo se muestra una introducción al Machine Learning asi como los algoritmos de aprendizaje más básicos para cada una de las tareas del aprendizaje supervisado y no supervisado, haciendo uso de la librería de Scikit-Learn.


* Los algoritmos de aprendizaje que se verán son:

	+ Aprendizaje Supervisado
		- Regresión: **Regresión Lineal**
		- Clasificación: **Regresión Logística**
	+ Aprendizaje No Supervisado
		- Clustering: **K-Means** y **Gaussian Mixture Models**
		- Reducción de Dimensionalidad: **Analisis de Componentes Principales** (PCA)


#### Tema 1: Introducción al Machine Learning

	* Notebooks:
		- 14_Machine_Learning_Introduccion.ipynb
		- 15_Tecnicas_de_Evaluacion.ipynb


#### Tema 2: Regresión Lineal (Múltiple)

	* Notebooks:
		- 16_Regresion_Lineal_Simple.ipynb
		- 17_Regresion_Lineal_Simple_Sckit.ipynb
		- 19_Regresion_Lineal_Multiple.ipynb
		- 20_Regresion_Lineal_Modelo_Matricial.ipynb
		- 21_Regresion_Lineal_Multiple_Scikit.ipynb


#### Tema 3: Evaluación de Modelos de Regresión

	* Notebooks:
		- 23_Evaluacion_Modelos_Regresion.ipynb
		- 24_Hold_Out_Regresion_Lineal_Multiple.ipynb
		- 25_Cross_Validation_Regresion_Lineal_Multiple.ipynb


#### Tema 4: Clasificación

	* Notebooks:
		- 27_Clasificacion_Regresion_Logistica.ipynb
		- 28_Clasificacion_Regresion_Logistica_Scikit_Iris.ipynb
		- 29_Clasificacion_Multiple_Regresion_Logistica_Scikit_Iris.ipynb
		- 30_Clasificacion_Multiple_N_Features_Regresion_Logistica_Scikit_Iris.ipynb


#### Tema 5: Evaluación de Modelos de Clasificación

	* Notebooks:
		- 32_Evaluacion_Modelos_Clasificacion.ipynb
		- 33_Evaluacion_Modelos_Clasificacion_Hold_Out_Iris.ipynb


#### Tema 6: Normalización, Correlación y Transformación de Datos

	* Notebooks:
		- 35_Transformaciones_de_Datos_de_Variables_Categoricas.ipynb
		- 36_Normalizacion_de_Datos.ipynb
		- 37_Correlacion_de_Datos.ipynb


#### Tema 7: Clustering

	* Notebooks:
		- 38_Clustering_K_Means.ipynb
		- 39_Clustering_K_Means_Scikit.ipynb
		- 40_Clustering_K_Means_4_Features_Scikit.ipynb
		- 41_Seleccion_Optima_Numero_Clusters.ipynb
		- 42_Ejemplo_Segmentacion_Clientes_Centros_Comerciales.ipynb
		- 43_Clustering_Gaussian_Mixture_Models.ipynb
		- 44_Clustering_Gaussian_Mixture_Models_Scikit.ipynb


#### Tema 8: Reducción de la Dimensionalidad

	* Notebooks:
		- 45_Analisis_de_Componentes_Principales_PCA.ipynb
		- 46_Ejemplo_Clasificacion_Multiple_con_PCA.ipynb

<hr>

## Instalación del entorno

Para ejecutar los scripts y notebooks de este proyecto es necesario tener creado un entorno virtual con conda (también puede ser con un virtualenv), en el que a parte de tener instaladas las librerías que te instala anaconda por defecto al crear el entorno (numpy, scipy, pandas, matplotlib, scikit, etc) hay que instalar una serie de librerías específicas que se indican en el fichero requirements.txt.

A continuación se muestran los pasos a seguir para crear el entorno virtual con conda por medio de una consola:

`Nota: estos mismos pasos pueden realizarse también por medio del Anaconda Navigator, pero mejor hacerlo por consola.`

1.- Crear un entorno virtual con un python 3.6 llamado "python36_DS"

```
>> conda create -n python36_DS python=3.6 anaconda
```

2.- Activar el entorno virtual

```
>> conda activate python36_DS
```

3.- Instalar librerias con pip:

```
>> pip install -r requirements.txt
```

* Si queremos instalar las librerias de forma manual podemos hacerlo de la siguiente manera "una a una":

	```
	>> pip install nombre_libreria==VERSION
	```
	
* Por ejemplo para instalar la librería de Tweepy lo podríamos hacer:

	```
	>> pip install tweepy==3.8.0
	```

`Nota: La instalación de librerías también se podria realizar por medio del repositorio de "conda" (en vez de "PIP"), pero estos comandos no los mostramos en este README.`



#### Bonus Track Anaconda

A continuación se muestran algunas acciones extra:

1.- Desinstalar librerías:

```
>> pip uninstall nombre_libreria
```

2.- Desactivar el entorno virtual (previamente tiene que estar activado)

```
>> conda deactivate
```

3.- Eliminar entorno virtual (llamado "python36_DS")

```
>> conda remove -n python36_DS -all
```