# 🌸 ResNet50 Flower Classifier with Transfer Learning

A powerful image classification model built using **Transfer Learning with ResNet50**, trained on a 14-class **flower dataset**. This project leverages TensorFlow, Keras, and real-time performance visualization for production-ready flower recognition.

## 🚀 Features

- ✅ Uses **ResNet50** pretrained on ImageNet
- ✅ Supports **transfer learning** and fine-tuning
- ✅ Works with **custom datasets** (flowers in this case)
- ✅ Includes **real-time training plots**
- ✅ Predicts image classes with **confidence scores**
- ✅ Designed for **easy deployment or integration**

---

## 🧠 Model Architecture

- Base Model: `ResNet50 (include_top=False)`
- Custom Head:
  - `GlobalAveragePooling2D`
  - `Dense(128, activation='relu')`
  - `Dropout(0.5)`
  - `Dense(14, activation='softmax')`

---

## 📦 Dataset

- **Source:** 14-class flower dataset
