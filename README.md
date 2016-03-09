Cómo clasificar artículos con Python
====================================

Lleva a cabo una clasificación de artículos usando un algoritmo de clustering
(K-means) y la medida estadística TF-IDF ([Term frequency-Inverse document frequency](https://en.wikipedia.org/wiki/Tf%E2%80%93idf)) aplicada a un conjunto
de artículos.

Para este ejemplo, he utilizado [iPython Notebook](http://ipython.org/notebook.html). El primer cuaderno, *download_articles.ipynb*, lleva a cabo la descarga de artículos online de varios
periódicos online usando sus fuentes RSS (no relacionado con ninguna técnica de
 aprendizaje automático). El segundo, *articles_classifier.ipynb*, muestra cómo
 crear un clasificador utilizando la librería [scikit-learn](http://scikit-learn.org/).

 El directorio *training* contiene ya un conjunto de artículos que se pueden
 utilizar para entrenar el clasificador mientras que en *test* hay otros
 artículos distintos con los que se puede probar la precisión del clasificador.
 Otros conjuntos de ejempos se pueden encontrar en el directorio *articles*.
