# Trabajo Final de Grado
:mortar_board: Grado en Ingeniería Informática  
Universitat Oberta de Catalunya

## Aprendizaje Automático aplicado a la detección de intrusiones y de malware

### :clipboard: Resumen
Desde el 21 de noviembre de 1969, fecha en la que se conectó el ordenador SDS Sigma 7 al primer nodo de la primera red de computadoras llamada ARPANET, correspondiente a la Universidad de California en Los Ángeles (UCLA, EE. UU.), se han observado los riesgos que representan los ataques informáticos y la propagación de malware a través de la red.

Esta interconexión computacional ha avanzado a pasos agigantados desde sus inicios, y con ello, la cantidad de vulnerabilidades de seguridad que ha llevado asociadas. Por esta razón, a partir de aquel año 1969, se ha producido una batalla interminable entre actores atacantes y defensores que se remonta hasta el presente.

Al mismo tiempo que se producían estos avances tecnológicos, se iban generando en esta red enormes volúmenes de datos, lo que hoy en día se conoce como “Big Data”. Con el paso de los años, se ha descubierto el verdadero potencial que se esconde tras estos datos, y cómo a través de diferentes algoritmos, se puede dotar a una máquina computacional de la capacidad de recibir estas enormes cantidades de datos y aprender de ellos (denominado “aprendizaje automático” o “machine learning”).

Por tanto, si se fusionan todos estos avances, se obtiene la combinación perfecta para explotar todo el potencial existente en las técnicas de aprendizaje automático y poder aplicarlo al campo de la Seguridad Informática con el fin de contribuir en la mejora de los sistemas de defensa existentes.

En este Trabajo Final de Grado se abordará la creación de dos modelos de aprendizaje automático, a través del entrenamiento de diferentes algoritmos con un conjunto de datos seleccionado para cada modelo, con el objetivo de que estos modelos entrenados sean capaces de predecir malware y ataques en la red.


### :dart: Objetivos
Los objetivos que se pretenden alcanzar tras la finalización de este Trabajo Final de Grado son los siguientes:
1. Estudiar de qué forma se puede mejorar la seguridad de los sistemas de computación actuales, haciendo uso para ello, de los avances que se han producido en el campo de la Inteligencia Artificial en los últimos años.
2. Investigar sobre la rama de la IA que es capaz de dotar a los ordenadores de la capacidad de que aprendan por sí mismos, llamada Aprendizaje Automático.
3. Estudiar las características propias de los ataques informáticos en una red de comunicaciones y las características propias del malware.
4. Analizar los diferentes algoritmos y técnicas de aprendizaje automático existentes, que puedan aplicarse al campo de la seguridad informática con el objetivo de fortificar los sistemas actuales.
5. Conocer los diferentes métodos de preparación de los datos, selección de características y extracción de conocimiento.
6. Aprender las técnicas de diseño y construcción de modelos predictivos basados en aprendizaje automático, así como el entrenamiento posterior de estos modelos con diferentes conjuntos de datos.
7. Desarrollar un modelo predictivo para la detección de anomalías en la red y otro para la detección de malware, con el objetivo de que estos sean capaces de analizar los datos futuros sin supervisión humana.
8. Identificar los fortalezas y las debilidades que puede suponer implementar en una organización un sistema basado en técnicas de aprendizaje automático.


### :chart_with_upwards_trend: Fases del TFG
La estrategia elegida para afrontar este proyecto se sustenta en las siguientes fases:

1. **Fase de investigación** sobre los diferentes algoritmos y técnicas de aprendizaje automático que pueden ser aplicados con garantías de éxito al campo de la ciberseguridad, concretamente a la detección de malware y de ataques informáticos a través de la red.
2. **Fase de análisis** de la información recopilada, a través de numerosas fuentes, con el objetivo de seleccionar las técnicas y los algoritmos de aprendizaje automático que se consideren mas adecuados para los dos casos de uso propuestos.
3. **Fase de desarrollo** de dos modelos de aprendizaje automático; uno para cada caso de uso. Estos modelos se crearán a través del entrenamiento de los algoritmos elegidos con el conjunto de datos etiquetado de cada caso. Aquí es donde se llevará a la práctica toda la teoría investigada y detallada en los apartados teóricos de este TFG.


### :bulb: Casos de uso elegidos
Los dos casos de uso escogidos son los siguientes:

1. **Caso de uso 1**: Detección de malware empleando técnicas de Aprendizaje Automático.
En este caso de uso se presentará el análisis de diferentes archivos binarios con diferentes formatos, en base a la información extraída de su interior. A continuación, se entrenará a un modelo de aprendizaje automático con muestras de ejecutables benignos y de ejecutables maliciosos, con el objetivo de que el modelo final entrenado pueda predecir la tipología de un binario en base a sus características.

2. Caso de uso 2: Detección de ciberataques empleando técnicas de Aprendizaje Automático.
Para llevar a cabo este caso, se partirá de la captura de un determinado tráfico de red para posteriormente analizarlo, con la intención de encontrar patrones en estos paquetes que nos ayuden a detectar posibles anomalías. El objetivo de esta fase es crear un modelo de aprendizaje automático, a través del entrenamiento de diferentes algoritmos con este tráfico de red capturado, para encontrar cuál de ellos realiza una mejor clasificación de los ataques existentes en él (DDos, fuerza bruta, escalada de privilegios, etc). Esto nos ayudará a obtener el modelo más adecuado, que luego podrá ser capaz de recibir otro tráfico cualquiera y en base a su entrenamiento anterior, poder clasificarlo sin supervisión.
