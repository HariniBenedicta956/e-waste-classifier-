# E-Waste Image Classification using EfficientNetV2B0

This project uses deep learning and transfer learning to classify e-waste images into 10 categories using the EfficientNetV2B0 model.

## 🔍 Problem Statement
Manual sorting of electronic waste is error-prone and labor-intensive. This model helps automate classification using AI.

## 💻 Tech Stack
- TensorFlow
- EfficientNetV2B0
- Python
- Tkinter (GUI)
- Matplotlib (Charts)

## 📦 Dataset
- Source: [E-Waste Image Dataset - Kaggle](https://www.kaggle.com/datasets/akshat103/e-waste-image-dataset)
- 10 Classes: PCB, Battery, Microwave, Mobile, Mouse, Printer, Television, Washing Machine, Keyboard, Player

## 🧠 Model
- Base Model: EfficientNetV2B0 (pretrained on ImageNet)
- Loss: Sparse Categorical Crossentropy
- Optimizer: Adam
- Metrics: Accuracy

## 📊 Output
- Accuracy/Loss visualization
- Confusion Matrix
- GUI for real-time classification

## 📁 How to Run
1. Clone the repository
2. Install requirements using `pip install -r requirements.txt`
3. Run `main.py`

## 📌 Note
This project was developed as part of a 4-week AICTE internship and built to stand out in a competitive submission.
