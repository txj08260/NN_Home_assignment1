# 📘 CS5720 – Neural Networks and Deep Learning  
**University of Central Missouri**  
**Instructor**: Dr. I-Hua Tsai  
**Semester**: Summer 2025  

---

## 👤 Student Information

| Name                  | Student ID | Course                                 |
|-----------------------|------------|----------------------------------------|
| Jagarlamudi Tharaka   | 700770826  | CS5720 – Neural Networks and Deep Learning |

---

## 📚 Assignment Overview

This assignment showcases core **TensorFlow** operations and fundamental **deep learning** concepts. The tasks were designed to practice:

- Tensor creation, reshaping, broadcasting
- Implementation and comparison of loss functions
- Neural network training and analysis using **TensorBoard**
- Interpretation of model training behavior

---

## ✅ Tasks Completed

### 🔹 1. Tensor Manipulations & Reshaping
- Generated random tensor with shape **(4, 6)**
- Reshaped to **(2, 3, 4)** and transposed to **(3, 2, 4)**
- Performed broadcasting with tensor of shape **(1, 4)**
- Explained the concept of **broadcasting** in TensorFlow

### 🔹 2. Loss Functions & Hyperparameter Tuning
- Implemented:
  - **Mean Squared Error (MSE)**
  - **Categorical Cross-Entropy (CCE)**
- Compared loss values for different prediction scenarios
- Visualized results using **Matplotlib** bar charts

### 🔹 3. Neural Network Training + TensorBoard
- Built a basic **neural network model** using TensorFlow and Keras
- Trained model on the **MNIST** dataset
- Configured logging for:
  - Accuracy and loss
  - Histogram summaries
  - Learning rate tracking
- Visualized metrics using **TensorBoard**

### 🔹 4. Analysis (Q&A)
- Analyzed overfitting, learning trends, and validation gaps
- Answered reflective questions based on TensorBoard insights
- Provided commentary directly in notebook cells

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Home_assignment1.ipynb` | Google Colab notebook with complete implementation |
| `README.md` | This documentation file |

---

## 🚀 How to Run

> Recommended Platform: [Google Colab](https://colab.research.google.com/)

1. Open `Home_assignment1.ipynb` in Google Colab  
2. Run each cell sequentially  
3. After training the model, launch TensorBoard by running:  
   ```python
   %tensorboard --logdir logs/fit/


