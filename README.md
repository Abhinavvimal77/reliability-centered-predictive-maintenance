Reliability-Centered Predictive Maintenance
Using Logistic Regression (Parametric) & Random Forest (Non-Parametric)
📌 Project Overview

This project focuses on Reliability-Centered Predictive Maintenance (RCPM) using machine learning techniques to predict machine failure.

The goal is to identify potential failures in advance using operational sensor data, enabling proactive maintenance planning and improved machine reliability.

Two models were implemented:

Logistic Regression (Parametric Model)

Random Forest Classifier (Non-Parametric Model)

📊 Dataset Information

Total Samples: 10,000

Total Features: 10

Target Variable: Machine Failure (0 = No Failure, 1 = Failure)

Features Used:

Air temperature [K]

Process temperature [K]

Rotational speed [rpm]

Torque [Nm]

Tool wear [min]

Type (Encoded)

Other operational variables

Train-Test Split:

Training: 8,000 samples

Testing: 2,000 samples

Stratified split to preserve class distribution

⚙️ Methodology
1️⃣ Data Preprocessing

Checked datatypes

Handled categorical variables

Feature selection

Train-test split (80–20)

Standardization (for Logistic Regression)

2️⃣ Logistic Regression (Parametric Model)

Used to estimate failure probability

Provides interpretable coefficients

Evaluated using:

Confusion Matrix

Precision / Recall / F1-score

ROC-AUC Score

📈 ROC-AUC ≈ 0.90+

3️⃣ Random Forest (Non-Parametric Model)

Captures nonlinear relationships

Handles feature interactions

More robust to multicollinearity

Outperformed Logistic Regression

📈 ROC-AUC ≈ 0.96+

📉 Model Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

ROC-AUC Score

Confusion Matrix

Actual vs Predicted Scatter Plot

📌 Key Insights

Machine failure is a highly imbalanced problem.

Logistic Regression provides interpretability.

Random Forest provides superior predictive performance.

Combining parametric and non-parametric approaches strengthens predictive maintenance strategy.

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-Learn

Matplotlib

Seaborn

Jupyter Notebook

🚀 Future Improvements

Implement SMOTE for imbalance handling

Add XGBoost / Gradient Boosting

Deploy model using Flask / FastAPI

Real-time monitoring dashboard

👨‍💻 Author

Abhinav M
MSc Statistics – Data Science
Machine Learning | Predictive Analytics | Data Science
