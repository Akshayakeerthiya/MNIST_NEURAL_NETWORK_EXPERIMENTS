# MNIST NEURAL NETWORK EXPERIMENTS

## Overview

* Hands-on experiments using the **MNIST handwritten digit dataset**.
* Focused on understanding the fundamentals of **Neural Networks and Deep Learning**.
* Explored how different architectures and training parameters affect model performance.

## Dataset

* **Dataset:** MNIST
* **Total Images:** 70,000
* **Training Images:** 60,000
* **Testing Images:** 10,000
* **Classes:** 10 (Digits 0–9)
* **Image Size:** 28 × 28 pixels
* **Input Features:** 784 pixels

## Objectives

- Understand **Neural Network architecture**.
- Understand **Dense layers, weights, biases, and trainable parameters**.
- Understand different **activation functions**.
- Understand the impact of **batch size, epochs, and optimization** on training.
- Analyze **model performance and identify overfitting**.

## Data Preprocessing

* Normalize pixel values from **0–255 to 0–1**.
* Reshape images from **28 × 28 to 784 features**.
* Prepare labels for **10-class classification**.

### Reshaping

```text
(60,000, 28, 28) → (60,000, 784)
```

## Technologies Used

* **Python**
* **TensorFlow**
* **Keras**
* **NumPy**
* **Pandas**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**

## Key Learnings

* **Neural Network Architecture**

  * Understood the structure of input layers, hidden layers, neurons, and output layers.

* **Dense Layers & Parameters**

  * Learned how Dense layers work.
  * Understood weights, biases, and trainable parameters.

* **Data Preparation**

  * Learned how image data is reshaped and normalized before training.

* **Activation Functions**

  * Understood the role of **Sigmoid, Tanh, and ReLU** in neural network learning.

* **Training & Optimization**

  * Learned how **epochs, batch size, and Gradient Descent** affect training.

* **Model Evaluation**

  * Learned to compare training and validation performance and identify overfitting.

## Key Observations

* Increasing the number of **epochs beyond an optimal point can lead to overfitting**.

* Increasing the **hidden layers alone does not guarantee higher accuracy**; the architecture needs to be properly designed and tuned.

* Using a **full batch size can result in lower model performance** compared with an appropriate mini-batch size.

* The choice of **activation function can significantly influence model performance** and learning behaviour.

* Model performance depends on a **combination of architecture and training parameters**, not on a single factor.


