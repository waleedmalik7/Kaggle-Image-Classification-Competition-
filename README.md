# CIFAR-100 Image Classification Project

## Overview
This project focuses on classifying images from the **CIFAR-100 dataset** using a custom Convolutional Neural Network (CNN). The project includes detailed analysis, model development, and performance tuning, resulting in achieving a **Top 20 position** (out of 200) on the [Kaggle competition leaderboard](https://www.kaggle.com/competitions/cifar-challenge-classify-the-world-of-objects/leaderboard).

## Placement (20th place)
![image](https://github.com/user-attachments/assets/e952dd64-a3c6-45b1-a078-45f24f1d9527)


## Dataset
- **Dataset**: CIFAR-100
- **Images**: 60,000 color images of 32x32 pixels
- **Classes**: 100 distinct categories grouped into 20 superclasses

### Challenge
The goal was to classify images into their respective categories with high accuracy using deep learning techniques.

---

## Features
### 1. **Preprocessing & Data Augmentation**
- **Normalization**: Standardized pixel values using channel-wise means and standard deviations.
- **Data Augmentation**:
  - Random horizontal flips
  - Random cropping with padding of 4 pixels

### 2. **Model Design**
- **Architecture**:
  - Three convolutional layers (32, 64, and 128 channels)
  - Max-pooling after every two convolutional layers
  - Dropout (50%) for regularization
  - Two fully connected layers
  - Output: 100 categories
- **Optimizer**: Stochastic Gradient Descent (SGD)
- **Loss Function**: Categorical Cross-Entropy
- **Learning Rate**: 0.05

### 3. **Training Results**
- **Train Accuracy**: 66.81%
- **Test Accuracy**: 56.03%
- **Kaggle Leaderboard Score**: **0.3184**

---

## Achievements
- **Top 20 Leaderboard Position**: Reached the top 20 in the [Kaggle competition](https://www.kaggle.com/competitions/cifar-challenge-classify-the-world-of-objects/overview) by balancing model simplicity and computational efficiency.
- **Key Strategies for Success**:
  - Leveraging data augmentation to improve generalization.
  - Employing dropout to reduce overfitting.
  - Optimizing training with an efficient CNN architecture.

---

## Files
### 1. [Report: Model Design and Performance Analysis](./Model_Design_and_Performance_Analysis.pdf)
This document provides a detailed explanation of the model design, preprocessing methods, and performance analysis.

### 2. [Notebook: ImageClassification_Kaggle_CNN.ipynb](./ImageClassification_Kaggle_CNN.ipynb)
This Jupyter Notebook contains the implementation of the CNN model, including:
- Data preprocessing
- Model architecture and training
- Performance evaluation and visualization

---

## Instructions
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook kaggle.ipynb
   ```
3. Follow the cells to understand the data preprocessing, model training, and evaluation process.

---

## Lessons Learned
- The importance of balancing model complexity and computational efficiency.
- Regularization techniques, such as dropout, are essential for reducing overfitting.
- Leveraging data augmentation can significantly improve model robustness and generalization.

---

## Future Work
- Experiment with more complex architectures like ResNet or DenseNet.
- Explore advanced regularization techniques (e.g., weight decay, mixup).
- Implement learning rate schedulers to optimize convergence.

---

## Acknowledgments
This project was completed as part of **COMPSCI 4ML3: Introduction to Machine Learning** at McMaster University under the guidance of the course instructors.

---

## Contact
**Waleed Malik**
- Kaggle: [waleedmalik7](https://www.kaggle.com/waleedmalik7)
- Email: [waleedmalik027@gmail.com](mailto:waleedmalik027@gmail.com)
