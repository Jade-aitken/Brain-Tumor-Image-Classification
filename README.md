# Brain-Tumor-Image-Classification using CNN (AlexNet)

### you can download the full file here:
https://drive.google.com/drive/folders/1ICxP1-BiSH2u-4VCgk2yA59O0l09EsMu?usp=sharing 

## 📌 Project Overview

This project focuses on building a **Convolutional Neural Network (CNN)** from scratch using the **AlexNet architecture** to classify brain tumors in MRI images. The model is designed for **multiclass classification**, distinguishing between different types of brain tumors using medical image data.

## 🧪 Objectives

- Analyze the image dataset to understand class distribution and visual characteristics.
- Build a **baseline AlexNet model** manually (without pre-trained weights).
- Improve performance by modifying the CNN architecture (dropout, batch normalization, optimizer tuning, etc.).
- Evaluate both models using multiple performance metrics to determine effectiveness.

## 📂 Dataset

The dataset contains MRI images categorized into multiple brain tumor types. Each image is labeled accordingly and varies in lighting, resolution, and angle.

## 📊 Exploratory Data Analysis (EDA)

- Color histograms for each tumor class
- Distribution of image resolutions and aspect ratios
- Analysis of variability (lighting, occlusion, angle)

## ⚙️ Preprocessing

- Image resizing and normalization
- Data split: 
  - Training set (with 15% reserved for validation)
  - Test set
- Applied data augmentation (optional)

## 🏗️ Model Development

### 🔹 Baseline Model: AlexNet (Manual)

- Built from scratch using Keras
- ReLU activations and max pooling
- Fully connected layers at the end
- Softmax activation for multiclass output

### 🔸 Modified Model

- Added **Dropout layers** to reduce overfitting
- Included **Batch Normalization** for faster convergence
- Experimented with **different learning rates**, optimizers, and additional layers
- Optionally tested alternative architectures like **DenseNet** or **EfficientNet**

## 📈 Evaluation Metrics

Models were evaluated on the test set using:

- **Accuracy**
- **Precision**
- **F1-Score**

