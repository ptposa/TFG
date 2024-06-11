### :dart: Creación de diferentes modelos de aprendizaje
En este apartado nos sumergiremos en el desarrollo de diferentes modelos de aprendizaje, lo que involucra una serie de pasos fundamentales, como la comprensión del problema que se está abordando o la recopilación y preparación de datos relevantes. Una vez que dispongamos de los datos adecuados, procederemos a la selección de características y al entrenamiento de diferentes algoritmos de aprendizaje.

Trabajaremos con un dataset de entrenamiento y otro de test. El conjunto de datos NSL-KDD ya proporciona varias configuraciones de conjuntos de datos que pueden emplearse para diferentes tareas. La descripción de todas las configuraciones, así como los ficheros correspondientes, se encuentran alojados en este respositorio de GitHub.

Por tanto, emplearemos el KDDTrain+.txt como conjunto de entrenamiento y el KDDTest+.txt como conjunto de test. De esta manera, no será necesario realizar la división del dataset en un conjunto de entrenamiento y en un conjunto de test, tal y como hemos realizado para el primer caso de uso.

Ambos dataset contienen un total de 42 características (43 con el índice), pero se diferencian en el número de registros. Mientras el dataset KDDTrain+.txt posee un total de 125.972 registros, el KDDTest+.txt contiene 22.543.