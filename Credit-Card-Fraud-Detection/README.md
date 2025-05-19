# 💳 Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions in real-time using classification algorithms and advanced data preprocessing techniques.

---

## 📌 Objective

Develop a predictive model that can accurately flag suspicious credit card transactions as fraud or non-fraud using transaction history and anonymized features.

---

## 🧠 Project Goals

### 1. Data Collection
- Used the [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud) containing **284,807 transactions** and **31 features**.
- Ensured data privacy and security compliance by using anonymized principal components (V1–V28).

### 2. Data Exploration
- Examined fraud distribution (only **0.17%** of transactions are fraudulent).
- Explored transaction `Amount` and `Time` for anomalies.
- Visualized distributions using histograms and box plots.

### 3. Data Preprocessing
- Normalized `Amount` and `Time` features using `StandardScaler`.
- Addressed data imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**.
- Removed outliers and prepared data for model training.

### 4. Exploratory Data Analysis (EDA)
- Visualized fraud vs non-fraud distributions for key features.
- Detected correlations using heatmaps.
- Identified skewness in transaction patterns.

### 5. Feature Engineering
- Applied scaling to numerical features.
- Focused on feature importance for model selection.
- Used balanced datasets for fair model evaluation.

### 6. Model Training & Evaluation
- Trained and compared:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost Classifier
  - Voting Classifier Ensemble
- Evaluated using:
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-Score)
  - ROC-AUC Score

---

## 📊 Results


> 🚨 Voting Classifier Model performed best in identifying fraudulent transactions while maintaining low false positives.

---

## 📌 Key Insights

- **Imbalanced data** required proper handling to avoid biased models.
- **SMOTE** effectively balanced the training dataset.
- Most fraudulent transactions had **lower amounts**, often under $2,000.
- Fraud detection relies heavily on hidden patterns in PCA components.

---

## 📁 Files Included

- `fraud_detection.ipynb` – Jupyter Notebook with all steps
- `README.md` – Project documentation

---

## 🔧 Libraries Used

- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- imbalanced-learn (SMOTE)
- xgboost

---

## 💡 Future Work

- Implement real-time transaction monitoring.
- Deploy model using Flask or FastAPI as a microservice.
- Integrate with live banking APIs for production environments.

---

## 🙌 Acknowledgements

- Dataset Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## 🧑‍💻 Author

**[Shubham Raut]** – *Data Analyst / Aspiring Data Scientist*

Feel free to ⭐ this repo if you found it useful, and fork for your own use!

