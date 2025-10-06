🧠 Handwritten Digit Recognition using CNN (MNIST Dataset)
This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify handwritten digits (0–9) from the MNIST dataset.

🚀 Features
Loads and preprocesses the MNIST dataset (normalization + reshaping)
Builds a 3-layer CNN architecture for image classification
Trains the model with Adam optimizer and categorical cross-entropy loss
Evaluates model performance and visualizes sample predictions
Achieves over 98% accuracy on test data

🧩 Model Architecture
Conv2D (32 filters, 3×3, ReLU) + MaxPooling (2×2)
Conv2D (64 filters, 3×3, ReLU) + MaxPooling (2×2)
Conv2D (64 filters, 3×3, ReLU)
Flatten → Dense(64, ReLU) → Dense(10, Softmax)

📊 Results
Training Epochs: 5
Batch Size: 64
Test Accuracy: ~98%

🖼️ Output Example
Displays a test image with its predicted label and actual label.

🧰 Tech Stack
Python
TensorFlow / Keras
NumPy
Matplotlib
