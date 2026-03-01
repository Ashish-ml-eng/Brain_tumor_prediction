🧠 Multi-Class Brain Tumor Prediction using CNN + Django
📌 Project Overview

This project is a Deep Learning–based Multi-Class Brain Tumor Classification System that predicts the type of brain tumor from MRI images.

The model classifies brain MRI scans into four categories:

🧬 Glioma Tumor

🧬 Meningioma Tumor

🧬 Pituitary Tumor

🧠 No Tumor

In addition to model development, I built a Django-based web application where users can upload an MRI image and receive a real-time prediction.

This project demonstrates both Deep Learning expertise and full-stack ML deployment skills.

🚀 Model Performance
📊 Evaluation Metrics
Metric	Value
🏆 Best Validation Accuracy	97.42%
✅ Test Accuracy	96.81%
📉 Test Loss	0.0954
📈 Peak Training Accuracy	99.27%

The model shows strong generalization with consistently high validation and test performance.

🧠 Model Architecture

Custom-built Convolutional Neural Network (CNN):

Convolutional Layers

ReLU Activation

MaxPooling Layers

Dropout (Overfitting Control)

Fully Connected Dense Layers

Softmax Output Layer (4 Classes)

Training Configuration

Loss Function: Categorical Crossentropy

Optimizer: Adam

Evaluation Metric: Accuracy

💻 Django Web Application

The trained CNN model was integrated into a Django web application.

✨ Features

Image upload interface

MRI image preprocessing (resize + normalization)

Real-time prediction

Displays predicted tumor class

Clean and user-friendly UI

🔄 Application Workflow

User uploads MRI image

Django backend loads trained model

Image is preprocessed

Model predicts tumor class

Result is displayed instantly on the webpage

This transforms the project into a complete end-to-end AI solution, not just a training notebook.

📁 Project Structure
Brain-Tumor-Prediction/
│
├── model_training.ipynb
├── web_page/
│   ├── templates/
│   ├── static/
│   ├── views.py
│   └── urls.py
│
└── README.md
🎯 Key Skills Demonstrated

Multi-class image classification

CNN architecture design

Overfitting control using Dropout

Dataset handling with TensorFlow

Model evaluation on test data

ML model integration with Django

Building deployable AI-powered web applications

👨‍💻 Author

Ashish Rajput
B.Tech CSE (AI & ML) – 2nd Year
Focused on Machine Learning, Deep Learning & AI Applications

🔗 GitHub: https://github.com/A7-ha4
