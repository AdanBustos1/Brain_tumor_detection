<h1 align="center">🧠 DEEP LEARNING MODEL FOR BRAIN TUMOR DETECTION</h1>

<img src="/img/EXAMPLE.jpg" alt="brain" width="400" align="center"/>

## Descripción del Proyecto

Este proyecto implementa un modelo de **aprendizaje profundo** para la detección automatizada de tumores cerebrales a partir de imágenes de resonancia magnética (MRI). El sistema utiliza redes neuronales convolucionales (CNN) para clasificar imágenes entre dos categorías: **presencia de tumor** o **ausencia de tumor**.

## Dataset

- **Fuente**: Brain MRI Images para Detección de Tumores Cerebrales
- **Estructura**: 
  - Carpeta `/no`: Imágenes de cerebros sin tumores
  - Carpeta `/yes`: Imágenes de cerebros con tumores
- **Formato**: Imágenes de resonancia magnética en escala de grises
- **Propósito**: Entrenamiento, validación y prueba del modelo

## Características del Modelo

- **Arquitectura**: Red Neuronal Convolucional (CNN) entrenada con Keras/TensorFlow
- **Entrada**: Imágenes de MRI (preprocesadas y normalizadas)
- **Salida**: Clasificación binaria (tumor/sin tumor) con probabilidades
- **Optimización**: Entrenamiento monitoreado con validación cruzada
- **Pérdida**: Binary Crossentropy

## Tecnologías Utilizadas

- **TensorFlow & Keras**: Framework de deep learning
- **NumPy**: Procesamiento numérico
- **Pandas**: Manipulación de datos
- **Matplotlib**: Visualización de imágenes y gráficos
- **Python**: Lenguaje de programación

## Estructura del Proyecto

```
├── main.ipynb                          # Notebook principal con el código
├── model.h5                            # Modelo entrenado guardado
├── brain-mri-images-for-brain-tumor-detection/
│   └── brain_tumor_dataset/
│       ├── no/                         # Imágenes sin tumores
│       └── yes/                        # Imágenes con tumores
├── img/                                # Imágenes de demostración
└── README.md                           # Este archivo
```

## Uso del Modelo

El notebook `main.ipynb` contiene:
- Carga y exploración del dataset
- Preprocesamiento de imágenes
- Desarrollo y entrenamiento del modelo
- Evaluación del rendimiento
- Visualización de predicciones
- Pruebas en nuevas imágenes

## Resultados

El modelo clasificará cada imagen de MRI como:
- **Positivo**: Presencia de tumor cerebral detectada
- **Negativo**: No se detecta presencia de tumor

La salida incluye tanto la clasificación como la confianza de la predicción.
