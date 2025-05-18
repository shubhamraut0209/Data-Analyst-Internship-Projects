
# 🛍️ New Year Sales Analysis Project

This project presents an in-depth analysis of New Year sales data to uncover valuable insights about customer behavior, purchasing patterns, and regional preferences. The findings can guide data-driven business strategies and marketing efforts during festive seasons.

---

## 📁 Dataset

The dataset contains sales transaction records including customer demographic details, product category, purchase amount, and location information.  
📄 Filename: `New Year Sales Data.csv`  
🗃️ Rows: 11251  
🧩 Columns: 15

---

## 🚀 Objectives

- Analyze customer behavior based on gender, age, marital status, and occupation.
- Identify top-performing states and most preferred product categories.
- Uncover insights to build a **high-purchasing customer persona**.
- Explore additional behavioral questions to extend insights.

---

## 🧰 Tools & Libraries Used

- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn
- Google Colab (development platform)

---

## 🧹 Steps Followed

### ✅ Step 1: Import Libraries
- Imported `numpy`, `pandas`, `matplotlib.pyplot`, `seaborn`.
- `%matplotlib inline` used for inline plotting.

### ✅ Step 2: Load Dataset
- Loaded the CSV file and previewed the dataset using `head()` and `info()`.

### ✅ Step 3: Data Cleaning
- Dropped unnecessary columns.
- Handled missing values.
- Converted the `Amount` column to integer type.

### ✅ Step 4: Data Overview & Summary
- Used `describe()` and `value_counts()` to understand key metrics.

---

## 📊 Exploratory Data Analysis (EDA)

### 👨‍👩‍👧 Gender Analysis
- **Observation**: Males contributed higher total purchases than females.

### 🧓 Age Group Analysis
- **Observation**: The **26–35** age group made the highest number of purchases and had the highest revenue.

### 🏙️ State Analysis
- **Observation**: **Uttar Pradesh**, **Maharashtra**, and **Karnataka** were the top contributors in orders and revenue.

### 💍 Marital Status Analysis
- **Observation**: Married individuals, especially **married men**, spent more than unmarried individuals.

### 💼 Occupation Analysis
- **Observation**: **IT professionals** and **Healthcare workers** contributed most to sales volume and value.

### 📦 Product Category Analysis
- **Observation**: Highest sales volume in **Clothing & Apparel**, but highest revenue from **Electronics** and **Footwear**.

---

## ❓ Additional Exploratory Questions

1. **Which age group contributes most to each product category?**
   - 26–35 age group dominated in most categories.
   - Notable variation seen in product preferences between genders.

2. **How does marital status affect spending across age groups?**
   - Married individuals in 26–35 and 36–45 age ranges showed the highest average spend.

3. **Which states show highest growth in revenue or orders?**
   - Dataset lacks "Date" column; thus, growth or seasonality analysis couldn't be performed.

4. **Are there occupation-category preferences?**
   - Yes. IT professionals favored Electronics; Healthcare workers leaned towards Clothing & Personal Care.

5. **Correlation between Age and Spending?**
   - Mild positive correlation observed. Males showed a stronger correlation than females.

---

## 🧑‍💼 Customer Persona: High-Purchasing Customer Profile

| Attribute      | Value                                |
|----------------|--------------------------------------|
| Gender         | Male                                 |
| Age Group      | 26–35 years                          |
| Marital Status | Married                              |
| Occupation     | IT or Healthcare                     |
| Product Focus  | Electronics, Footwear, Clothing      |
| Location       | Uttar Pradesh, Maharashtra, Karnataka|

---

## ✅ Conclusion

This project provided actionable insights into New Year sales behavior. The analysis highlighted the influence of age, gender, marital status, occupation, and location on purchasing patterns. These findings can guide targeted marketing, inventory planning, and customer engagement strategies.

---

## 📌 Project Developed By

**[Shubham Raut]**  
💼 Data Analyst Intern @ Inlighn Tech  
📆 Duration: March 2025 – Present  
🌐 GitHub: [https://github.com/shubhamraut0209]  
🔗 LinkedIn: [http://linkedin.com/in/shubham-raut-986bb1227]
