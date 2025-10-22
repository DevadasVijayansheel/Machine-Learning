## linear_regression_torch_optimizer

⚙️ **Linear Regression Using PyTorch Optimizer and Loss Module**  
🚀 Implemented with `torch.nn.MSELoss` and `torch.optim.SGD` for efficient training.

---

### 🔍 Project Summary

This notebook demonstrates how to implement **linear regression** using **PyTorch’s built-in tools**:
- `torch.nn.MSELoss` for loss computation
- `torch.optim.SGD` for weight optimization

We train a model on a **synthetically generated 1D dataset with noise**, using a gradient descent optimizer instead of manual updates.

---

### 🧪 Dataset Details

- **Samples:** 1000  
- **Input Feature (X):** Random float values ∈ [0, 10]  
- **Target (y):** Linear formula with noise:  
  \[
  y = 5x + 3 + \text{noise}
  \]  
- **Noise:** Gaussian noise (standard deviation ≈ 4.0)  
- **Bias Term:** Included manually as column of ones

---

### 🧰 Tools and Libraries Used

| Library       | Purpose                                  |
|---------------|------------------------------------------|
| **NumPy**     | Data generation, matrix setup            |
| **PyTorch**   | Tensors, MSELoss, SGD optimizer          |
| **Matplotlib**| Data & loss visualization                |
| **Python (3.x)** | Core logic and scripting             |

---

### ⚙️ Techniques Used

| Technique                    | Description                                                              |
|------------------------------|--------------------------------------------------------------------------|
| **Synthetic Data Generation**| Random data following a noisy linear rule                                |
| **Bias Handling**            | Appended a column of ones to model the intercept                         |
| **MSE Loss (torch.nn)**      | Measures prediction error during training                                |
| **Optimizer (SGD)**          | Automatically handles gradient step and weight updates                   |
| **Autograd Backpropagation** | `.backward()` computes gradients from loss                               |
| **Looped Optimization**      | Optimizer steps inside an iteration loop to minimize loss progressively  |

---



