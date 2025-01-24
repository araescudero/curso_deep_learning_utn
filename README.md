-- # 🎭 Clasificación de Rostros usando Redes Neuronales: Labeled Faces in the Wild (LFW) Este proyecto aborda la clasificación de rostros utilizando un subconjunto del dataset ** Rostros etiquetados en la naturaleza (LFW) ** disponible en scikit-learn. El objetivo principal es entrenar y evaluar dos modelos de redes neuronales: 1. **🔗 Red Densa (Fully Connected Neural Network)** 2. **🌀 Red Convolucional (Convolutional Neural Network)** Ambos modelos se diseñan para resolver un problema de clasificación multiclase, distinguiendo entre 7 personas con al menos 70 imágenes disponibles en el dataset. ## 📂 Estructura del Proyecto - **Dataset**: Utilizamos el conjunto de datos `LFW` proporcionado por la biblioteca scikit-learn, que incluye imágenes en escala de grises de tamaño uniforme y etiquetas correspondientes a los rostros de las personas. - 📏 **Tamaño de las imágenes**: `(h, w) = (62, 47)` - 🖼️ **Total de muestras**: `n_samples = 1288` - 🎭 **Clases**: `n_classes = 7`-**
