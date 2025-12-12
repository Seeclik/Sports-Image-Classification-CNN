# Sports-Image-Classification-CNN
A Deep Learning model using Convolutional Neural Networks (CNN) to classify images into 4 sports (Basketball, Swimming, Cricket, Table Tennis) with 86% accuracy using TensorFlow &amp; Keras.

# CNN for Sports Prediction 🏀🏏🏓🏊

## 📄 Project Overview
This project leverages Artificial Neural Networks (ANN)، specifically Convolutional Neural Networks (CNN)، to predict the type of sport depicted in an image. By analyzing visual features، the model classifies images into their respective sports categories with the aim of achieving high accuracy.

---

## 🎯 Goals & Objectives
* Develop a neural network model to accurately predict sport types from images.
* Create a system capability for real-time image classification and prediction.
* Implement and train CNN models from scratch using Keras and TensorFlow.
* Leverage pre-trained models for efficient image classification.

---

## 📂 Dataset
The dataset used for this project was obtained from Roboflow Universe.

* **Dataset Link:** [Sports Classification Dataset](https://universe.roboflow.com/projects-lb1jy/sports-classification-bxxqq)

* **Original Size:** The project started with **722 original images** sourced from Roboflow.
* **Final Size:** The dataset was augmented to **3,648 images** to ensure robust training and improve model generalization.

### Dataset Distribution
The final dataset of 3,648 images was divided into three subsets:
* **Training:** ~80% (3,366 images)
* **Validation:** ~10% (140 images)
* **Testing:** ~10% (142 images)

### Target Classes
The model is designed to classify images into the following sports:
1.  Basketball
2.  Swimming
3.  Cricket
4.  Table Tennis

---

## ⚙️ Methodology

* **Task Type:** Multiclass classification, Single label.

### Image Preprocessing & Augmentation
To enhance the model's ability to generalize, the dataset underwent extensive preprocessing and augmentation:
* **Preprocessing:** Auto-Orient applied, Resize to Stretch to 224x224.
* **Augmentation (Data Duplication):** Outputs per training example were set to **3**.
* **Augmentation Techniques Used:**
    * Flip: Horizontal.
    * Rotate: 90° Clockwise, Counter-Clockwise.
    * Rotation: Between -15° and +15°.
    * Saturation: Between -33% and +33%.
    * Brightness: Between -24% and +24%.
    * Exposure: Between -10% and +10%.
    * Blur: Up to 1px; Noise: Up to 0.26% of pixels.

### Core Techniques:
* Convolutional Neural Networks (CNN).
* Regularization Techniques & Optimizers.
* Transfer Learning (Pre-trained models).

---

## 📊 Results & Evaluation
The model was evaluated based on accuracy and loss metrics:
* **Accuracy:** 86%
* **Loss:** 59%

---

## 🛠️ Tools & Technologies
* **Deep Learning Frameworks:** Keras and TensorFlow.
* **Model Type:** CNN (Convolutional Neural Network).

---
*Created by **Khalid Alammari** - Connect with me on [linkedin.com/in/khalid-alammari-] or Email [Khalid.A.Alammari@gmail.com]*
