# Proyecto de Clasificación de Tumores de Mama y Regresión de Edad de Abalones

Este proyecto se enfoca en dos problemas relacionados con el aprendizaje automático: clasificación de tumores de mama y regresión de la edad de los abalones. A continuación, se describen brevemente ambos problemas y los conjuntos de datos utilizados.

## Clasificación: Tumores de Mama

En esta presentación, nos adentraremos en el emocionante campo de la clasificación de tumores de mama utilizando un enfoque basado en árboles. Para ello, utilizaremos el conjunto de datos ampliamente conocido "Wisconsin Diagnostic Breast Cancer" (WDBC).

El cáncer de mama es una enfermedad de gran impacto que afecta a muchas mujeres en todo el mundo. Diagnosticar con precisión si un tumor es benigno o maligno es crucial para determinar el tratamiento adecuado. En este contexto, el aprendizaje automático puede desempeñar un papel clave. Mediante el análisis de características de tumores de mama, podemos entrenar un modelo basado en árboles para realizar predicciones precisas sobre la malignidad de un tumor.

## Regresión: Edad de Abalones

El conjunto de datos "Abalone" es un conjunto de datos de dominio público que está disponible en el repositorio de aprendizaje automático de la UCI (University of California, Irvine). Este conjunto de datos se utiliza comúnmente en la comunidad de aprendizaje automático para tareas de clasificación y regresión.

Los abalones son un tipo de molusco marino que se encuentra en las costas de diversas regiones. El objetivo de este conjunto de datos es predecir la edad de los abalones a partir de varias medidas físicas, como el diámetro de la concha y la altura.

El conjunto de datos "Abalone" contiene información sobre 4177 abalones y se compone de los siguientes atributos:

- Sexo (categórico): M (masculino), F (femenino) e I (infante).
- Longitud (numérico): medida más larga de la concha en mm.
- Diámetro (numérico): medida perpendicular a la longitud en mm.
- Altura (numérico): altura de la carne en mm.
- Peso completo (numérico): peso entero del abalón en gramos.
- Peso de la carne (numérico): peso de la carne del abalón en gramos.
- Peso de las vísceras (numérico): peso de las vísceras en gramos.
- Peso de las conchas (numérico): peso de las conchas en gramos.
- Anillos (numérico): número de anillos en la concha, que se utiliza como indicador de la edad del abalón.

Estos problemas ilustran cómo el aprendizaje automático puede ser aplicado en áreas de la medicina y la ecología para realizar diagnósticos precisos y predecir características relevantes. A través del uso de modelos basados en árboles y técnicas de clasificación y regresión, se puede obtener información valiosa para la toma de decisiones y la comprensión de fenómenos complejos.

*Nota: Los detalles específicos sobre los métodos, algoritmos y resultados se encuentran en los archivos correspondientes del proyecto.*


## Archivos

- **Taller1_DewinsMurillo_ensemble_Clasificacion.ipynb**: Este archivo contiene el código y la documentación para el modelo de clasificación utilizando el conjunto de datos [Breast Cancer Wisconsin](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data).

![Breast Cancer Wisconsin](https://isanidad.com/wp-content/uploads/2013/10/Mamograf%C3%ADa-1024x675.jpg)

- **Taller1_DewinsMurillo_ensemble_Regresion.ipynb**: Este archivo contiene el código y la documentación para el modelo de regresión utilizando el conjunto de datos [Abalone](https://archive.ics.uci.edu/ml/machine-learning-databases/abalone/abalone.data).

![Abalone](https://www.learnaboutnature.com/wp-content/uploads/Abalone.jpg)

## Repositorio

Puedes acceder al repositorio completo en [[[https://github.com/SuperDesarroll/py-RNN-Clasificacion-Regresion](https://github.com/SuperDesarroll/py-ensemble-tree)]([https://github.com/SuperDesarroll/py-ensemble-tree](https://github.com/SuperDesarroll/py-ensemble-tree))]([https://github.com/SuperDesarroll/py-RNN-Clasificacion-Regresion](https://github.com/SuperDesarroll/py-ensemble-tree)) para obtener más detalles sobre la implementación de los modelos y explorar el código fuente.

## Instrucciones de Uso

Para ejecutar los modelos, se recomienda seguir los siguientes pasos:

1. Clonar el repositorio desde [[https://github.com/SuperDesarroll/py-RNN-Clasificacion-Regresion]([https://github.com/SuperDesarroll/py-ensemble-tree](https://github.com/SuperDesarroll/py-ensemble-tree))](https://github.com/SuperDesarroll/py-RNN-Clasificacion-Regresion) o descargar los archivos directamente.

2. Abrir los archivos `Taller1_DewinsMurillo_ensemble_Clasificacion.ipynb` y `Taller1_DewinsMurillo_ensemble_Regresion.ipynb` en Jupyter Notebook.

3. Asegurarse de tener instaladas las dependencias necesarias, como Pandas y Scikit-learn. En caso de ser necesario, instalar las dependencias faltantes utilizando pip o conda.

4. Ejecutar cada celda de código en los respectivos archivos de Jupyter Notebook para entrenar y evaluar los modelos de RNN.

Recuerda que los archivos de datos utilizados se encuentran en los enlaces proporcionados anteriormente.

¡Explora y experimenta con los modelos para clasificación y regresión! Si tienes alguna pregunta o comentario, no dudes en dejarlo en el repositorio. ¡Disfruta el proyecto!
