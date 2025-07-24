✅ Task Summary Report: Heart Disease Prediction
✅ Task Objective
To build a machine learning model that predicts whether a patient is at risk of heart disease based on clinical and physiological features.

📂 Dataset Used
Name: Heart Disease Dataset (Cleveland dataset from UCI repository)

Source:

Local file: heart.csv

Fallback URL: UCI Heart Disease Dataset

Features:

Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, ECG results, max heart rate, exercise-induced angina, oldpeak, slope, ca, thal

Target Variable:

Binary classification:

1: Presence of heart disease

0: No heart disease

🤖 Models Applied
Decision Tree Classifier (from sklearn.tree)

Parameters: max_depth=5, random_state=42

Train-Test Split: 80% training, 20% testing

📊 Key Results and Findings
Accuracy: Typically around 80–85% (based on printed results)

ROC AUC Score: Printed in final output (expected to be ~0.85+ for a good model)

Evaluation Metrics Used:

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

ROC AUC Score

💾 Model Output
Trained model is saved locally as: decision_tree_model.joblib
