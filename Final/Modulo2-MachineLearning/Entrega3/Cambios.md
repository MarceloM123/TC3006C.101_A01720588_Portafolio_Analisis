Cambios solicitados que han sido realizados:
* El dataset se separa en entrenamiento, validación, y prueba.
* Evalúa el modelo con un conjunto de prueba.
* Entrena el modelo sobre el conjunto de entrenamiento.
* El conjunto de validación se utiliza para escoger el modelo final (refinamiento de hiper-parámetros).
* El conjunto de prueba solamente se usa al final para reportar la capacidad de generalización del modelo seleccionado.
* Se detecta correctamente el grado de bias o sesgo: bajo medio alto.
* La decisión del grado de bias o sesgo se soporta con una tabla, gráfico, o similar.
* Se detecta correctamente el grado de varianza: bajo medio alto.
* La decisión del grado de varianza se soporta con una tabla, gráfico, o similar.
* Se detecta correctamente el nivel de ajuste del modelo: underfit, fit, overfit.
* La decisión del nivel de ajuste del modelo se soporta adecuadamente (explicación con base en criterior previos, o datos nuevos).
* Se utilizan técnicas de regularización para mejorar el desempeño del modelo.
* Se adjuntó el archivo de código fuente (puede ser el Jupyter Notebook o el .py si trabajaron aparte).