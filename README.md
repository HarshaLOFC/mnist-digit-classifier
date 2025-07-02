# 🧠 MNIST Digit Classifier using CNN

This is a simple deep learning project that uses a **Convolutional Neural Network (CNN)** to classify handwritten digits from the **MNIST dataset**. Built using **TensorFlow** and **Keras**, the model achieves ~99% accuracy on the test data.

---

## 📂 Project Overview

- 📄 **Dataset**: MNIST (70,000 images of handwritten digits)
- 🧠 **Model**: CNN with 3 convolutional layers + dense layers
- 📊 **Accuracy**: ~99% on test set
- 🧰 **Libraries**: TensorFlow, NumPy, Matplotlib

---

## 🏗️ Model Architecture

- Conv2D (32 filters, 3x3) + MaxPooling
- Conv2D (64 filters, 3x3) + MaxPooling
- Conv2D (64 filters, 3x3)
- Flatten → Dense (64) → Dense (10, Softmax)

---

## 🚀 How to Run

1. **Install dependencies**:
   
pip install tensorflow matplotlib numpy

2. Run the script :

   python image_classifier.py
