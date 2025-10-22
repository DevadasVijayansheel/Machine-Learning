ls## linear_regression_numpy_gradient_descent

📉 **Linear Regression using Gradient Descent (NumPy Implementation)**  
🧠 Train a simple linear model using only NumPy matrix operations and gradient math.

---

### 🔍 Project Summary

This notebook implements **linear regression using gradient descent** — from scratch with **NumPy only**.  
The goal is to fit a line to a noisy dataset by minimizing **Mean Squared Error (MSE)** through **manual gradient calculation and iterative updates**.

---

### 🧪 Dataset Detai

- **Samples:** 1000  
- **Input Feature (X):** Random values ∈ [0, 10]  
- **Target (y):**  
  \[
  y = 5x + 3 + \text{noise}
  \]  
- **Noise:** Normally distributed, scaled by 4.0  
- **Bias Term:** Added as a constant column of ones

---

### 🧰 Tools and Libraries Used

| Library       | Purpose                           |
|---------------|-----------------------------------|
| **NumPy**     | Matrix math, gradient updates     |
| **Matplotlib**| Data visualization & loss plotting |
| **Python (3.x)** | Core logic and structure        |

---

### ⚙️ Techniques Used

| Technique              | Description                                                      |
|------------------------|------------------------------------------------------------------|
| **Gradient Descent**   | Manual update of weights based on computed gradients             |
| **Bias Handling**      | Appended column of ones to model the intercept                   |
| **Matrix Multiplication** | Used to compute predictions and gradients                   |
| **MSE Loss Function**  | Used as objective function to minimize over iterations           |
| **Loss Curve Plotting**| Tracked model convergence visually over training steps           |

---
