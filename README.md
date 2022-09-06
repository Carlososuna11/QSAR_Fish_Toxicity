# QSAR FISH TOXICITY

### Descripción

Las arquitecturas de dicha red neuronal se realizaron como proyecto para el curso de Redes Neuronales y Deep Learning en la Universidad Autónoma de Occidente, de Cali, Colombia. Y predice `Concentración de una sustancia tóxica necesaria para matar al 50% de una población.`, cuyo dataset fue suministrado.

## Enunciado del Proyecto

Entrenar una Red MLP superficial en Tensorflow2-Keras que permita resolver el problema de regresión definido de acuerdo al data set seleccionado. La red entrenada deber ser emulada en Arduino como plataforma de implementación final.

### Anotaciones

Se recomienda primero entrenar la red neuronal en Tensorflow2-Keras, pruebe **al menos tres optimizadores y tres diferentes arquitecturas de red neuronal** (máximo 3 capas ocultas). Verificar el comportamiento de la red calculando el coeficiente de regresión obtenido. Cuando la red este convenientemente entrenada, implementarla en Arduino donde se debe verificar el correcto funcionamiento de la misma, para tal fin, la red implementada en Arduino debe recibir las entradas necesarias y generar la salida de la misma la cual debe coincidir con la obtenida en Tensorflow2-Keras. Algunas elementos a considerar para el mini-proyecto
    - Entendimiento del data set seleccionado.
    - Partición del data set en datos de entrenamiento y validación.
    - Normalización de las variables del data set.
    - Entrenamiento del modelo neuronal y la selección de su arquitectura. Usar tensor board para la visualización del grafo de los modelos generados.
    - Validación de los modelos neuronales trabajados para seleccionar el mejor.
    - Validación del mejor modelo neuronal implementado en Arduino verificando que su comportamiento es igual a la entrenada en Keras.

### DataSet Utilizado: [`QSAR FISH TOXICITY`](https://archive.ics.uci.edu/ml/datasets/QSAR+fish+toxicity)

> This dataset was used to develop quantitative regression QSAR models to predict acute aquatic toxicity towards the fish Pimephales promelas (fathead minnow) on a set of 908 chemicals. LC50 data, which is the concentration that causes death in 50% of test fish over a test duration of 96 hours, was used as model response. The model comprised 6 molecular descriptors: MLOGP (molecular properties), CIC0 (information indices), GATS1i (2D autocorrelations), NdssC (atom-type counts), NdsCH ((atom-type counts), SM1_Dz(Z) (2D matrix-based descriptors). Details can be found in the quoted reference: M. Cassotti, D. Ballabio, R. Todeschini, V. Consonni. A similarity-based QSAR model for predicting acute toxicity towards the fathead minnow (Pimephales promelas), SAR and QSAR in Environmental Research (2015), 26, 217-243; doi: 10.1080/1062936X.2015.1018938

### Referencias

- M. Cassotti, D. Ballabio, R. Todeschini, V. Consonni. A similarity-based QSAR model for predicting acute toxicity towards the fathead minnow (Pimephales promelas), SAR and QSAR in Environmental Research (2015), 26, 217-243; doi: 10.1080/1062936X.2015.1018938.