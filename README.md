# Clasificación de Imágenes Reales o Generadas por IA

![Intelgencia artificial_page-0001](https://github.com/user-attachments/assets/1f683238-1e3d-4ef5-bfd9-e151d88b7d10)

---

## 📌 Descripción del Proyecto

Repositorio que presenta modelos y métodos probados sobre el dataset **CI-FAKE**, para la clasificación de imágenes como **reales** o **sintéticas (generadas por IA)**.

---

## 📚 Índice

- [📌 Descripción del Proyecto](#-descripción-del-proyecto)
- [📊 Dataset](#-dataset)
- [📁 Acceso al proyecto](#-acceso-al-proyecto)
- [🧠 Modelos Utilizados](#-modelos-utilizados)
- [📃 Detalles](#-detalles)
- [:hammer:Funcionalidades del proyecto]()
- [🎥 video]()
- [👨‍💻 Autores]()

---

## 📊 Dataset

The dataset contains two classes - REAL and FAKE.

For REAL, they collected the images from Krizhevsky & Hinton's CIFAR-10 dataset

For the FAKE images, they generated the equivalent of CIFAR-10 with Stable Diffusion version 1.4

There are 100,000 images for training (60k per class) and 20,000 for testing (10k per class)

🔗 [Ir al dataset en Kaggle](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images)

---

## 📁 Acceso al proyecto
- Descarga y montar el archivo ´.ipynb´ a un collab notebook

### 🛠️ Abre y ejecuta el proyecto
- 📌 Referencia para celdas de codigo que son auxiliares
- 🥷🏿 Referencia a celdas para codigo que no usa etiquetas
- 🏷️ Referencia a celdas para codigo que usa etiquetas
- 🚨 En la primera celda (Montar Drive), se debe cambiar la ruta a la carpeta personal de Drive donde están los archivos del proyecto.
- ✅ Despues de ejecutado el collab por primera vez, si se quiere trabajar sobre machine learning y clustering metods, solo hace falta ejecutar las celdas marcadas con este emoji, dado que los datos y modelos seran guardados en el drive personal de quien use el notebook

---

## 🧠 Modelos Utilizados
### Supervisados 🏷️
- Red convolucional 
- Red neuronal densa 
- Machine Learning (supervisado)
  - LogisticRegression
  - DecisionTree
  - RandomForest
  - SVM
### No supervisados 🥷🏿
- Arquitectura Autoencoder 
- Reductores de dimensionalidad 
  - PCA
  - T-SNE
- Clustering Methods 
  - Kmeans
  - DBSCAN
 
---

## 📃 Detalles
- Estado del proyecto: Finalizado
- Acceso al Proyecto: Abierto
- Tecnologías utilizadas: DeepLearning, MachineLearnig and clustering methods
- Personas Desarrolladoras del Proyecto: Alejandro Castro Rondón y Nicolas Linares Rojas

---

## :hammer: Funcionalidades del proyecto
- `Funcionalidad 1`: Testeo de arquitecturas no supervisadas en clasificación de imagenes 
- `Funcionalidad 2`: Identificacion de imagenes artificiales

---

## 🎥 Video
https://youtu.be/tBBVRDBCrAo

---

## 👨‍💻 Autores
| [<img src="https://avatars.githubusercontent.com/u/120747172?v=4" width=115><br><sub>Alejandro Castro Rondón</sub>](https://github.com/AleCastro06-collab) | [<img src="https://avatars.githubusercontent.com/u/159267707?v=4" width=115><br><sub>Nicolas Linares Rojas</sub>](https://github.com/nicolaslinaresrojas) |
| :---: | :---: | 
