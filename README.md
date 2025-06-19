# 🎥 Movie Data Analysis Project – iScale

This project is focused on analyzing a large movie dataset (`mymoviedb.csv`) using Python libraries like Pandas, NumPy, Seaborn, and Matplotlib. The goal is to clean, process, and visualize data to gain insights such as genre trends, popularity, voting behavior, and movie release patterns over time.

---

## 📁 Dataset Overview

- **File Name:** mymoviedb.csv
- **Size:** ~4 MB
- **Total Rows:** 9,827 (expanded to 25,552 after processing)
- **Columns Included:**
  - `Release_Date`
  - `Title`
  - `Overview`
  - `Popularity`
  - `Vote_Count`
  - `Vote_Average`
  - `Original_Language`
  - `Genre`
  - `Poster_Url`

---

## 🧹 Data Cleaning and Preparation

Steps performed:

- Converted `Release_Date` into year format (`int`).
- Removed unnecessary columns: `Overview`, `Original_Language`, `Poster_Url`.
- Checked and confirmed no missing or duplicated values.
- Categorized `Vote_Average` into:
  - `not_popular`
  - `below_avg`
  - `average`
  - `popular`
- Split and exploded `Genre` column for better analysis (each genre in a separate row).

---

## 📊 Key Questions & Insights

### Q1: What is the most frequent genre?
- ✅ **Answer:** `Drama` is the most frequent genre across all movies.

### Q2: Which genres have the highest average votes?
- ✅ **Answer:** `Drama`, `Thriller`, and `Action` appear the most among top-rated films.

### Q3: What movie is the most popular?
- ✅ **Answer:** *Spider-Man: No Way Home*  
  - Genres: Action, Adventure, Science Fiction

### Q4: What movie has the lowest popularity?
- ✅ **Answer:** *The United States vs. Billie Holiday* and *Threads*

### Q5: Which year had the most movie releases?
- ✅ **Answer:** The year `2020`

---

## 📈 Visualizations

Generated using Seaborn and Matplotlib:

- Bar chart of genre frequency
- Distribution of vote categories
- Most & least popular movie lookup
- Histogram of movie releases by year

---

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## ✅ Features of This Project

- Clean and structured dataset with no missing/duplicate data
- Feature engineering with genre explosion and vote categorization
- Visual storytelling using graphs
- Scalable for recommendation systems and ML models in future

---

## 📌 How to Run

1. Clone the repository
2. Make sure Python and Jupyter are installed
3. Open the `.ipynb` file
4. Run all cells in order

---

## 🙋‍♂️ About Me

I’m an aspiring **Data Analyst/Data Scientist** with a passion for storytelling through data.  
This is one of my self-driven projects to showcase my skills in data preprocessing, exploration, and visualization.

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/debashish-parida-a260b1355) or check out my other work!

---

> ⭐ If you liked this project, consider giving it a star!
