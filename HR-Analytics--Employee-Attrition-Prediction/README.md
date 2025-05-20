# HR Analytics – Employee Attrition Prediction

## **Overview**
This project focuses on predicting employee attrition using various HR-related features such as job role, satisfaction levels, overtime, and salary. It aims to help HR teams proactively identify at-risk employees and implement retention strategies.

---

## **Objective**
To build a machine learning model that predicts whether an employee is likely to leave the organization based on historical data and work-related factors.

---

## **Dataset**
- Source: [IBM HR Analytics Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- File: `WA_Fn-UseC_-HR-Employee-Attrition.csv`
- Records: 1,470 employees
- Features: Demographics, job role, satisfaction levels, performance ratings, etc.

---

## **Project Pipeline**

### 1. **Data Collection**
- Imported HR dataset.
- Ensured ethical handling and confidentiality of data.

### 2. **Data Exploration**
- Identified high attrition rates among employees with:
  - High overtime hours
  - Low job satisfaction
  - No recent promotions

### 3. **Data Preprocessing**
- Handled missing values.
- Converted categorical variables using Label Encoding and One-Hot Encoding.
- Normalized numerical features.

### 4. **Exploratory Data Analysis (EDA)**
- Used heatmaps, bar plots, and pairplots to visualize trends.
- Identified strong correlation between attrition and features like OverTime, JobSatisfaction, and YearsSinceLastPromotion.

### 5. **Model Building**
- Trained multiple models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - Voting Classifier (Ensemble)
- Used cross-validation, confusion matrices, and classification reports for evaluation.

---

## **Results**

| Model               | Accuracy | F1-Score |
|--------------------|----------|----------|
| Logistic Regression| ~83%     | Moderate |
| Random Forest       | ~88-90%  | High     |
| XGBoost             | ~90%     | High     |
| **Voting Classifier**   | **91%+**  | **Best**  |

> **Best Performing Model:** Voting Classifier

---

## **Key Insights**
- Employees doing **OverTime** are most likely to leave.
- **Low Job Satisfaction** is a critical churn driver.
- **Long gaps since last promotion** also impact attrition rates.
- **Work-Life Balance** and **Environment Satisfaction** are strong influencers.

---

## **Business Recommendations**
1. Limit excessive overtime to prevent burnout.
2. Improve engagement through regular feedback.
3. Recognize and reward long-standing employees.
4. Promote a healthier work-life balance and team environment.

---

## **Conclusion**
The model successfully predicts employee attrition and identifies actionable drivers of churn. It can be integrated into HR workflows to proactively retain top talent.

---

## **Tech Stack**
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- SMOTE (for class imbalance)
