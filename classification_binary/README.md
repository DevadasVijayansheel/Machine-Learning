## classification_binary
📊 Exercise 1: Binary Classification using Linear Regression (Manual + Scikit-Learn)
🔍 Overview


### 🛠️ Technologies Used

| Tool           | Purpose                              |
|----------------|--------------------------------------|
| Python (NumPy) | Matrix operations & manual modeling  |
| Matplotlib     | Data visualization                   |
| scikit-learn   | Dataset generation & metric evaluation |



This project demonstrates a hands-on implementation of binary classification using a synthetic dataset generated with make_blobs. The classification is achieved using linear regression, first implemented manually using NumPy and then validated using scikit-learn. The exercise focuses on core machine learning principles, such as model fitting, decision boundaries, classification accuracy, and metric evaluation — both automated and manual.

📌 Objectives

Generate a 2D, two-class dataset with noise using sklearn.datasets.make_blobs.

Implement linear regression from scratch using NumPy.

Use the regression output to classify samples into two classes.

Visualize classification and decision boundaries using matplotlib.

Evaluate model performance using:

Accuracy

Confusion matrix

Precision, recall, and F1 score (manual and sklearn)

Precision-Recall Curve (automated and manual)

📂 Tasks Completed
✅ Task 1: Linear Regression with NumPy (Manual)
Computed weights using the closed-form solution of linear regression.

Predicted regression scores and classified based on proximity to class 0 or 1.

Plotted:

Classified data with color coding.

Decision boundary line based on regression weights.

Evaluated performance with classification_report and precision_recall_curve from scikit-learn.

✅ Task 2: Manual Evaluation Metrics (NumPy)
Calculated:

Confusion Matrix (TN, FP, FN, TP)

Accuracy, Precision, Recall, F1 Score

Plotted precision-recall curve using manual calculations across different thresholds.

✅ Task 3: Linear Regression with Scikit-Learn
Reproduced classification using LinearRegression from sklearn.

Extracted model weights and intercept to compute and plot the decision boundary.

Evaluated performance using:

classification_report

precision_recall_curve + plotting

✅ Task 4: Manual Evaluation with Scikit-Learn Predictions
Performed the same manual evaluation (Task 2) using predictions from LinearRegression.

Verified consistency between manual and library-based metric calculations.

📈 Visualizations
Scatter plots showing classified points (Class 0 vs Class 1).

Decision boundary separating predicted classes.

Precision-Recall curves for:

Scikit-learn based predictions

Manually calculated thresholds



📊 Key Learnings
Applied machine learning fundamentals without black-box libraries.

Understood linear regression behavior for classification.

Gained practical insights into precision-recall trade-offs.


