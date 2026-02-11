# 🧠 Building a Brain – Fashion MNIST Image Classifier

This project demonstrates how a simple Artificial Neural Network can classify clothing images using the Fashion MNIST dataset.

The model is built using TensorFlow and Keras and mimics the basic working of a biological neuron through weighted inputs and bias terms.

## 📌 Project Overview

- Dataset: Fashion MNIST (28x28 grayscale images)
- Input Size: 784 pixels (Flattened)
- Output Classes: 10 clothing categories
- Model Type: Fully Connected Neural Network
- Framework: TensorFlow / Keras

## 🏗 Model Architecture

1. **Flatten Layer**
   - Converts 28x28 image into a 784-dimensional vector.

2. **Dense Layer (10 neurons)**
   - Each neuron represents one clothing category.
   - Uses weighted sum + bias to produce class scores.

## 🎯 Training Details

- Loss Function: Sparse Categorical Crossentropy
- Optimizer: Adam
- Evaluation Metric: Accuracy
- EarlyStopping used to prevent overfitting

## 📊 Key Learnings

- Understanding weights and bias in neural networks
- Multi-class classification using softmax
- Overfitting and validation monitoring
- Model parameter calculation (7850 total parameters)
- Importance of epochs and early stopping

## 🚀 Results

The model achieves strong validation accuracy on unseen test data, demonstrating how even a simple neural network can effectively classify images.

---

🔗 Inspired by NVIDIA Deep Learning Institute (DLI) – "Building a Brain in 10 Minutes"
