CNN Image Classification using CIFAR-10
📌 Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to classify images from the CIFAR-10 dataset. The model learns important visual features through convolution and pooling layers and predicts one of the 10 image categories.

🚀 Dataset

The project uses the CIFAR-10 dataset containing 60,000 color images of size 32×32.

Classes
Airplane
Automobile
Bird
Cat
Deer
Dog
Frog
Horse
Ship
Truck
Dataset Split
Training Images: 50,000
Testing Images: 10,000
🛠️ Technologies Used
Python
PyTorch
Torchvision
NumPy
🧠 CNN Architecture
Input Image (3 × 32 × 32)

↓ Conv2D + ReLU
↓ MaxPooling

↓ Conv2D + ReLU
↓ MaxPooling

↓ Conv2D + ReLU
↓ MaxPooling

↓ Flatten

↓ Fully Connected Layer

↓ Output Layer (10 Classes)
📊 Workflow
Load CIFAR-10 Dataset
Apply Transformations
Create DataLoaders
Build CNN Model
Train the Model
Test Model Accuracy
🎯 Features
Multi-class Image Classification
CNN-based Feature Extraction
PyTorch Implementation
CIFAR-10 Dataset Support

The CNN model was trained on the CIFAR-10 dataset and achieved a test accuracy of 74.79% on unseen images.




