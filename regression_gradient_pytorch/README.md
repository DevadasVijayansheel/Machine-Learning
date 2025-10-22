## linear_regression_pytorch

🔥 **Linear Regression with Gradient Descent Using PyTorch**  
📌 Implemented from scratch using auto-differentiation and tensor operations.

---

### 🔍 Project Summary

This notebook implements **linear regression using gradient descent in PyTorch**, replicating the functionality of a NumPy-based solution with the added benefit of **automatic differentiation**.  
We use a **synthetic 1D dataset** with added Gaussian noise to simulate real-world data variation. PyTorch handles **gradient tracking**, **backpropagation**, and **tensor operations**, enabling efficient training and model optimization.

---

### 🧪 Dataset Details

- **Samples:** 1000  
- **Feature (X):** Random values between 0 and 10  
- **Target (y):** Computed as  
  \[
  y = 5x + 3 + \text{noise}
  \]  
- **Noise:** Normally distributed noise with standard deviation ≈ 4.0  
- **Bias Term:** Appended as a constant column of ones to learn the intercept

---

### 🧰 Tools and Libraries Used

| Library       | Purpose                                        |
|---------------|------------------------------------------------|
| **NumPy**     | Data generation, matrix manipulation           |
| **PyTorch**   | Tensor math, backpropagation, optimization     |
| **Matplotlib**| Visualization of data and training progress    |
| **Python (3.x)** | Core logic and implementation               |

---

### ⚙️ Techniques Used

| Technique                         | Description                                                                     |
|----------------------------------|---------------------------------------------------------------------------------|
| **Gradient Descent**             | Iteratively minimizes MSE loss by updating weights                             |
| **Bias Handling**                | Added column of 1s to X to learn the intercept term                            |
| **MSE Loss Function**            | Loss = mean squared error between predictions and true values                  |
| **Automatic Differentiation**    | PyTorch tracks operations and computes gradients automatically with `.backward()` |
| **Manual Weight Update Loop**    | Used `with torch.no_grad()` for safe weight updates without tracking history   |
| **Gradient Resetting**           | Cleared gradients after each iteration using `weights.grad.zero_()`            |

---

###