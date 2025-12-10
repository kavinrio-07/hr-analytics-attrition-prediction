# 📊 HR Analytics – Employee Attrition Prediction

A machine learning project to analyze HR data and predict employee attrition using data preprocessing, EDA, and multiple classification models.

---

## 🚀 Project Overview
Employee attrition affects business continuity and recruitment costs.  
This project builds a predictive model to identify employees likely to leave the company.

Key steps:
- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature encoding  
- Model training and evaluation  
- Saving the best model for reuse

---

## 📁 Dataset
The dataset contains HR attributes such as:
- Age  
- Job Role  
- Monthly Income  
- Work-life balance  
- Job satisfaction  
- Overtime  
- Distance from home  
- Years at company / Years with current manager  
- And more...

**Target variable:** `Attrition` (Yes / No)

> Note: The dataset file is expected at `/data/hr_dataset.csv` (add it to the `data/` folder).

---

## 🛠️ Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Joblib

---

## 🔍 Steps Performed

### 1. Data Preprocessing
- Removed irrelevant columns (`EmployeeCount`, `EmployeeNumber`, `Over18`, `StandardHours`)  
- Checked for missing values and duplicates  
- Separated categorical & numerical columns  
- Applied label encoding for categorical features

### 2. Exploratory Data Analysis (EDA)
- Visualized attrition distribution  
- Created correlation heatmap to inspect feature relationships

### 3. Model Building
Trained the following models:
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)

### 4. Model Evaluation
Used:
- Accuracy score  
- Confusion matrix  
- Cross-validation (5-fold)

**Best model chosen:** Random Forest Classifier (saved to `models/HR_Analytics_Model.pkl`)

---

## 📈 Results
- Random Forest achieved the best balance of accuracy and stability across cross-validation folds.
- The saved model can be loaded to make predictions on new employee data.

---

## 🗂️ Recommended Repository Structure

