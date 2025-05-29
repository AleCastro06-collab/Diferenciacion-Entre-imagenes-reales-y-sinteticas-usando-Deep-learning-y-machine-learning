# Clasificación de Imágenes Reales o Generadas por IA

![Banner](https://github.com/user-attachments/assets/b6a94084-8619-4a08-bcd1-eae42b480ce4)

---

## 📌 Descripción del Proyecto

Repositorio que presenta modelos y métodos probados sobre el dataset **CI-FAKE**, para la clasificación de imágenes como **reales** o **sintéticas (generadas por IA)**.

---

## 📚 Índice

- [📌 Descripción del Proyecto](#-descripción-del-proyecto)
- [📊 Dataset](#-dataset)
- [🧠 Modelos Utilizados](#-modelos-utilizados)
- [⚙️ Requisitos](#️-Archivos-opcionales)
- [📝 Resultados](#-resultados)
- [📎 Referencias](#-referencias)

---

<!-- Aquí puedes seguir desarrollando secciones como estas: -->

## 📊 Dataset


The dataset contains two classes - REAL and FAKE.

For REAL, they collected the images from Krizhevsky & Hinton's CIFAR-10 dataset

For the FAKE images, they generated the equivalent of CIFAR-10 with Stable Diffusion version 1.4

There are 100,000 images for training (50k per class) and 20,000 for testing (10k per class)

🔗 [Ir al dataset en Kaggle](https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images)

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

- Estado del proyecto: Finalizado
- Acceso al Proyecto: Abierto
- Tecnologías utilizadas: DeepLearning, MachineLearnig and clustering methods
- Personas Desarrolladoras del Proyecto: Alejandro Castro Rondón y Nicolas Linares Rojas
