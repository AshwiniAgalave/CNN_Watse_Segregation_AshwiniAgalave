# ♻️ Waste Material Segregation for Improving Waste Management using CNN

## 📌 Project Overview

This project implements a Convolutional Neural Network (CNN) for automatic waste material classification to support smart waste management and recycling systems.

The model classifies waste images into seven categories:
- Food Waste
- Glass
- Metal
- Paper
- Plastic
- Textile
- Vegetation

## 🎯 Objectives

- Build a CNN-based waste classifier
- Preprocess and normalize images
- Apply data augmentation
- Train and evaluate the model
- Support sustainable waste management

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pillow
- Jupyter Notebook

## 📁 Project Structure

```text
CNN_Waste_Segregation/
│
├── CNN_Assg_Waste_Segregation_AshwiniAgalave.ipynb
├── README.md
├── requirements.txt
├── Dataset/
├── Images/
└── Outputs/
```

## 🔄 Workflow

Dataset → Preprocessing → Resizing → Normalization → Train/Test Split →
Data Augmentation → CNN Training → Evaluation → Prediction

## 🧠 CNN Architecture

Input (128×128×3)
→ Conv2D(32)
→ MaxPooling
→ Conv2D(64)
→ MaxPooling
→ Conv2D(128)
→ MaxPooling
→ Flatten
→ Dense(128)
→ Dropout(0.5)
→ Softmax(7 Classes)

## 📊 Features

- Image preprocessing
- Data augmentation
- Multi-class classification
- Accuracy & loss visualization
- Confusion matrix evaluation

## 🌱 Applications

- Smart recycling
- Waste sorting
- Environmental monitoring
- Smart city solutions

## 👩‍💻 Author

Ashwini Agalave

## 📄 License

Educational and academic use.
