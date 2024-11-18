# Proyecto: Clasificación Morfológica de Tardígrados Utilizando Redes Neuronales Convolucionales
Este repositorio contiene los notebooks y recursos utilizados en el proyecto para la clasificación automática de géneros de tardígrados mediante técnicas de aprendizaje profundo, incluyendo el uso de modelos YOLO y ResNet50.

![val_batch1_labels](https://github.com/user-attachments/assets/2cd2fed8-d809-4daa-8501-4f499bdea47b)



## Archivos del Repositorio
### YOLOAPPRCHtardclass.ipynb
Este notebook contiene la implementación de la arquitectura YOLOv5 para la detección de tardígrados en imágenes microscópicas. Incluye:

Configuración y entrenamiento del modelo YOLOv5.
Evaluación del modelo en términos de precisión y recall.

### imgtratamientoTardis.ipynb
En este notebook se aborda el tratamiento y preprocesamiento de imágenes microscópicas, con los siguientes pasos:

Aplicación de técnicas de aumento de datos (data augmentation).
Ajustes en brillo, contraste y color.
Preparación de las imágenes para el entrenamiento de modelos.


### procesamiento_imágenes.ipynb
Este archivo se enfoca en las operaciones iniciales de procesamiento de las imágenes, tales como:

Conversión de formatos.
Segmentación y limpieza de las imágenes.
Organización en carpetas y etiquetado.


tranflearnResnet50.ipynb
Este notebook detalla la aplicación de transfer learning y fine-tuning utilizando ResNet50. Incluye:

Preparación del modelo preentrenado.
Ajuste de hiperparámetros para el dataset específico.
Resultados de evaluación y comparación de desempeño.
