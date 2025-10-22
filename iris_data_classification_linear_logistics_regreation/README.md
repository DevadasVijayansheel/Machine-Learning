## iris_data_classification_linear_logistics_regreation
## classification_iris

📊 **Exercise 1: Multiclass Classification on the Iris Dataset (Linear vs Logistic Regression)**

---

### 🔍 Overview

This project focuses on classifying flower types from the **Iris dataset**, a well-known benchmark in machine learning. It contains **150 samples** from **3 Iris species** (`Setosa`, `Versicolor`, and `Virginica`), with each sample described by **4 features**: sepal length, sepal width, petal length, and petal width.

The challenge lies in the fact that only one class (Setosa) is **linearly separable**, while the other two classes overlap significantly — making it a perfect dataset to test and compare **linear vs. logistic regression** for multiclass classification.

---

### 🛠️ Technologies Used

| Tool               | Purpose                                  |
|--------------------|------------------------------------------|
| Python (NumPy)     | Data manipulation & custom modeling      |
| scikit-learn       | Dataset loading, model training, metrics |
| Matplotlib         | Data visualization                       |

---

### 📌 Objectives

- Load and explore the Iris dataset using `scikit-learn`.
- Visualize feature relationships and class separability.
- Implement a **one-vs-rest** classification approach using:
  - Linear Regression
  - Logistic Regression
- Evaluate classification performance using:
  - Precision, Recall, F1-Score (via `classification_report`)
- Visualize predicted vs. true class labels for comparison.

---

### 📂 Tasks Completed

#### ✅ Task 1: Classification using Linear Regression

- Implemented **One-vs-Rest** classification using `LinearRegression` on each class.
- Standardized the dataset using `StandardScaler`.
- Predicted class labels using the class with the **highest regression output**.
- Visualized results:
  - Used different feature pairs (4 permutations) to compare true and predicted classes.
- **Result:** Linear regression performed well on class 0 but struggled with overlapping classes.

#### ✅ Task 2: Classification using Logistic Regression

- Switched to `LogisticRegression` for better handling of overlapping class boundaries.
- Applied the same One-vs-Rest logic using **class probability outputs**.
- Achieved improved performance across all three classes.
- Matched expected benchmark classification scores:
  
```txt
             precision    recall  f1-score   support

      Class 0     1.00       1.00      1.00        50
      Class 1     0.96       0.96      0.96        50
      Class 2     0.96       0.96      0.96        50

  avg / total     0.97       0.97      0.97       150

