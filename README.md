# NLP-Amazon-Reviews
Este repositorio contiene el entrenamiento replicable de NLP para un set de reviews compartidos por los cleintes de productos desitribuidos por amazon el cual se puede encontrar en https://www.kaggle.com/datasets/meetnagadia/amazon-kindle-book-review-for-sentiment-analysis/data
asi mismo el objetivo es encotrar una metodologia que mejor clasifique los reviews basado en el sentimiento que este representa, de modo que se pueda categorizar los reviews en positivos y negativos.
para ello se recomienda descargar las diferentes librerias sugeridas en el inicio del notebook y continuar replicando y modificando las diferentes celdas teniendo en cuenta la propia database.
durante el estudio se utilizan metodologias de revision y correccion de textos, entre ellas una tecnica fundamental fue la tokenizacion, donde se propone usar bag of words BoW y tf-idf donde este ultimo obtuvo mejores resultados en terminos de precision.
para clasificar los diferentes sentimientos se propusieron 3 metodologias. Nive Bayes, random forest y boosting gradient.
a modo de conclusion: la metodologia TF-IDF junto la clasificacion de naive bayes, presentaron los mejores resultados para clasificar las diferentes reviews, seria interesante mas adelante profundizar mas en las palabras mas repetidas en cada uno de los sentimientos asociados a las revews y asi identificar cuales son las principales oportunidades de mejora y las que mayor potencial de rentabilidad tienen
