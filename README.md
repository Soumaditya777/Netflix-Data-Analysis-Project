# 📊 Netflix Movie Data Analysis

A data exploration and visualization project on a Netflix-like movie dataset containing 9,800+ entries. The goal is to derive insights about movie trends, genres, ratings, and popularity using Python data analysis tools.

---

## 🔧 Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📁 Dataset Overview

The dataset includes the following columns:

- `Release_Date`: Movie release year  
- `Title`: Movie name  
- `Overview`: Short description *(dropped for analysis)*  
- `Popularity`: Popularity score  
- `Vote_Count`: Number of votes  
- `Vote_Average`: Average rating  
- `Original_Language`: Language *(dropped for analysis)*  
- `Genre`: Comma-separated genres  
- `Poster_Url`: Poster link *(dropped for analysis)*  

**Post-cleaning stats:**
- 25,552 rows (after genre explosion)
- No missing or duplicate values
- Vote averages categorized into: `popular`, `average`, `below_avg`, `not_popular`

---

## 🔍 Key Explorations

### ✅ Data Cleaning

- Converted `Release_Date` to extract the year
- Dropped irrelevant columns: `Overview`, `Poster_Url`, `Original_Language`
- Exploded comma-separated `Genre` column
- Converted `Genre` and `Vote_Average` to categorical variables

### 📈 Visual Insights

- **Most Frequent Genre:** Drama
- **Top Rated Genres:** Drama, Action
- **Most Popular Movie:** *Spider-Man: No Way Home*
- **Least Popular Movies:** *The United States vs. Billie Holiday*, *Threads*
- **Most Active Year for Releases:** 2020

### 📊 Visualizations

- Genre frequency distribution
- Vote average distribution
- Popularity vs. Vote scatter plots
- Movie releases over time

---

## 🧠 Key Learnings

- Data cleaning and preprocessing on real-world media datasets
- Effective use of `seaborn` and `matplotlib` for storytelling
- Genre explosion and categorical mapping for better analysis
- Insights into movie production and audience preferences

---

## 🚀 How to Run

1. Upload the dataset (`mymoviedb.csv`) in Google Colab.
2. Open and run the `Netflix_Data_Analysis.ipynb` notebook.
3. Follow through each section to view data visualizations and insights.

---

## 📌 Conclusion

This project gives a practical perspective on how to handle unstructured movie data and extract valuable business insights using Python and visualizations.

