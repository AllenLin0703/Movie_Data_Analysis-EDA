# 🎮 Movie Data Analysis

This project explores and visualizes insights from a dataset of over **9,000 movies** collected from *The Movie Database (TMDB) API*.
It aims to understand how genres, popularity, votes, and ratings interact to shape trends in the global film industry.

---

## 📁 Project Structure

```
Movie_Data_Analysis/
├── Movie_Data_Analysis.ipynb   # Jupyter notebook containing full EDA process
├── mymoviedb.csv               # Original dataset
├── README.md                   # Project documentation 
```

---

## 🧠 Objective

Perform an end-to-end **Exploratory Data Analysis (EDA)** on movie metadata,
covering descriptive statistics, data cleaning, visualization, and insights.
The analysis also identifies potential business and predictive modeling directions.

---

## 🧩 Key Steps in the Analysis

### 1. Environment Set-up

Importing Python libraries (`pandas`, `numpy`, `matplotlib`) and configuring environment for reproducibility.

### 2. Public Functions

Helper functions were written to:

* Load CSV files with flexible encodings
* Identify relevant columns (titles, genres, votes, etc.)
* Clean and extract primary genres and years from raw strings

### 3. Data Wrangling

Automatic column detection, year parsing, and primary genre extraction were performed.
Numeric columns (votes, ratings, popularity) were standardized.

### 4. Exploration Summary

* Shape and dimensions of the dataset
* Missing value overview
* Sampling of raw data for validation

### 5. Data Cleaning

Removed duplicates, filtered invalid years, and prepared cleaned data for analysis.

---

## 📊 EDA Questions & Visual Insights

| #      | Question                                                | Key Insight                                                                      |
| ------ | ------------------------------------------------------- | -------------------------------------------------------------------------------- |
| **Q1** | Which genre appears most frequently?                    | Drama, Action, and Comedy dominate the dataset.                                  |
| **Q2** | Which genres receive the highest total number of votes? | Action and Adventure attract the most audience engagement.                       |
| **Q3** | Which movie has the highest popularity score?           | *Spider-Man: No Way Home (2021)* is the most popular film, classified as Action. |
| **Q4** | Which year had the largest number of movie releases?    | 2021 recorded the highest number of releases, reflecting post-digital boom.      |
| **Q5** | Which movies are top-rated with sufficient votes?       | Timeless classics like *The Godfather* and *Shawshank Redemption* lead.          |
| **Q6** | What is the relationship between vote count and rating? | Weak correlation (~0.25), indicating that popularity ≠ quality.                  |

---

## 📈 Extended Analysis Suggestions

To expand this notebook into a portfolio-level project, you can include:

* **Correlation Heatmap** between votes, ratings, popularity, budget, and revenue
* **ROI (Return on Investment)** analysis by genre
* **Hypothesis Testing** (e.g., ANOVA for rating differences between genres)
* **Predictive Modeling** for movie ratings based on metadata
* **Trend Analysis** of genre popularity by decade
* **Interactive Dashboard** using Streamlit or Plotly

---

## 🏁 Conclusion

* **Action** and **Drama** dominate both in frequency and audience interaction.
* The **correlation between popularity and rating** is modest, showing distinct audience vs. critic preferences.
* Movie production volume surged sharply after 2000, peaking around **2021**.
* Critically acclaimed classics maintain their reputation over decades.

---

## 💡 Future Work

* Integrate **financial data (budget, revenue)** to explore profitability.
* Perform **sentiment or keyword analysis** on movie overviews.
* Build an **interactive dashboard** for dynamic filtering and exploration.

---

## 🛠️ Technologies Used

* Python 3.12
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn (for potential modeling)
* Jupyter Notebook

---

## ✨ Author

**Zhishen Lin (Allen Lin)**
📍 Rutgers University, MSDS Program
