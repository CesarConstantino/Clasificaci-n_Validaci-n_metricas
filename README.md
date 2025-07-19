Vamos a crear un proyecto de **clasificación** de clientes morosos en una empresa de financiamiento de automóviles. La [`Scikit-Learn`](https://scikit-learn.org/stable/index.html) será la principal biblioteca utilizada para realizar la validación y evaluación del rendimiento de los modelos de clasificación durante el curso. Explorar la documentación de esta biblioteca puede brindarte una excelente oportunidad para mejorar tus habilidades y adquirir mayor autonomía en la validación y en las métricas de modelos a lo largo del curso. Por lo tanto, a medida que avancemos, aprovecha este recurso adicional en tu aprendizaje.

### Datos del proyecto

Para realizar la clasificación de los clientes, se utilizará una [base de datos](https://github.com/alura-es-cursos/2162-clasificacion-validacion-de-modelos-y-metricas/blob/main/prestacar.csv) para alimentar nuestro proyecto. El uso de esta base es esencial, ya que, una vez descargada, proporciona la información necesaria para construir nuestros modelos de clasificación y te ofrece valiosa experiencia práctica en machine learning.

## Creando un modelo inicial

En esta clase, se aborda el desafío de una empresa financiera de automóviles con problemas para identificar clientes deudores. El objetivo es automatizar este proceso mediante un modelo de Machine Learning de clasificación.

Los pasos principales son:

1. Cargar y explorar un dataset con información de clientes.
2. Segmentar los datos en variables explicativas (X) y la variable objetivo (Y), que indica si un cliente es deudor o no.
3. Utilizar un modelo de clasificación de árbol de decisión para predecir si un cliente es deudor.
4. Evaluar el rendimiento del modelo utilizando la métrica de exactitud.

El modelo inicial alcanza una exactitud del 100%, lo que plantea dudas sobre su capacidad de generalización. En el próximo video, se validará el modelo para determinar si realmente está funcionando correctamente.

## Utilidad del método score()

Durante la construcción de un modelo para clasificar transacciones bancarias como legítimas o fraudulentas, una persona científica de datos utilizó la biblioteca Scikit-Learn, que ofrece diversos algoritmos de machine learning que pueden ser utilizados para la clasificación de datos. En cada uno de estos algoritmos, el método [`fit()`](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier.fit) se utiliza para entrenar un modelo a partir de las variables explicativas y la variable respuesta.

Sin embargo, después del entrenamiento del modelo, se realiza un paso más mediante el uso del método `score()`. Seleccione la alternativa que describe de manera adecuada la finalidad de usar el `score()` en este contexto:

Se utiliza para evaluar el desempeño del modelo ajustado.
El método [`score()`](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier.score) tiene la finalidad de comparar las predicciones realizadas por el modelo con los valores reales de los datos y calcula una tasa de acierto en porcentaje llamada **exactitud**.
