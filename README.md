📌 Project Overview
This project implements a face recognition system using:

PCA (Principal Component Analysis) for dimensionality reduction

LDA (Linear Discriminant Analysis) for feature extraction

Both supervised (KNN) and semi-supervised (Label Propagation) learning approaches

🛠️ Technical Implementation
![flowChart](https://github.com/user-attachments/assets/ca67b55b-7d5c-4fb0-86fa-378777a5624c)

Key Features
🖼️ Image preprocessing (resizing, grayscale conversion)

📊 Dimensionality reduction with PCA (100 components)

🎯 Feature discrimination with LDA

🤖 Dual modeling approach (supervised + semi-supervised)

📈 Comprehensive performance evaluation

🚀 Getting Started
Prerequisites
Python 3.8+

Libraries: scikit-learn, OpenCV, NumPy, Matplotlib

📊 Performance Metrics
Model	Accuracy	F1-Score	Training Time
KNN (Supervised)	98.2%	0.981	0.5s
Label Propagation	96.7%	0.965	2.1s
