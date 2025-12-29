# Convolutional Neural Network from Scratch

This repository contains a **Convolutional Neural Network (CNN) implemented completely from scratch**, without using any deep learning frameworks such as PyTorch or TensorFlow.

The goal of this project is **deep understanding**, not performance or accuracy.

Only **NumPy** and **SciPy** are used for numerical operations and convolution utilities.

---

## 🚀 Project Motivation

Modern deep learning frameworks abstract away most of the internal mechanics of neural networks.
While they are powerful, they often hide *why* things work.

This project was built to:

* Understand **CNN internals at a low level**
* Implement **forward and backward propagation manually**
* Learn how **kernels, gradients, and loss flow** through the network
* Remove all “black boxes”

---

## 🧠 What’s Implemented

### Core Components

* Custom base `Layer` class
* **Convolutional Layer**

  * Manual kernel initialization
  * Forward pass using convolution
  * Backward pass with gradient computation
* **Activation Functions**

  * ReLU (with backward propagation)
* **Reshape Layer**

  * Converts convolution output into vector form
* **Fully Connected (Dense) Layer**
* **Loss Function**

  * Mean Squared Error (MSE)
* Manual **training loop** (no optimizers)

---

## 📊 Dataset

* **Fashion-MNIST**
* Trained on **2 selected classes only**
* Reason:

  * No GPU
  * No optimizers
  * Training kept intentionally lightweight

This allows focus on **correctness and understanding**, not speed.

---

## ⚙️ Tech Stack

* Python
* NumPy
* SciPy
* Jupyter Notebook

No deep learning frameworks were used.

---

## 🧪 Training Philosophy

* No Adam / SGD optimizers
* No automatic differentiation
* Gradients are **derived and applied manually**
* Emphasis on:

  * Shape tracking
  * Correct gradient flow
  * Mathematical clarity

---

## 📁 File Structure

```
Convolutional_NN_Scratch.ipynb
```

All components are implemented and demonstrated inside the notebook for clarity and step-by-step execution.

---

## 📌 Key Learnings

* Why **reshape layers** are necessary in CNNs
* How **kernels learn through gradients**
* How convolution differs from dense computation
* What frameworks actually do behind the scenes
* Why CNNs are computationally expensive without optimizations

---

## 🔮 Future Improvements

* Add optimizers (SGD, Momentum)
* Extend to multi-class classification
* Improve numerical stability
* Add max/average pooling layers
* Modularize into separate Python files

---

## 📖 Disclaimer

This project is **educational**, not production-ready.
Accuracy and speed were intentionally sacrificed to maximize understanding.

---

## ⭐ If you find this useful

Consider starring ⭐ the repository or using it as a reference to build your own neural networks from scratch.

---

**Built to understand, not to impress.**
