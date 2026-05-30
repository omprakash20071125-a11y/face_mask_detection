# 😷 Face Mask Detection

A deep learning project that detects whether a person 
is wearing a face mask or not.

## 🔍 What it does
- Trains MobileNetV2 using Transfer Learning
- Classifies images as mask or no mask
- Detects multiple faces in an image using OpenCV
- Draws green box for mask and red box for no mask

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- MobileNetV2 (Transfer Learning)
- OpenCV (Haar Cascade)
- Google Colab

## 🚀 How to Run
1. Open the .ipynb file in Google Colab
2. Mount your Google Drive
3. Place your dataset in Google Drive like this:
   - data/with_mask/
   - data/without_mask/
4. Run all cells from top to bottom

## 📊 Model
- Used MobileNetV2 pretrained on ImageNet
- Added a Dense layer with Sigmoid for binary classification
- Trained with EarlyStopping to avoid overfitting

## 🤝 Acknowledgements
- Dataset from https://www.kaggle.com/datasets/omkargurav/face-mask-dataset
- OpenCV implementation with help from AI assistance

## view the Notebook
[![View Notebook](https://img.shields.io/badge/Rendered%20with-NBViewer-orange?style=for-the-badge&logo=jupyter)](https://nbviewer.org/github/omprakash20071125-a11y/face_mask_detection/blob/main/face_with_or_without_mask-2.ipynb)
