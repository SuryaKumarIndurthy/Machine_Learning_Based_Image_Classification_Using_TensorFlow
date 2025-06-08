# Machine Learning-Based Image Classification Using TensorFlow

This project demonstrates how to build and train a simple image classification model using TensorFlow to classify clothing items from the Fashion MNIST dataset. The model learns to recognize 10 different categories, such as shirts, sneakers, and coats, based on grayscale image data.

---

## 📊 Project Overview

- Dataset: Fashion MNIST (60,000 training and 10,000 test images)
- Model: Fully connected neural network using Keras Sequential API
- Accuracy: ~90.97% on training data and ~88.55% on test data
- Visualization: Shows prediction results with color-coded feedback (green for correct, red for incorrect)

---

## 🧠 Model Architecture

- `Flatten`: Converts 28x28 image to 784-length vector
- `Dense(128, activation='relu')`: Fully connected hidden layer
- `Dense(10)`: Output layer with logits for 10 classes
- Loss Function: `SparseCategoricalCrossentropy(from_logits=True)`
- Optimizer: `Adam`
