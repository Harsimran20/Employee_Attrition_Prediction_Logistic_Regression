# 🧠 Employee Attrition Prediction System

A machine learning project to predict whether an employee is likely to leave the company using **Logistic Regression**. This model helps HR departments make data-driven decisions to retain key talent.

---

## 🚀 Project Overview

Employee attrition is a critical issue for companies. By leveraging employee data, this system predicts attrition risk based on factors like salary, job satisfaction, overtime, and more.

---

## 📊 Dataset

**Source**: Employee Attrition Dataset  
- Features include: `Age`, `JobRole`, `MonthlyIncome`, `DistanceFromHome`, `Overtime`, `YearsAtCompany`, etc.  
- Target: `Attrition` (Yes = 1, No = 0)

> A small sample dataset is included in this repo (`employee_attrition_logistic_regression.csv`) for testing purposes.

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**: 
  - `pandas`  
  - `scikit-learn`  
  - `numpy`  

---

## 🧱 Model Pipeline

1. **Data Preprocessing**
   - Label encoding for categorical features
   - Feature scaling using `StandardScaler`
2. **Model Training**
   - Train Logistic Regression model on 80% of the data
3. **Evaluation**
   - Use `confusion_matrix` and `classification_report` to assess performance

---

## 📦 How to Run

1. Clone this repository
2. Install dependencies:
   pip install pandas scikit-learn
Run the Python script:

python attrition_prediction.py
📈 Sample Output

Confusion Matrix:
[[0 1]
 [0 0]]

Classification Report:
              precision    recall  f1-score   support

           0       0.00      0.00      0.00       1.0
           1       0.00      0.00      0.00       0.0

    accuracy                           0.00       1.0
   macro avg       0.00      0.00      0.00       1.0
weighted avg       0.00      0.00      0.00       1.0

👩‍💼 Real-World Use Case
Helps HR managers:

Identify at-risk employees

Take proactive engagement or retention actions

Improve employee satisfaction and reduce hiring costs

📄 License
This project is open source under the MIT License.
