**Fecha**: 9 de marzo de 2025  
**Autor**: Luis Alejandro de la Rosa García

# 📝 Binary Classification NLP

Este proyecto implementa un modelo de clasificación binaria utilizando técnicas de procesamiento de lenguaje natural (NLP). Se entrena una red neuronal para predecir si una reseña de una película es positiva (1) o negativa (0).

## 🎯 Objetivo  
Crear un modelo de clasificación binaria que utilice métodos de NLP y redes neuronales para hacer predicciones precisas. El objetivo principal es entender cómo funciona una red neuronal en el contexto de la clasificación binaria.

## 🚀 Uso  
El código está encapsulado en una función dentro del archivo `imdb_classification.py`. Para entrenar el modelo y hacer predicciones, usa un archivo `main.py` con el siguiente contenido:

python
from imdb_classification import train_imdb_model

# Llamar a la función para entrenar el modelo y obtener los datos de prueba
model, x_test, y_test = train_imdb_model()

# Realizar una predicción con el modelo entrenado
print("\nEjemplo de predicción en nuevas reseñas:")
print(model.predict(x_test[:2]))

# 📁 Estructura del Proyecto
bash
Copiar
Editar
Binary_classification_NLP/
│── Src/
│   ├── imdb_classification.py  # Lógica del modelo
│   ├── main.py  # Punto de entrada
│── README.md  # Documentación
└── requirements.txt  # Dependencias
# 📝 Descripción de Archivos
Src/imdb_classification.py: Contiene la lógica del modelo de clasificación binaria basado en NLP, utilizando vectorización de texto y una red neuronal básica.
main.py: Punto de entrada del programa, donde se entrena y visualiza el modelo.
requirements.txt: Lista de dependencias necesarias para ejecutar el proyecto.
