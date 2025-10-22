## Linear_regression_housing_data
## california_housing_regression

📊 **Exercise 1: House Price Prediction using Linear Regression (California Housing Dataset)**

---

### 🔍 Overview

In this project, we work with the **California Housing dataset**, which contains data on average house prices per city block, along with **8 descriptive features** such as income, population, and geographic coordinates.

The goal is to predict house prices using **linear regression**, both using:
- `scikit-learn`’s built-in model
- **Manually implemented** regression using NumPy (closed-form solution)

---

### 🛠️ Technologies Used

| Tool             | Purpose                                 |
|------------------|-----------------------------------------|
| Python (NumPy)   | Manual linear regression implementation |
| scikit-learn     | Dataset loading, regression, evaluation |
| Matplotlib       | Data visualization                      |

---

### 🏡 Dataset Features

| Feature Name | Description                          |
|--------------|--------------------------------------|
| MedInc       | Median income in block               |
| HouseAge     | Median house age in block            |
| AveRooms     | Average number of rooms              |
| AveBedrms    | Average number of bedrooms           |
| Population   | Block population                     |
| AveOccup     | Average house occupancy              |
| Latitude     | House block latitude                 |
| Longitude    | House block longitude                |

- **Samples:** 20,640  
- **Features:** 8  
- **Target:** Median house value per block (continuous)

---

### 📌 Objectives

- Explore and visualize the relationship between house prices and individual features.
- Build a **multiple linear regression model** with 8 input variables.
- Implement linear regression:
  - ✅ Using `LinearRegression` from `scikit-learn`
  - ✅ Using NumPy closed-form solution (`θ = (XᵀX)⁻¹Xᵀy`)
- Evaluate model performance using **Mean Squared Error (MSE)**.

---

### 📂 Tasks Completed

#### ✅ Task 1: Exploratory Data Visualization

- Created scatter plots for each feature vs house price.
- Observed non-linear relationships in several features, such as Latitude and MedInc.

#### ✅ Task 2: Linear Regression with Scikit-Learn

- Trained a `LinearRegression` model.
- Made predictions and evaluated performance with `mean_squared_error`.
- **Result:**  


---

### 📈 Visualizations

- 📌 **Scatter Plots** of house price vs. each feature  
Example:  
- Price vs. Median Income  
- Price vs. Latitude  
- Price vs. Average Rooms

![Sample Plot](california_price_vs_medinc.png)

*Example: Price vs. Median Income*

---

### 📊 Key Learnings

- Practiced implementing **multivariate linear regression** from scratch.
- Reinforced understanding of the **closed-form solution** using matrix algebra.
- Validated that manual and library-based results are consistent when implemented correctly.
- Understood challenges with **non-linear patterns** in real-world datasets.

---

### 🧠 Future Improvements

- Add **feature normalization** or polynomial feature expansion to improve performance.
- Use **regularized regression** (Ridge, Lasso) to reduce overfitting.
- Explore **non-linear models** like Decision Trees or Gradient Boosting.

---



---
