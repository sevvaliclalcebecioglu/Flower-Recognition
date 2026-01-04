# 🌸 Flower Recognition Project

This project focuses on building a **flower classification model** using Python and deep learning. The goal is to automatically classify images of flowers into **5 classes**: `daisy`, `dandelion`, `rose`, `sunflower`, and `tulip`.

---

## 🛠 Technologies Used
- Python 3.x
- TensorFlow / Keras
- OpenCV / PIL
- Streamlit (for web interface)

---

## 💡 Project Description
- The dataset contains images of 5 types of flowers.
- We first implemented a **CNN model from scratch**, but validation accuracy was moderate due to limited data.
- Then, we used **Transfer Learning with VGG16**, freezing its convolutional base and adding custom dense layers.
- This approach significantly improved the model's generalization, achieving **high accuracy on both training and validation sets**.

---

## ⚡ Features
- Classify uploaded flower images into 5 categories.
- Simple **Streamlit web interface** for image upload and prediction.
- Easily extendable to more flower classes or different pretrained models.

---

## 📈 Results
- Training accuracy: ~99%
- Validation accuracy: ~60-80% depending on model
- Transfer Learning improved generalization over a basic CNN.