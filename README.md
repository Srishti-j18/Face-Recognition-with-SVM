# Face Recognition with HOG + SVM

This repository implements a **face recognition system** using **HOG (Histogram of Oriented Gradients)** for feature extraction, **PCA (Principal Component Analysis)** for dimensionality reduction, and **SVM (Support Vector Machine)** for classification, inspired by Skillcate AI tutorials.

## ✨ Features
- **HOG feature extraction** for robust face descriptors
- **SVM classifier** for face/non-face binary classification or multi-class recognition  
- **Real-time detection** via webcam or image processing
- Trained on Indian celebrity faces (Aamir Khan, Jaya Bachchan, etc.)

## 📦 Requirements
```bash
pip install opencv-python scikit-learn numpy matplotlib imutils
```

## 🚀 Quick Start
```bash
git clone https://github.com/Srishti-j18/Face-Recognition-with-SVM.git

cd Face-Recognition-with-SVM
```

## 📊 Dataset
- **Positive samples**: Face images (frontal/profile)

- **Negative samples**: Random background images

- **Recommended**: 500+ samples per class for good accuracy

## 🔗 Reference
This project takes reference from SkillcateAI's HOG+SVM face recognition tutorial.
