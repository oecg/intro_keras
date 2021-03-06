Pedro Atencio - 2019

Repositorio del taller - Introducción a las redes neuronales en Keras - desarrollado en la Universidad Nacional del Sur, Bahía Blanca, Argentina.


## Contenido:

1. Conceptos generales (días 1 y 2)
    1. Regresor logistico como una neurona. <a href="https://colab.research.google.com/drive/1G4FS7fqJYl0iq3m1oX9IWrH7l6iCymMd">link</a>
        1. Análisis desde el grafo de cómputo.
        2. Implementación tradicional.
        3. Broadcasting / Vectorization.
        4. Implementación vectorizada.
        5. Descenso del gradiente.
    2. El operador XOR. <a href="https://colab.research.google.com/drive/1cdyj7wISIXyg1TIjX88vXlGZgTfXOPlp">link</a>
        1. Clasificación no-lineal.
        2. XOR y su descomposición lineal.
        3. Regresores lineales en capas.
    3. Red Neuronal y Backpropagation (descenso del gradiente generalizado) <a href="https://colab.research.google.com/drive/1nQ69bRBGqe8sbtT10WhchyXr6Kvd14fL">link</a>
        - Notación.
        - Forward propagation.
        - Backpropagation.
        - Errores y funciones de activación.
2. Conceptos tecnológicos (tensorflow.keras) (días 3 y 4)
    1. Introducción a Keras. <a href="https://colab.research.google.com/drive/1HbKczB-BXFO2Xg4QE0W2Ix5oBa_xFumE">link</a>
        1. Primera red en Keras.
        2. Ensamble de la red: a) Construcción como lista b) Agregación de capas (model.add) b) "Cableado" manual.
        3. Compilación.
        4. Preparacion del dataset.
            Split.
            K-Fold.
        5. Entrenamiento y validación.
            model.evaluate()
            Evaluacion durante el entrenamiento.
        6. Ejemplo: MNIST.
    2. Aplicaciones. <a href="https://colab.research.google.com/drive/1ceI-3gWA448fZ44707oZ6BUBf5Tdarod">link</a>
        1. Clasificación y Regresión.
        2. Redes convolutivas.
        3. Redes recurrentes
        4. Utilizando una red profunda pre-entrenada.
        5. Deep features / Latent spaces.
        6. Fine-tuning: Utilizar una red pre-entrenada y afinarla para que trabaje con nuestros datos.
3. Conceptos utilitarios (día 5). <a href="https://colab.research.google.com/drive/1_wJkHW47yMfTmCy2v-iit3AeASd0Nf91">link</a>
    1. Callbacks: Tomar decisiones durante el proceso de entrenamiento.
    2. Lamba layers: Construir nuestras propias capas de red neuronal.
    3. Estimación del  learning_rate
    4. Grid search: Encontrar los mejores parámetros de la red.
    5. Custom losses: Construir nuestras propias funciones de error.
    6. Custom Activations: Construir nuestras propias funciones de activación.
