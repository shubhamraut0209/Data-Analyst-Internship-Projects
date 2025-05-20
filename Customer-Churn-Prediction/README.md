## 📊 Customer Churn Prediction – Telecom Industry

## 🔍 Objective
Build a predictive model to identify customers who are likely to churn from a telecom company, using demographic and service usage data. This helps the company proactively retain valuable customers and improve service quality.

🧠 Project Goals
📥 Data Collection

---

## Dataset: WA_Fn-UseC_-Telco-Customer-Churn.csv

Ensure data privacy compliance.

---

## 🔍 Data Exploration

- Understand subscription types, contract durations, payment methods, etc.

- Identify behavior patterns in churned customers.

---

## 🧹 Data Preprocessing

- Handle missing values and outliers.

- Convert categorical columns into numerical (Label Encoding / One-Hot Encoding).

- Normalize numerical features.

---

## 📊 Exploratory Data Analysis (EDA)

- Visualize churn trends by contract type, payment method, and tenure.

- Use heatmaps and bar charts to understand patterns.

---

## 📌 Feature Selection

Use Random Forest Feature Importance to identify key churn indicators.

---

## 🤖 Model Training

Train three classification models:

- Random Forest

- XGBoost

- VotingClassifier (ensemble of RF + XGB)

Evaluate using accuracy, precision, recall, and F1-score.

---

## 📈 Key Insights from EDA
- Contract Type: Churn is high among customers with Month-to-Month contracts.

- Tenure: Customers with short tenure (< 12 months) are more likely to churn.

- Paperless Billing: Has higher churn than mailed billing.

- AutoPay: Lower churn observed among AutoPay users.

---

## 🤖 Model Performance

 ✅ VotingClassifier (Soft Voting) achieved the best balance of precision and recall, making it suitable for real-time churn prediction.

---

## ✅ Final Conclusion
This project successfully identified key patterns and built predictive models to detect churn risk in telecom customers.
With a high-performing ensemble model, telecom companies can now:

- Implement targeted retention campaigns for customers at risk.

- Offer contract upgrades or discounts to improve customer loyalty.

- Use tenure and payment method insights to personalize customer service.

---

## 📁 Project Structure

├── customer_churn_prediction.ipynb
├── README.md

---

## 💡 Future Enhancements
- Deploy the model using Flask or Streamlit for real-time prediction.

- Automate retraining using recent customer data.

- Integrate customer support feedback for a holistic churn analysis.
