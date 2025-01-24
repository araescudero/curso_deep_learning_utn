# 🎭 Clasificación de Rostros usando Redes Neuronales: Labeled Faces in the Wild (LFW)

Este proyecto aborda la clasificación de rostros utilizando un subconjunto del dataset **Labeled Faces in the Wild (LFW)** disponible en scikit-learn. El objetivo principal es entrenar y evaluar dos modelos de redes neuronales: 

1. **🔗 Red Densa (Fully Connected Neural Network)**  
2. **🌀 Red Convolucional (Convolutional Neural Network)**  

Ambos modelos se diseñaron para resolver un problema de clasificación multiclase, distinguiendo entre 7 personas con al menos 70 imágenes disponibles en el dataset.

## 📂 Estructura del Proyecto

- **Dataset**:  
  Utilizamos el dataset `LFW` proporcionado por la biblioteca scikit-learn, que incluye imágenes en escala de grises de tamaño uniforme y etiquetas correspondientes a los rostros de las personas.  
  - 📏 **Tamaño de las imágenes**: `(h, w) = (62, 47)`  
  - 🖼️ **Total de muestras**: `n_samples = 1288`  
  - 🎭 **Clases**: `n_classes = 7`  

- **⚙️ Preprocesamiento de Datos**:  
  - Redimensionamos las imágenes y agregamos un canal para las redes convolucionales.
  - Estandarizamos las características usando `StandardScaler` para mejorar la convergencia del modelo.
  - Dividimos el dataset en entrenamiento y prueba utilizando `train_test_split`, con una fracción de datos de prueba entre el 20% y el 30%.

- **🧠 Modelos**:
  - **Red Densa**:  
    Incluye capas totalmente conectadas con activaciones ReLU, regularización mediante Dropout y una capa de salida con activación Softmax.
  - **Red Convolucional**:  
    Consiste en capas convolucionales seguidas de MaxPooling, Dropout y una capa totalmente conectada para la clasificación final.

## 📊 Resultados

- **Métricas de Evaluación**:  
  - 🔢 **Precisión (`Accuracy`)** en los conjuntos de entrenamiento y prueba.
  - 🧮 **Matriz de confusión** para evaluar el desempeño del modelo en cada clase.
  
- **🎯 Objetivos Cumplidos**:  
  Ambos modelos lograron:
  - Precisión de al menos **90%** sobre el conjunto de entrenamiento.
  - Precisión de al menos **80%** sobre el conjunto de prueba.

## 🖼️ Visualizaciones

Se incluyen visualizaciones clave del dataset y del desempeño de los modelos, como:
- 📷 Ejemplos del dataset de entrenamiento.
- 📈 Matrices de confusión.
- 📉 Curvas de pérdida y precisión durante el entrenamiento.

## 🛠️ Requisitos

- 🐍 **Python 3.8+**
- 📦 Bibliotecas principales:
  - `scikit-learn`
  - `numpy`
  - `matplotlib`
  - `tensorflow`
  - `seaborn`


   
