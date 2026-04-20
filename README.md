# Smile Predictor – AI-Based Smile Detection App

A machine learning-based web application that detects whether a person is smiling in an image. The system classifies input images into two categories: Smiling or Not Smiling. It provides instant predictions through an interactive web interface built with Streamlit.

This project demonstrates practical use of computer vision, image preprocessing, and binary classification using a trained machine learning model.

---

## Features

- Upload an image and get instant smile detection
- Automatic face detection using OpenCV
- Machine learning-based binary classification
- Displays prediction confidence score
- Simple and responsive web interface
- Dark-themed UI for better user experience

---

## How It Works

1. The user uploads an image through the web interface  
2. OpenCV detects a face in the image  
3. The detected face is cropped and preprocessed  
4. The image is converted to grayscale, resized, and flattened  
5. A trained machine learning model predicts whether the person is smiling  
6. The result and confidence score are displayed on the screen  

---
## Requirements

| Technology | Purpose |
|------------|--------|
| Python | Core programming language |
| Streamlit | Web application framework |
| OpenCV | Face detection and image processing |
| NumPy | Numerical computations |
| scikit-learn | Model training and prediction |
| Joblib | Model serialization |
| Pillow | Image handling |

## Project Structure
Smile-Predictor/
│
├── app.py # Streamlit application

├── smile_stalker.pkl # Trained machine learning model

├── scaler.pkl # Feature scaler

├── requirements.txt # Project dependencies

└── README.md # Documentation
