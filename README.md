# Human Mood Recognition using Deep Learning

This project focuses on **recognizing human mood or emotion (Happy, Neutral, Angry)** from facial images using **state-of-the-art deep learning models** and **transfer learning**. Built and evaluated entirely in **Google Colab**, the project supports both training and **real-time mood prediction on custom input images**.


## 📍 Problem Statement

Understanding human emotions through facial expressions can empower AI systems to be more intuitive and human-aware. This project aims to classify facial images into **three mood categories**:
- 😄 Happy  
- 😐 Neutral  
- 😠 Angry

Such systems have applications in:
- Mental health support tools
- Smart assistants & customer service bots
- Surveillance and monitoring
- Classroom engagement systems

---

## 🎯 Project Objectives

- Utilize **transfer learning** to train high-performing models with limited data
- Train and compare multiple pretrained CNN architectures
- Apply data augmentation to improve generalization
- Use callbacks to optimize training performance
- Implement **real-time mood recognition** on user-uploaded images
- Evaluate models based on accuracy and confusion matrix

---

## 🧠 Models Used

We experimented with and evaluated the following pretrained models from TensorFlow’s Keras applications:
- ✅ **ResNet50**
- ✅ **VGG16**
- ✅ **VGG19**
- ✅ **EfficientNetB4**

These models were used with:
- Frozen convolutional base layers
- Custom dense classifier layers
- Softmax output for 3-class mood classification


