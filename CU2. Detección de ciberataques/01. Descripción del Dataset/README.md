## Conjunto de datos NSL-KDD

En este segundo caso de uso se trabajará con el conjunto de datos NSL-KDD, que es una mejora del conjunto de datos original de detección de intrusiones en la red llamado KDD Cup 99. El conjunto de datos original (KDD Cup 99) fue creado y administrado por el Laboratorio Lincoln del MIT para el Programa de Evaluación de Detección de Intrusiones de DARPA. Este dataset incluye una amplia variedad de intrusiones simuladas en un entorno de red militar.

El Laboratorio Lincoln del MIT creó un entorno de prueba para adquirir durante nueve semanas, una cantidad ingente datos procedentes del volcado de todo el tráfico de red producido en una red de área local (LAN) que simulaba a una LAN típica de la Fuerza Aérea de EE. UU. Durante este tiempo, operaron esta LAN como si fuera un verdadero entorno de la Fuerza Aérea, pero la acribillaron con múltiples ataques.


### :one: Justificación de esta elección

He seleccionado el conjunto de datos NSL-KDD porque ha sido y sigue siendo uno de los dataset más utilizados para la detección de intrusiones. Sé que existen otros datasets más modernos como UNSW-NB15, UGR'16, CICIDS2017 o CSE-CIC-IDS-2018, entre otros. Sin embargo, me he decantado por este conjunto de datos por los siguientes motivos:

1. En el análisis de malware del prier caso de uso se ha empleado las muestras de malware más modernas y se quería hacer justo lo contrario en este caso de uso, es decir, sumergirse en los fundamentos de un dataset relativamente antiguo para aprender las bases de las técnicas de detección de intrusiones antes de pasar a datasets más complejos que implementen nuevas características como el anonimato o la encriptación.

2. Como se ha mencionado, es una mejora del dataset KDDCup99, que fue uno de los primeros conjuntos de datos en el campo de la detección de intrusiones en las redes.

3. Considero que es un dataset suficientemente maduro, ampliamente utilizado por los profesionales de la ciencia de datos de seguridad, siendo objeto de numerosos estudios y comparaciones con otros datasets que también ayudan a crear modelos de detección de intrusiones. Considero que esto nos proporciona una base sólida para poder evaluar y comparar el rendimiento de diferentes algoritmos de aprendizaje.

4. Aunque no es tan grande como algunos conjuntos de datos más modernos mencionados anteriormente, el NSL-KDD es lo suficientemente grande como para entrenar modelos de machine learning de manera efectiva y también lo suficientemente manejable para experimentación y desarrollo.


### :two: Descripción de los diferentes archivos

- KDDTrain+.arff: conjunto completo de entrenamiento NSL-KDD con etiquetas binarias en formato ARFF.
- KDDTrain+.txt: conjunto completo de entrenamiento NSL-KDD que incluye etiquetas de tipo de ataque y nivel de dificultad en formato CSV.
- KDDTrain+_20Percent.arff: subconjunto del 20% del archivo KDDTrain+.arff.
- KDDTrain+_20Percent.txt: subconjunto del 20% del archivo KDDTrain+.txt.
- KDDTest+.arff: conjunto completo de test NSL-KDD con etiquetas binarias en formato ARFF.
- KDDTest+.txt: conjunto completo de test NSL-KDD que incluye etiquetas de tipo de ataque y nivel de dificultad en formato CSV.
- KDDTest-21.arff: subconjunto del archivo KDDTest+.arff que no incluye registros con un nivel de - dificultad de 21 de 21 en formato ARFF.
- KDDTest-21.txt: subconjunto del archivo KDDTest+.txt que no incluye registros con un nivel de dificultad de 21 de 21 en formato CSV.
- training_attack_types.txt: este archivo no se incluye como parte del conjunto de datos NSL-KDD, pero sí en el conjunto de datos KDD Cup 99 original, y puede encontrarse en la URL de la licencia.
- kddcup.names: representa una lista de características. Este archivo no se incluye como parte del conjunto de datos NSL-KDD, pero sí en el conjunto de datos KDD Cup 99 original, y puede encontrarse en la URL de la licencia.


### :key: Licencia de uso

**Conjunto original de datos KDD Cup 99**  
https://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html

**Conjunto mejorado NSL-KDD**  
M. Tavallaee, E. Bagheri, W. Lu, and A. Ghorbani, “A Detailed Analysis of the KDD CUP 99 Data Set,” Submitted to Second IEEE Symposium on Computational Intelligence for Security and Defense Applications (CISDA), 2009.  
https://www.unb.ca/cic/datasets/nsl.html