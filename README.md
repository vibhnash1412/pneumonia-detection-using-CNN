# Pneumonia detection using CNN
This project demonstrates how a Convolutional Neural Network (CNN) can be used to detect Pneumonia from chest X-ray images. Implemented in Python using TensorFlow/Keras, the model classifies X-rays into Normal or Pneumonia, providing an AI-based assistive tool for medical imaging.

# Dataset

Dataset used: Chest X-Ray Images (Pneumonia) – Kaggle

The dataset contains chest X-ray images categorized into:

|-Train (Normal / Pneumonia)

|-Validation (Normal / Pneumonia)

|-Test (Normal / Pneumonia)

# Project Workflow

1. Data Preprocessing:
   
  -Dataset downloaded from Kaggle and unzip it
  
  -Image resizing, normalization, and greyscale conversion
  
  -Train/Validation/Test split loading

3. Model Architecture:
  -Custom CNN layers with Conv2D, MaxPooling, Dropout, and Dense layers
  -Binary classification output with ReLU activation

4. Training and Evaluation:
  -Training with accuracy and loss tracking
  -Validation and testing for performance assessment

5. Result:
  -The model achieved high accuracy on validation/test data
  -Demonstrated reliable classification between Normal and Pneumonia X-rays

# Prerequisites
1. Python 3.8+
2. TensorFlow / Keras
3. NumPy, Matplotlib, Seaborn, scikit-learn

# Future Improvements

1. Experiment with transfer learning (VGG16, ResNet, EfficientNet).
2. Deploy model in a web app (Flask/Streamlit).
