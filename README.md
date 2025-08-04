# Human Mood Recognition using Deep Learning

This project aims to recognize human moods — such as **Happy**, **Neutral**, and **Angry** — from facial images using **pretrained Convolutional Neural Networks (CNNs)** like **ResNet50**, **VGG16**, **VGG19**, and **EfficientNetB4**.

The system is built and tested in **Google Colab**, with support for real-time mood detection on custom input images.

---

## 🔍 Overview

Human mood recognition is a crucial component of many AI-powered systems in:
- Mental health monitoring
- Customer emotion analysis
- Smart assistants
- Surveillance & human-computer interaction

This project applies **Transfer Learning** to fine-tune powerful CNNs on a labeled mood dataset. It also includes evaluation and real-time inference on test images.

---

## ✅ Features

- Uses transfer learning with:
  - ResNet50
  - VGG16
  - VGG19
  - EfficientNetB4
- Image augmentation using `ImageDataGenerator`
- Callbacks:
  - EarlyStopping
  - ModelCheckpoint
  - ReduceLROnPlateau
- Comparison of multiple models based on accuracy
- **Real-time mood recognition** using custom/test images

---

## 📁 Folder Structure (Google Drive Integration)

