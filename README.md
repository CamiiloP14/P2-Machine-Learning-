<h1 align="center"> Aprendizaje supervisado -Machine Learning </h1>
<p align="center">
  <img width="400" height="300" src="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
</p>

## Tabla de contenidos
* [Introducción](#Introducción)

* [Decripción del proyecto](#Descripción-del-proyecto)

* [Desarrollo del proyecto](#Desarrollo-del-proyecto)

* [Flujo de control](#Flujo-de-control)

* [Tecnologías utilizadas](#tecnologías-utilizadas)

* [Estado del proyecto](#Estado-del-proyecto)

* [Información del proyecto](#Información-del-proyecto)

* [Conclusiones](#Conclusiones)

## Introducción
Hola, mi nombre es Camilo Pedreros :wave: y hoy quiero compartirles un proyecto de machine learning en el que he estado trabajando. Este proyecto se enfoca al área de aprendizaje supervisado con el objetivo de crear un modelo para hacer predicciones.

## Descripción del proyecto
Un importante Centro de Salud :hospital: nos ha contratado con el fin de poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días.

## Desarrollo del proyecto

- 1) EDA \
Primero cargamos los datos usando la libreria pandas, para luego empezar a realizar un EDA de los dos datasets: 'hospitalizaciones_train' y 'hospitalizaciones_test'. Se realizan los cambios necesarios, se crea la variable objetivo ('target') y se realizan algunos gráficos para observar la distribución de los datos.
- 2) Modelado\
Después de tener los datos limpios, y observando el requerimiento del cliente, no enfocamos en hacer modelos de clasificación. Para esto, se tomaron en cuenta los algorítmos de K vecinos más cercanos y el algoritmo de árbol de decisión, pero finalmente se escoge el algoritmo de árbol de decsión ya que el modelo era más performantte que el de KNN.
- 3) Predicción\
Finalmente se entrena el modelo y se realizan las predecciones con el dataset 'hospitalizaciones_test'.
- 4) Rendimiento del modelo\
Para evaluar el desempeño del modelo, se utilizaron las métricas de Exhaustividad (Recall) de precisión (Accuracy), basándonos en la matriz de confusión.

## Flujo de control
<p align="center">
  <img width="600" height="400" src="https://user-images.githubusercontent.com/109446657/207929132-baacad01-c9b7-4215-8202-6a8256456ce5.svg">
</p>

## Tecnologías utilizadas
Para este proyecto se utilizando las siguientes herramientas.
* Python
  * numpy
  * pandas
  * seaborn
  * matplotlib
  * sklearn


Python es un lenguaje de programación que te permite trabajar rápidamente e integrar sistemas de manera más efectiva. https://docs.python.org/3/
## Estado del proyecto
 <p align="left">
   <img src="https://img.shields.io/badge/STATUS-%20FINALIZADO-green">
   </p>
   
 ## Información del proyecto
 Puede encontrar toda la información inicial de este proyecto en https://github.com/soyHenry/Datathon#readme

## Conclusiones
Este fue un proyecto desafiante en el que se logra interiorizar los conceptos de Machine Learning, Aprendizaje supervisado y algorítmos de clasificación. Así mismo, se logra el objetivo de predecir la estadia de un paciente en el hospital en cuestión. Las futuras actualizaciones de este proyecto se enfocarán en mejorar la performance del proyecto e investigar más algoritmos de clasificación para poder hacer mejores predicciones.
