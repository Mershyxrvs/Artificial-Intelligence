# Artificial Intelligence 🤖🧠

A collection of AI and deep learning projects covering **CNN image classification**, **transfer learning**, and **neural networks**.

## Projects

### 1. CIFAR-100 Image Classification (`CIFAR100.ipynb`)

Convolutional Neural Network (CNN) for classifying images across 100 categories.

- **Architecture:** Conv2D → MaxPooling → Flatten → Dense → Softmax(100)
- **Dataset:** CIFAR-100 (32×32 color images, 100 classes)
- **Features:** EarlyStopping + ModelCheckpoint callbacks, training history visualization
- **Framework:** TensorFlow / Keras

### 2. EfficientNetB0 Image Classifier (`EfficientNetB0_Image_Classifier.ipynb`)

Transfer learning with EfficientNetB0 pre-trained on ImageNet for real-world image classification.

- **Model:** EfficientNetB0 (ImageNet weights)
- **Pipeline:** Download image from URL → Preprocess → Predict → Top-5 results
- **Output:** Bar chart of top predictions with confidence scores

### 3. MNIST Digit Recognition (`MNIST_using_ANN.ipynb`)

Simple Artificial Neural Network (ANN) for handwritten digit recognition.

- **Architecture:** Flatten → Dense(128, ReLU) → Dense(10, Softmax)
- **Dataset:** MNIST (28×28 grayscale digits 0–9)
- **Training:** 50 epochs, Adam optimizer
- **Framework:** TensorFlow / Keras

### 4. Image Download & Preprocessing (`Image_Download_+_Preprocessing_+_Visualization.ipynb`)

Utility notebook for downloading images from URLs and preparing them for ML pipelines.

- **Tools:** Requests, PIL, Matplotlib
- **Operations:** Download, convert to RGB, display, save locally

## Tech Stack

- Python 3
- TensorFlow / Keras — Deep learning framework
- EfficientNetB0 — Transfer learning model
- NumPy, Matplotlib, PIL — Data handling & visualization
- Jupyter Notebook

## Quick Start

```bash
pip install -r requirements.txt
jupyter notebook CIFAR100.ipynb
```
