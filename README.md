
# README
Este repositorio contiene los siguientes archivos:

01 - modelo 1.ipynb
02 - modelo 2.ipynb
03 - comparación.ipynb
04 - dataset.csv
05 - informe.pdf

Descripción del Proyecto
El objetivo de este proyecto es analizar los datos del conjunto "Predict Students' Dropout and Academic Success", disponible en el repositorio de UCI Machine Learning. Los datos utilizados se encuentran en el archivo dataset.csv. A partir de este análisis, se implementaron y compararon dos modelos de clasificación: Decision Tree Classifier y Random Forest.

Modelo 1: Decision Tree Classifier
El primer modelo se desarrolló utilizando un clasificador de árbol de decisión (Decision Tree Classifier). Para optimizar su rendimiento y evitar problemas de underfitting o overfitting, se empleó la técnica de GridSearchCV para ajustar los hiperparámetros.

Modelo 2: Random Forest
El segundo modelo se implementó utilizando un clasificador de bosque aleatorio (Random Forest). Al igual que en el modelo anterior, se utilizó GridSearchCV para ajustar los hiperparámetros y mejorar su desempeño.

Comparación de Modelos
En el archivo 03 - comparación.ipynb, se realiza un análisis comparativo de los modelos. Este análisis incluye:

-Matrices de confusión comparativas.
-Índice de concordancia de Cohen (Cohen's Kappa).
-Curvas ROC para ambos modelos.
-Comparación de métricas clave (precisión, recall, F1, entre otras).
-Informe Final

El archivo informe.pdf contiene un análisis detallado de los resultados obtenidos, las conclusiones derivadas de la comparación entre los modelos, y reflexiones finales sobre el desempeño de cada enfoque.
