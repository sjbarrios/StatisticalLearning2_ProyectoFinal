# StatisticalLearning2_Proyecto Final

### Parte 1 Proyecto Final Statistical Learning 2

La Parte No. 1 del Proyecto Final del Curso corresponde al diseño de una FeedForward Neural Network.

En este notebook se trabaja sobre un dataset denominado "Parkinsons" (aprobado para el proyecto) que recopila información biomédica de voces de pacientes con esta enfermedad.

El trabajo consiste en encontrar una arquitectura de red neuronal FeedForward para un clasificador binario, que prediga con una exactitud de al menos 85% si un paciente tiene o no la enfermedad basado en la información biomédica de su voz.

La experimentación incluye: Inicialización Aleatoria, Normalización de Batch, Normalización Dropout, Experimentación con Número de Unidades y Profundidad, con la API de Keras.

El repositorio consta de:
1. Notebook "Parte1.ipynb"
2. Modelo Entrenado Final "FFN_Parkinsons.h5"
3. Dataset "parkinsons.csv"
4. Carpeta con LOGS de TensorBoard
5. Carpeta de Imágenes (utilizadas para mostrar arquitectura final y experimentación en TensorBoard dentro del notebook).
6. Carpeta de Checkpoints, donde se guarda el modelo cada ciertas iteraciones, con el objetivo de evidenciar que se guarda el progreso del entrenamiento. Se utiliza Keras Callbacks.

### Parte 2 Proyecto Final Statistical Learning 2

La Parte No. 2 del Proyecto Final del Curso corresponde al uso de Redes Neuronales Convolucionales CNN. En este caso, se propuso y se aprobó el trabajo sobre el paper de "Style Transfer", utilizando una arquitectura de Red Convolucional VGG19 entrenada sobre el dataset "ImageNet", y utilizarla para generar funciones de costo de contenido + estilo, e implementar Style Transfer con imágenes especificadas. Adicional, se muestran las representaciones intermedias obtenidas al extraer el contenido de los filtros utilizando un modelo auxiliar de Keras para visualización.

El repositorio consta de:
1. Notebook "Parte2.ipynb"
2. Carpeta de Checkpoints. En este caso específico, los checkpoints son muy pesados (78MB) por lo que para subir a GitHub (que acepta tamaño máximo de 25MB) se muestra una imagen como evidencia de los checkpoints generados con el código. Estos están a disposición con gusto a solicitud a "sergio.barrios@galileo.edu".
3. Carpeta "fuentes" con las imágenes utilizadas para experimentación.
4. Carpeta con LOGS de TensorBoard
5. Carpeta de Imágenes (utilizadas para mostrar la fase de experimentación en TensorBoard dentro del notebook).
6. Carpeta de Resultados "M+VanGogh" con el progreso de una transferencia de estilo cada 100 iteraciones.
7. Carpeta de Resultados "SF+Cubism" con el progreso de otra transferencia de estilo cada 1000 iteraciones.
