# Hand Gesture Recognition using CNN & Mediapipe

## Overview
This project implements a **Hand Gesture Recognition System** using **Convolutional Neural Networks (CNN)** and **Mediapipe** for feature extraction. The system classifies hand gestures from images and enables real-time gesture recognition.

## Dataset
The dataset consists of various hand gesture images categorized into different classes (e.g., **Thumbs Up, Index Finger, OK Sign**, etc.).

Ensure that the dataset is available in a **zipped format** at `/content/dataset.zip` in **Google Colab**.

## Features
✅ Extracts dataset and processes images using **OpenCV & Mediapipe**  
✅ Trains a **CNN Model** for gesture classification  
✅ Supports **real-time gesture recognition** using a webcam  
✅ Displays **predicted gestures** with image visualization  
✅ Handles errors gracefully for missing or incorrect image paths  

## Model Architecture
The **CNN model** consists of:
- **2 Convolutional Layers** with ReLU activation
- **MaxPooling Layers** for feature reduction
- **Flatten & Fully Connected Layers** for classification
- **Softmax Activation** for multi-class prediction
## Dependencies
- Python 3.x
- TensorFlow/Keras
- OpenCV
- Mediapipe
- NumPy & Pandas
- Matplotlib


