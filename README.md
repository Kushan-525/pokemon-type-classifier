# Pokémon Type Classifier

Este proyecto implementa un modelo de **Visión por Computadora** basado en Deep Learning para identificar los tipos elementales (Fuego, Agua, Planta, etc.) de un Pokémon basándose únicamente en su imagen visual.

El modelo fue entrenado utilizando **Transfer Learning** con arquitecturas como **MobileNetV2** y **ResNet50**, aplicando técnicas de *Fine-Tuning* y *Data Augmentation* para mejorar la precisión en un problema de clasificación multi-etiqueta.

## 🚀 Características principales

* **Enfoque:** Clasificación Multi-etiqueta (*Multi-label classification*) para soportar Pokémon con tipos duales.
* **Arquitectura:** Uso de modelos pre-entrenados en ImageNet como base (MobileNetV2).
* **Estrategia de Entrenamiento:** Fine-Tuning en dos fases (entrenamiento de la cabeza y descongelamiento parcial de la base).
* **Stack Tecnológico:** Python, TensorFlow, Keras, Pandas, Scikit-Learn.

---

## 📂 Obtención de los Datos (Dataset)

**Nota Importante:** Debido a que el dataset de imágenes supera los 500MB, este no se encuentra alojado directamente en este repositorio de GitHub.

Para ejecutar este proyecto, debes descargar las imágenes y colocarlas en la estructura correcta:

1.  **Descarga de los datasets** desde los siguientes enlaces:
    * 📥 **[Dataset of 32000 Pokemon Images & CSV, JSON](https://www.kaggle.com/datasets/divyanshusingh369/complete-pokemon-library-32k-images-and-csv)**
    * 📥 **[Pokemon Image Dataset](https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types)**
2.  **Descomprime el archivo** en la raíz de este proyecto.
