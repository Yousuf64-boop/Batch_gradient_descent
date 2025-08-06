# Batch Gradient Descent - Linear Regression

This project implements **Batch Gradient Descent (BGD)** from scratch using Python for solving a linear regression problem. It walks through the mathematical intuition and code required to optimize a linear model using BGD.

## 📁 Files

- `Batch_Gradient_Descent_.ipynb` - Jupyter notebook containing the complete implementation of the algorithm.

## 🚀 Features

- Batch Gradient Descent for parameter optimization.
- Cost function visualization (optional if plotting included).
- Manual calculation of gradients and updates.
- Code-only version (no markdown explanations inside notebook).

## 📌 Requirements

Make sure you have the following Python libraries:

```bash
pip install numpy matplotlib
🧠 Algorithm Overview
Initialize weights and bias.

Define a cost function (Mean Squared Error).

Calculate gradients w.r.t weights and bias.

Update parameters iteratively using learning rate.

Repeat for specified number of epochs.

🔍 Example
The goal is to fit a straight line 
𝑦
=
𝑚
𝑥
+
𝑏
y=mx+b to the given data using gradient descent.

python
for epoch in range(epochs):
    y_pred = m * X + b
    error = y - y_pred
    cost = np.mean(error ** 2)
    m -= learning_rate * gradient_m
    b -= learning_rate * gradient_b
📈 Visualization (If applicable)
The notebook may include:

Error reduction over epochs.

Plotting fitted regression line over data points.

✍️ Author
Yousuf Midya
