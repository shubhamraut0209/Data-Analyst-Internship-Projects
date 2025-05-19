
# Zomato Data Analysis Portfolio Project

This project explores a Zomato dataset to extract insights on customer behavior, restaurant preferences, cost trends, and the impact of online vs. offline orders. The goal is to understand patterns in ratings, votes, spending habits, and restaurant types to help platforms like Zomato enhance customer experience and business strategy.

---

## Project Objectives

- Clean and preprocess the Zomato dataset.
- Analyze restaurant types, customer ratings, and cost patterns.
- Compare online vs. offline order performance.
- Identify which restaurant types drive the most votes and engagement.
- Provide insights and actionable conclusions based on data.

---

## Dataset

- **Source:** Zomato data (CSV format)
- **Key Columns:** `rate`, `votes`, `listed_in(type)`, `approx_cost(for two people)`, `online_order`, etc.

---

## Technologies Used

- **Language:** Python  
- **Tools & Libraries:**  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
- **Environment:** Jupyter Notebook / Google Colab

---

## Key Analysis Performed

### 1. Most Common Type of Restaurant
- Used count plots to identify the dominant restaurant types.
- **Finding:** *Casual Dining* is the most frequent type.

### 2. Votes by Restaurant Type
- Aggregated total votes by `listed_in(type)`.
- **Finding:** *Cafes* and *Casual Dining* restaurants received the highest votes.

### 3. Ratings Distribution
- Histogram of `rate` column.
- **Finding:** Most ratings fall between **3.5 to 4.5**.

### 4. Cost Preferences for Couples
- Count plot of `approx_cost(for two people)`.
- **Finding:** Most couples spend around **₹300 to ₹600**.

### 5. Online vs Offline Ratings
- Boxplot comparing ratings for `online_order = Yes` vs `No`.
- **Finding:** *Online orders tend to receive higher ratings.*

### 6. Online Orders by Restaurant Type
- Heatmap of online/offline distribution by restaurant type.
- **Finding:** *Cafes and Quick Bites* dominate online orders.

### 7. Highest Offline Orders by Type
- Found types with the most offline orders.
- **Finding:** *Casual Dining* sees the highest offline traffic.

---

## Final Insights

- **Most Preferred Type:** Casual Dining  
- **Votes Leader:** Cafes & Casual Dining  
- **Online Rating Edge:** Online orders have higher average ratings  
- **Typical Couple Spend:** ₹300–₹600  
- **Offline Traffic Leader:** Casual Dining  
- **Online Order Preference:** Cafes and Quick Bites  

---

## Customer Persona: Zomato’s Typical User

- Orders online frequently from **Cafes and Quick Bites**
- Rates food between **3.5 to 4.5**
- Spends around **₹500** when ordering as a couple
- Prefers **Casual Dining** when eating out
- Engages more with restaurants having good ratings and high votes

---

## Author

**[Shubham Raut]**  
Data Analyst | Python & Visualization Enthusiast  
[LinkedIn Profile](http://linkedin.com/in/shubham-raut-986bb1227) | [GitHub Profile](https://github.com/shubhamraut0209)

---

## License

This project is for educational and portfolio purposes only.
