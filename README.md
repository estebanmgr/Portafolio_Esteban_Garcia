# [Esteban García](https://www.linkedin.com/in/estebanmgr/)

Ingeniero Industrial especializado en ciencia de datos e inteligencia artificial, con alta capacidad analítica y de optimización de procesos

# [Proyecto 1: Predicción del precio de venta de una vivienda.](https://github.com/estebanmgr/California_Housing_Price)
*	Predecir el valor medio de una vivienda en el área de California tomando en cuenta varios datos significativos de la zona (Ingreso medio de la población cercana, número de habitaciones, número de baños, edad de la vivienda, etc.).
* Analizar los datos para hacer una limpieza de los mismos con el finde ordenarlos y que ayuden a trabajar mejor los distintos modelos de regresión.
* Utilizar y entrenar distintos modelos de regresión (Lineal, Árbol de decisiones, Support Vector Machine, Random Forest, K neigbors y gradient boosting) para luego poder contrastar los resultados con una parte de los datos que no han sido utilizarlos y así medir su eficacia.
* Evaluar el modelo con el mejor porcentaje de eficacia para luego probarlo con un conjunto de evaluación ya depurado.

# [Proyecto 2: Predicción de la ocurrencia de un incendio forestal.](https://github.com/estebanmgr/Incendios_Forestales)
Para este utilicé la base de datos de incendios forestales en la zona de Algeria con el fin de preecir la posibilidad de ocurrencia un incendio y así poder ayudar a los recursos destinados para combatirlos y poder disminuir su devastadoras consecuencias, para esto:
* Limpié y analicé los datos para asegurarme que existiera una homogeneidad en los mismos y que no tuviesemos valores faltantes que tratar así poder entrenar correctamente los distintos modelos de clasificación.
* Utiliar y entrenar distintos modelos de clasificación (Regresión logistica, Nearest neighbors, Suport vector machine (Linear, rbf, sigmoide y poly), Naive bayes, Arbol de decisiones y Random forest) para luego poder contrastar los resultados con una parte de los datos que no han sido utilizarlos y así medir su precisión.

# [Proyecto 3: Detección de emociones faciales en tiempo real.](https://github.com/estebanmgr/Deteccion_de_emociones_faciales)
En este proyecto creé y entrené una red neuronal para la detección de emociones faciales, para esto utilizé la transferencia de conocimientos de una red neuronal pre entrenada y la modifiqué para que se ajustara al caso de estudio. Esto puede ser de utilidad para las personas que deseen subir una foto y detectar emociones de las personas que aparecen en ella, también puede servir como base para utilizarlo en algun filtro de alguna red social.

Logré que el modelo predijese con una precisión del 85% en 15 epocas gracias a la transferencia de conocimiento de un modelo pre entrenado de la librería de keras.preprocessing y ajustandola muy poco, para la mayoría de los casos este porcentaje de acierto será más que necesario para detectar las emociones. El nombre de la red utilizada fue la de "MobileNetV2".
