---

## 📊 Dataset
- HAM10000 (~10K images, 7 classes)  
- Dataset not included due to size  

**Links:**  
- Kaggle: https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000  
- Google Drive: <YOUR_DRIVE_LINK>  

---

## 🧠 Model & Approach
- MobileNetV2 with transfer learning  
- Data augmentation: rotation, flipping, zoom, brightness/contrast  
- Softmax classifier for 7 classes  

---

## 📈 Results
- Overall Accuracy: 96.24%  
- Metrics: `results/classification_report.txt`  
- Optional visuals: `results/confusion_matrix.png`, `results/training_curve.png`

---

## 💻 How to Run
1. Open `notebooks/skin_cancer_classification.ipynb` in Colab  
2. Mount Google Drive and provide dataset path  
3. Run all cells  

---

## ✅ Authorship
Independently designed and implemented as part of a **B.Tech capstone project**.

---

## 📚 Acknowledgements
- HAM10000 dataset by **ISIC / Kaggle**  
- Pretrained weights by **PyTorch**




# Skin Cancer Classification using Deep Learning

A deep learning-based multiclass skin cancer classification project
using transfer learning and data augmentation.

Accuracy achieved: 96.24%

# Deep Learning-Based Skin Cancer Classification using MobileNetV2

## Overview
This project implements a deep learning framework for multiclass
skin cancer classification using MobileNetV2 with transfer learning
and data augmentation on the HAM10000 dataset.

## Dataset
- HAM10000 dermoscopic image dataset
- ~10,000 images
- 7 skin lesion classes
- Dataset not included due to size constraints

## Model
- Architecture: MobileNetV2
- Transfer Learning (ImageNet weights)
- Data Augmentation
- Softmax classifier (7 classes)

## Results
- Accuracy: ~96%
- Strong generalization with minimal overfitting
- Lightweight model suitable for mobile and real-time deployment

## How to Run
1. Open the notebook in Google Colab
2. Mount Google Drive
3. Update dataset path
4. Run all cells

## Tech Stack
- Python
- TensorFlow / Keras
- Google Colab






