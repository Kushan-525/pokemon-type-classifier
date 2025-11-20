# Pokémon Type Classifier

Este proyecto implementa un modelo de **Visión por Computadora** basado en Deep Learning para identificar los tipos elementales (Fuego, Agua, Planta, etc.) de un Pokémon basándose únicamente en su imagen visual.

## Características principales

* **Enfoque:** Clasificación Multi-etiqueta (*Multi-label classification*) para soportar Pokémon con tipos duales.
* **Arquitectura:** Utiliza **Transfer Learning** con modelos pre-entrenados (MobileNetV2 y ResNet50) como base.
* **Técnicas:** Implementa estrategias de **Fine-Tuning** (ajuste fino) en dos fases y **Data Augmentation** para mejorar la generalización.
* **Stack:** Python, TensorFlow, Keras, Pandas, Scikit-Learn.

## Sobre el proyecto

El objetivo de este proyecto es resolver un problema de clasificación de imágenes donde las clases no son mutuamente excluyentes (un Pokémon puede ser *Fuego* y *Volador* al mismo tiempo).

El modelo fue entrenado con un dataset de más de 15,000 imágenes. Se compararon arquitecturas como ResNet50 y MobileNetV2, optando finalmente por una estrategia de **Fine-Tuning** sobre MobileNetV2 debido a su eficiencia y precisión. El pipeline incluye preprocesamiento de imágenes, aumento de datos en tiempo real y métricas de evaluación específicas para problemas desbalanceados (Precision, Recall, F1-Score).
