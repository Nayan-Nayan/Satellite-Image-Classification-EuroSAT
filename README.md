# 🛰️ Satellite Image Classification using CNN

This project focuses on classifying satellite images into different land-use categories using a Convolutional Neural Network (CNN).

## 📌 Problem Statement
Given a satellite image, classify the dominant land-use type such as forest, water, residential, or industrial area.

## 🛰️ Dataset
- **EuroSAT Dataset**
- Real Sentinel-2 satellite images provided by the European Space Agency (ESA)
- 10 land-use classes

## 🧠 Approach
- Preprocessed images by resizing and normalization
- Split data into training and validation sets
- Built a CNN using TensorFlow/Keras
- Trained the model using the Adam optimizer
- Evaluated performance on unseen validation data

## 📊 Results
- Achieved ~70% accuracy on validation data
- Model generalized well without overfitting

## 🛠️ Tech Stack
- Python
- TensorFlow / Keras
- TensorFlow Datasets (TFDS)
- Google Colab

## 🚀 Future Improvements
- Apply transfer learning (ResNet / MobileNet)
- Add data augmentation
- Extend to land-use segmentation

## 📎 Notes
This project was built as part of learning AI/ML and computer vision concepts with a focus on aerospace and satellite imagery.
