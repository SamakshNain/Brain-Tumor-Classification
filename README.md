# 🧠 Brain Tumor Detection using Deep Learning

This project focuses on detecting brain tumors using deep learning, leveraging **ResNet-101** for accurate classification of MRI images into four categories: **Glioma Tumor, Meningioma Tumor, Pituitary Tumor, and Normal**.

## 📌 Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Model Architecture](#model-architecture)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Results](#results)
7. [Future Work](#future-work)
8. [Acknowledgments](#acknowledgments)

---

## 📖 Introduction
Brain tumors are abnormal growths of cells in the brain that require accurate diagnosis for effective treatment. This project implements a **Convolutional Neural Network (CNN)** using **ResNet-101**, a pre-trained deep learning model, to classify brain MRI images.

## 📂 Dataset
The dataset consists of MRI images categorized into:
- **Glioma Tumor**
- **Meningioma Tumor**
- **Pituitary Tumor**
- **Normal (No Tumor)**

The data is preprocessed and augmented for better generalization.

## 🏗 Model Architecture
- **Base Model**: ResNet-101 (pre-trained on ImageNet)
- **Custom Layers**: Fully connected layers for classification
- **Loss Function**: Categorical Cross-Entropy
- **Optimizer**: Adam

## ⚙️ Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/brain-tumor-detection.git
   cd brain-tumor-detection
2. Install Dependencies:  
   ```sh
   pip install -r requirements.txt
3. Run the Script  
   ```sh
   python brain_tumor_detection_final.py  
## 🚀 Usage  
- Load and visualize MRI images.  
- Preprocess and augment the dataset.  
- Train the ResNet-101 model on the dataset.  
- Evaluate and visualize model performance.  

## 📊 Results  
- Achieved high **classification accuracy** on validation data.  
- Plotted **loss and accuracy curves** for training and validation.  
- Showcased **sample predictions** for better interpretability.  

## 🔍 Future Work  
- Implement **data augmentation** for further accuracy improvement.  
- Explore **other deep learning architectures** such as EfficientNet.  
- Develop a **web-based interface** for real-time predictions.  

## 🙌 Acknowledgments  
- **Kaggle & Open-Source Datasets** for MRI scans.  
- **TensorFlow/Keras** for deep learning framework.  
- **Colab GPU** for training support.  
   

  
  
