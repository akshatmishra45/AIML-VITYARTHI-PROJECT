# AIML-VITYARTHI-PROJECT
## 📌 Project Description  This project builds a Linear Regression model using NumPy to predict student scores from study hours, attendance, and previous marks. It uses Gradient Descent to learn feature relationships, demonstrating core machine learning concepts without external libraries.
# 🎯 Student Score Prediction using Linear Regression (NumPy)

## 📌 Overview

This project implements a simple **Linear Regression model from scratch using NumPy** to predict a student's final score based on:

* Study hours
* Attendance percentage
* Previous score

The model is trained using **Gradient Descent** without relying on machine learning libraries like scikit-learn.

---

## 🚀 Features

* Pure NumPy implementation
* Manual gradient descent optimization
* Multi-variable linear regression
* Simple and easy-to-understand code
* Predicts student performance based on input features

---

## 📂 Dataset

The dataset consists of:

* **Input Features (X):**

  * Hours studied
  * Attendance (%)
  * Previous score

* **Target Variable (y):**

  * Final score

Example:

```
X = [Hours, Attendance, Previous Score]
y = Final Score
```

---

## ⚙️ How It Works

1. Initialize weights and bias to zero
2. Predict output using:

   ```
   y_pred = X·weights + bias
   ```
3. Compute error:

   ```
   error = y_pred - y
   ```
4. Calculate gradients:

   ```
   dw = (1/n) * Xᵀ · error
   db = (1/n) * sum(error)
   ```
5. Update parameters:

   ```
   weights -= lr * dw
   bias -= lr * db
   ```
6. Repeat for multiple epochs

---

## 🧪 Training Details

* Learning Rate: `0.0001`
* Epochs: `10000`
* Optimization: Gradient Descent

---

## 🔮 Prediction Example

```
Input:
Hours = 8
Attendance = 90
Previous Score = 80

Output:
Predicted Score ≈ 85
```


---

## 🤝 Contributing

Pull requests are welcome! Feel free to improve the model or add features.

---

## 📜 License

This project is open-source and available under the MIT License.
