# 🎬 Netflix Movie Recommendation System

## 📌 Objective

Build a **content-based recommendation system** using **TF-IDF Vectorization** and **Cosine Similarity** to suggest movies based on user preferences such as genres and descriptions from the Netflix dataset.

---

## 📂 Dataset

- **Source**: [Netflix Movies and TV Shows Dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **File**: `netflix_titles.csv`
- **Features**:
  - `title`: Title of the movie/show
  - `listed_in`: Genre(s)
  - `description`: Short description
  - `type`, `director`, `cast`, `country`, `release_year`, etc.

---

## 🎯 Project Goals

### ✅ Data Collection
- Imported dataset containing Netflix shows and movie metadata.
- Ensured consistency and removed duplicates.

### ✅ Data Preprocessing
- Combined `title`, `listed_in`, and `description` to form a single textual content.
- Removed missing values and duplicates.
- Text normalized for TF-IDF vectorization.

### ✅ Exploratory Data Analysis (EDA)
- Bar charts to analyze genre popularity.
- Release year trends.
- Common genre combinations.

### ✅ Feature Engineering
- Used **TF-IDF Vectorizer** to extract weighted keyword features from combined content.

### ✅ Model Building
- Calculated **cosine similarity** between movie vectors.
- Built a content-based **recommendation engine** that returns the top 10 similar movies.

---

## 🔍 Sample Recommendations

```python
get_recommendations('Narcos')

---

## 📊 Tools & Libraries

- Python (Pandas, Numpy, Sklearn, Matplotlib, Seaborn)

- TF-IDF (Scikit-learn)

- Cosine Similarity (Scikit-learn)
