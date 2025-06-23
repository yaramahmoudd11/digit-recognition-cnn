# Handwritten Digit Recognition using CNN

## 🎯 Objective
Build a convolutional neural network (CNN) to recognize handwritten digits (0–9) from grayscale images using the MNIST dataset.

## 📦 Dataset
- Source: keras.datasets.mnist
- 60,000 training images and 10,000 testing images
- Image size: 28x28 pixels, grayscale

## 🧠 Model Architecture
- 2x Conv2D layers with ReLU activation
- 2x MaxPooling2D layers
- Flatten → Dense(128) → Dropout(0.3) → Dense(10 softmax)

## 📊 Performance
- Accuracy: ~98% on test data
- Trained over 5 epochs
- Visualized predictions and confirmed model generalization

## 🚀 Tools
- Python, TensorFlow, Keras
- Matplotlib for visualization

## 👩‍💻 Author
Yara Mahmoud — ML Intern @ CodeAlpha
