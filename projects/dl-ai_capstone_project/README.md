# **Comparing VGG16, ResNet50, and ResNet18 for Image Classification**

## 📌 **Project Overview**  
This project is designed to practice and apply deep learning concepts I gained from the **AI Capstone Project with Deep Learning** course by IBM on Coursera. The goal is to build image classifiers using transfer learning with popular pre-trained models, including **VGG16**, **ResNet50**, and **ResNet18**, evaluate their performance on classification tasks, and compare their effectiveness.

## 🎯 **Learning Objectives**  
By completing this project, I:
- Implemented **transfer learning** using **VGG16**, **ResNet50**, and **ResNet18** pre-trained models
- **Prepared and preprocessed image data** for deep learning tasks
- **Fine-tuned** pre-trained models for specific classification problems
- **Modified model architectures** by replacing output layers for binary classification
- **Evaluated and compared** the performance of different model architectures
- Gained practical experience with **Keras**, **TensorFlow**, and **PyTorch** frameworks

## 🛠 **Technologies & Tools Used**  
- **Python**  
  - Libraries: TensorFlow, Keras, PyTorch, NumPy, Matplotlib, Pandas  
- **Jupyter Notebook** (for coding and experimentation)  
- **Pre-Trained Models**:
  - VGG16 (Visual Geometry Group)
  - ResNet50 (Residual Network with 50 layers)
  - ResNet18 (Residual Network with 18 layers)
- **Image Data** (for binary and multi-class classification tasks)

## 💻 **Implementation Details**
- **ResNet18 Implementation**: Used PyTorch to load a pre-trained ResNet18 model, froze the pre-trained layers, and modified the final fully-connected layer for binary classification (positive/negative samples)
- **VGG16 vs ResNet50**: Implemented both models using Keras and TensorFlow, comparing their performance on concrete crack image classification
- **Transfer Learning Approach**: Leveraged knowledge from pre-trained models on ImageNet to achieve high accuracy with limited training data
- **Model Evaluation**: Analyzed performance metrics including accuracy, loss curves, and misclassified samples