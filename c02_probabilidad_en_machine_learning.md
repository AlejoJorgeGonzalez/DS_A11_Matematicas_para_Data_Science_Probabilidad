# PROBABILIDAD EN MACHINE LEARNING

La probabilidad es un lenguaje matemático que permite cuantificar la incertidumbre. En machine learning esta incertidumbre se presenta en tres fuentes

- Datos
- Atributos del modelo
- Arquitectura del modelo

La incertidumbre en los datos resulta de que los métodos de medición no son perfectos, siempre van a tener un error. En los atributos el error aparece ya que el modelo es un subconjunto de la realidad, esta reducción de variables ya genera una capa de incertidumbre en la arquitectura, el modelo matemático es una representación simplificada de la realidad, por lo que también genera incertidumbre.

Un ejemplo es un modelo de clasificación

![](https://i.imgur.com/bqbV5uG.png)

Imagine que se tiene varios documentos y estos documentos deben ser clasificados por temas, como por ejemplo, deportes, videojuego, política, etc. El modelo, lo que realiza es una probabilidad de cada uno de estos temas, y lo asigna a la categoría que mayor porcentaje tenga, a esto se le conoce como un clasificador probabilístico. Se muestra como es el funcionamiento de un modelo de clasificación

![](https://i.imgur.com/JJxNYYJ.png)

Es de anotar que este modelo es de entrenamiento supervisado, por que se le esta diciendo cuales son las etiquetas, el modelo comienza con una parte de entrenamiento, en donde se le asigna varios documentos con sus respectivas etiquetas, despues el modelo extrae los atributos, es decir aquellas palabras que se encuentran mas comúnmente en el modelo y despues pasa por un algoritmo de machine learning. Despues se pasa a la fase de predicción en donde un documento cualquiera, el modelo extrae los atributos, pasa por un modelo de clasificación para predecir con que probabilidad pertenece a tal etiqueta.

Las etapas de un modelo es la siguiente

![](https://i.imgur.com/xeEOGmp.png)

Todas la etapas del modelo siempre va a tener una incertidumbre. En la arquitectura es donde se selecciona el modelo a utilizar, que despues se diseña, donde algunos pueden utilizar probabilidad, ya que hay modelos que no utilizan la probabilidad, para este caso se utiliza el modelo de Naive Bayes. Despues se selecciona el entrenamiento, que para este caso es el MLE (Estimación de máxima verosimilitud).  Sigueinte, continua la calibración que es el ajuste de aquellos parametros que no se puede ajustar en la optimización y que son llamados hiper-parametros, para este caso se utiliza la optimización bayesiana. Terminado el entrenamiento, continua la predicción en la cual se interpreta esta predicción. Po r último se termina con un resultado del proceso del modelo.
