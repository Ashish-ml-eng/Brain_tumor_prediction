# 🧠 Multi-Class Brain Tumor Prediction using CNN + Django

> A Deep Learning–based Brain Tumor Classification System with real-time MRI prediction, deployed via a Django web application.

---

## 📌 Project Overview

This project is a **Multi-Class Brain Tumor Classification System** that predicts the type of brain tumor from MRI images using a custom-built Convolutional Neural Network (CNN).

The model classifies brain MRI scans into four categories:

| Label | Class |
|---|---|
| 🧬 | Glioma Tumor |
| 🧬 | Meningioma Tumor |
| 🧬 | Pituitary Tumor |
| 🧠 | No Tumor |

Beyond model development, a **Django-based web application** was built where users can upload an MRI image and receive a real-time prediction — making this a complete end-to-end AI solution.

---

## 🚀 Model Performance

| Metric | Value |
|---|---|
| 🏆 Best Validation Accuracy | **97.42%** |
| ✅ Test Accuracy | **96.81%** |
| 📉 Test Loss | **0.0954** |
| 📈 Peak Training Accuracy | **99.27%** |

The model shows strong generalization with consistently high validation and test performance.

---

## 🧠 Model Architecture

Custom-built Convolutional Neural Network (CNN):

- Convolutional Layers
- ReLU Activation
- MaxPooling Layers
- Dropout (Overfitting Control)
- Fully Connected Dense Layers
- Softmax Output Layer (4 Classes)

**Training Configuration:**

| Setting | Value |
|---|---|
| Loss Function | Categorical Crossentropy |
| Optimizer | Adam |
| Evaluation Metric | Accuracy |

---

## 💻 Django Web Application

The trained CNN model was integrated into a Django web application for real-time inference.

### ✨ Features

- MRI image upload interface
- Image preprocessing (resize + normalization)
- Real-time tumor class prediction
- Clean and user-friendly UI

### 🔄 Application Workflow

```
User uploads MRI image
        ↓
Django backend loads trained model
        ↓
Image is preprocessed
        ↓
Model predicts tumor class
        ↓
Result displayed instantly on webpage
```

---

## 📁 Project Structure

```
Brain-Tumor-Prediction/
│
├── model_training.ipynb       # CNN training pipeline
├── web_page/
│   ├── templates/             # HTML templates
│   ├── static/                # CSS / JS assets
│   ├── views.py               # Prediction logic
│   └── urls.py                # URL routing
│
└── README.md
```

---

## 🎯 Key Skills Demonstrated

- Multi-class image classification
- Custom CNN architecture design
- Overfitting control using Dropout
- Dataset handling with TensorFlow/Keras
- Model evaluation on held-out test data
- ML model integration with Django
- Building deployable AI-powered web applications

---

## 👨‍💻 Author

**Ashish Rajput**
Focused on Machine Learning, Deep Learning & AI Applications

🔗 GitHub: [A7-ha4](https://github.com/A7-ha4)
