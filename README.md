# **<p align="center">`Datathon` <br> `Machine Learning`</p>**

> ## Introducción

En este proyecto, a modo de datathon o de concurso, vamos a trabajar con un dataset sobre los pacientes de un hospital,
y vamos a intentar predecir si su estadía va a ser larga (9 días o más) o corta (menos de 9 días).

> ## Objetivo

El objetivo de este proyecto es entrenar un modelo de machine learning para poder clasificar correctamente
la estadía de los pacientes, basándonos en varios datos tales cómo: la edad, el género, el número de habitaciones disponibles en el hospital,
la cantidad de visitantes que fueron registrados, etc.

> ## Método

Se realizó un EDA sobre el set de datos para corroborar que hay algún tipo de relación entre los datos, por más mínima que sea.
Para este proyecto, vamos a usar un modelo de clasificación de árboles de decisión de Scikit-Learn.
Primero, dividiremos nuestro conjunto de datos en un conjunto de entrenamiento y un conjunto de prueba. 
Entrenaremos nuestro modelo en el conjunto de entrenamiento y luego lo evaluaremos en el conjunto de prueba.<br>

> ## Resultados

Luego de entrenar nuestro modelo, **obtuvimos una precisión del 75% en el conjunto de prueba**.<br>
Esto significa que nuestro modelo es capaz de clasificar correctamente la estadía de los pacientes en la gran mayoría de los casos.
