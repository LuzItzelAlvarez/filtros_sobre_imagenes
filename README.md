# Clasificación de imágenes con CNN usando optimizadores Adam y SGD en la base Intel Image Classification.

## Descripción

Este proyecto entrena y evalúa dos modelos de redes neuronales convolucionales (CNN) para la clasificación de imágenes en seis categorías: bosques, calles, montañas, edificios, mares y glaciares, utilizando el dataset Intel Image Classification. El propósito es comparar el rendimiento de dos optimizadores: Adam y SGD, y analizar su desempeño en términos de precisión y pérdida tanto en el conjunto de entrenamiento como en el conjunto de validación.

## Requisitos

 - Python 3.x
 - TensorFlow
 - Keras
 - Numpy
 - Matplotlib
 - Scikit-learn
 - PIL (Python Imaging Library)

## Resultados

Durante el entrenamiento, se utilizaron dos optimizadores: Adam y SGD. Los resultados mostraron que el modelo entrenado con Adam logró una mayor precisión en el conjunto de validación en comparación con el modelo SGD.

### Resultados del Modelo Adam:
 - Precisión de Entrenamiento: 88.94%
 - Precisión de Validación: 66.00%
### Resultados del Modelo SGD:
 - Precisión de Entrenamiento: 85.17%
 - Precisión de Validación: 67.20%

## Conclusiones:

El optimizador Adam superó al optimizador SGD en términos de precisión tanto en el conjunto de entrenamiento como en el de validación. Aunque el modelo con SGD presentó un desempeño competitivo, el modelo con Adam logró una convergencia más rápida y una mayor precisión en general.
