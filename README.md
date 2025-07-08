# ♻️ E-Waste Classification Model

This project implements an image classification model for identifying various categories of electronic waste using deep learning. Built using **EfficientNetV2B3**, the model demonstrates high accuracy in detecting and classifying e-waste types. It serves as a step toward automating and optimizing e-waste management through AI.

## 🚀 Demo

👉 **Try the live model here**:  
[![Gradio App](https://img.shields.io/badge/Gradio-Live%20Demo-00b2ff?style=for-the-badge&logo=gradio)](https://huggingface.co/spaces/Prateek-Batham/AICTE_E_waste_classification)  
**Hosted on Hugging Face Spaces with Gradio UI**

---

## 📊 Model Performance

- **Architecture**: EfficientNetV2B3 (upgraded from V2B0)
- **Test Accuracy**: 98.00%
- **Test Loss**: 0.0754
- **Epochs**: 15
- **Dataset**: Labeled e-waste images split into training, validation, and test sets

---

## 🧠 Features

- Image classification of different types of electronic waste
- Real-time predictions via Gradio interface
- Transfer learning with EfficientNetV2 for robust performance
- Clean, modular, and scalable code

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- EfficientNetV2 (via `keras.applications`)
- Gradio for model deployment
- Hugging Face Spaces for hosting
