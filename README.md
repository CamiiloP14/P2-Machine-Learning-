<h1 align="center"> Aprendizaje supervisado -Machine Learning </h1>

## Tabla de contenidos
* [Introducción](#Introducción)

* [Decripción del proyecto](#Descripcion-del-proyecto)

* [Desarrollo del proyecto](#Desarrollo-del-proyecto)

* [Estado del proyecto](#Estado-del-proyecto)

* [Acceso al proyecto](#acceso-proyecto)

* [Tecnologías utilizadas](#tecnologías-utilizadas)

* [Personas Contribuyentes](#personas-contribuyentes)

* [Personas-Desarrolladores del Proyecto](#personas-desarrolladores)

* [Licencia](#licencia)

* [Conclusión](#conclusión)
## Introducción
Hola, mi nombre es Camilo Pedreros :wave: y hoy quiero compartirles un proyecto de machine learning en el que he estado trabajando. Este proyecto se enfoca al área de aprendizaje supervisado con el objetivo de crear un modelo para hacer predicciones.

## Descripción del proyecto
Un importante Centro de Salud :hospital: nos ha contratado con el fin de poder predecir si un paciente tendrá una estancia hospitalaria prolongada o no, utilizando la información contenida en el dataset asociado, la cual recaba una muestra histórica de sus pacientes, para poder administrar la demanda de camas en el hospital según la condición de los pacientes recientemente ingresados.

Para esto, se define que un paciente posee estancia hospitalaria prolongada si ha estado hospitalizado más de 8 días.

## Desarrollo del proyecto

- 1) EDA \
Primero cargamos los datos usando la libreria pandas, para luego empezar a realizar un EDA de los dos datasets: 'Hospitalizaciones_train' y ospitalizaciones_test'. Se realizan los cambios necesarios, se crea la variable objetivo ('target') y se realizan algunos gráficos para observar la distribución de los datos.
- 2) Modelado\
Después de tener los datos limpios, y observando el requerimiento del cliente, no enfocamos en hacer modelos de clasificación y se tomaron en cuenta los algorítmos de K vecinos más cercanos y el algoritmo de árbol de decisión ya que estos son perfectos cuando la varible objetivo es una variable binaria.
-3) Predicción\
Finalmente se entrena el modelo y se realizan las predecciones con el dataset 'hospitalizaciones_test'.
- 3) Rendimiento del modelo\
Para evaluar el desempeño del modelo, se utilizaron las métricas de Exhaustividad (Recall) de precisión (Accuracy), basándonos en la matriz de confusión.

## Flujo de control
![supervised-learning-diagram](https://user-images.githubusercontent.com/109446657/207928437-bedb2903-f6cf-4aa0-a550-c2bdfb25606a.png)

