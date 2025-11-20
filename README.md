# MNIST Handwritten Digit Classification 🔢

This project implements a Deep Learning model to recognize and classify images of handwritten digits (0-9) using the famous MNIST dataset.

## 🧠 Project Overview
**Context:** Completed as part of the Stellenbosch University / HyperionDev Data Science Bootcamp.
**Goal:** To build and train a Neural Network capable of correctly identifying digits from 28x28 pixel grayscale images.

## 🛠️ Tech Stack
* **Python 3** (Jupyter Notebook)
* **TensorFlow / Keras:** For building and training the Neural Network architecture.
* **Matplotlib & Seaborn:** For visualizing image data and model performance metrics (confusion matrices).

## 🔎 Key Analysis Steps
1.  **Data Preprocessing:**
    * Normalized pixel values to a 0-1 range to improve training convergence.
    * Reshaped input data to fit the model requirements (28x28x1).
    * One-hot encoded target labels (if applicable).
2.  **Model Architecture:**
    * Constructed a **Convolutional Neural Network (CNN)** (or Dense Network) designed for image feature extraction.
    * Utilized layers such as `Conv2D`, `MaxPooling2D`, and `Dense`.
3.  **Training & Evaluation:**
    * Trained the model over multiple epochs, monitoring Loss and Accuracy.
    * Evaluated performance on unseen test data to prevent overfitting.

## 📈 Results
* The model achieved high accuracy on the test set, demonstrating the effectiveness of CNNs for image classification tasks.
* [Optional: Add specific accuracy score here if known, e.g., "Achieved 98.5% test accuracy"].

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
