# 🏠 Airbnb Price Prediction - New York City 🗽

This project aims to predict Airbnb listing prices in New York City using machine learning models based on features like location, room type, amenities, and host details.

![NYC Map](New_York_City_.png)

---

## 📌 Objective

Predict the listing prices for Airbnb properties in NYC to help hosts optimize their pricing strategies for increased revenue.

---

## 🎯 Project Goals

- Import and clean Airbnb NYC 2019 dataset
- Explore price patterns across neighborhoods and room types
- Engineer features and preprocess data
- Visualize key trends and distributions
- Build regression models (Linear Regression, XGBoost)
- Provide pricing insights and recommendations

---

## 🗂️ Dataset

**Source:** Inside Airbnb  
**File:** `AB_NYC_2019.csv`  
**Rows:** ~49,000+  
**Fields:** ID, host_id, neighbourhood, room_type, price, number_of_reviews, availability, etc.

---

## 🔍 Exploratory Data Analysis (EDA)

- Identified **price variations** across neighborhood groups (Manhattan, Brooklyn, etc.)
- Found that **entire home/apartment listings** are priced significantly higher
- Noticed positive correlation between **number of reviews** and pricing
- Filtered out extreme outliers (price > $500)

---

## 🧹 Data Preprocessing

- Handled missing values in `reviews_per_month`
- Removed listings with price outliers
- Converted categorical variables (`neighbourhood_group`, `room_type`) to numerical using one-hot encoding

---

## 📊 Visualizations

- Box plots of price by neighborhood and room type
- Histograms for price distribution
- Correlation heatmap of numeric and encoded features

---

## 🤖 Models Used

| Model             | R² Score |
|------------------|----------|
| Linear Regression | ~0.21   |
| XGBoost Regressor | ~0.38   |

- **XGBoost** outperformed Linear Regression due to its ability to handle complex patterns in data.

---

## 🧠 Key Features Used

- Minimum nights
- Number of reviews
- Reviews per month
- Availability
- Neighbourhood group (One-Hot)
- Room type (One-Hot)

---

## 💡 Recommendations

- **Hosts in Manhattan** can charge premium rates if offering entire homes with high availability.
- **Superhosts** with good reviews and frequent responses should consider pricing slightly higher.
- Consider **seasonal adjustments** in pricing based on availability and review frequency.

---

## 📁 Repository Structure

📦 Airbnb_Price_Prediction_NYC/
│
├── New_York_City_.png # NYC Map image
├── Airbnb_Price_Prediction.ipynb # Jupyter Notebook (Project Code)
├── README.md # Project Documentation

----

## 📌 Tools & Technologies

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📈 Future Improvements

- Include text mining on host descriptions and amenities
- Use NLP on customer reviews
- Deploy model as an API or interactive pricing tool

---

## 🙌 Acknowledgements

Dataset from [Inside Airbnb](http://insideairbnb.com/).  
Map inspired by NYC Open Data.

---

## 🔗 Connect with Me

📧 shubhamraut123.com@gmail.com  
🌐 [LinkedIn](http://linkedin.com/in/shubham-raut-986bb1227) | [GitHub](https://github.com/shubhamraut0209)

---

