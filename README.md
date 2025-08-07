# 🎬 Netflix Data Analysis Project

This project is a simple exploratory data analysis (EDA) of a Netflix movie dataset using Python. The main goal was to clean the data and use visualizations to explore patterns in genres, popularity, ratings, and release trends.

---

## 🎯 Objective

To analyze Netflix's movie data and gain insights into:
- Common genres
- Popularity trends
- Average vote ratings
- Movie release patterns over the years

---

## 🧰 Tools & Libraries

- Python
- Jupyter Notebook
- Pandas (for data cleaning and manipulation)
- NumPy (for numerical operations)
- Matplotlib and Seaborn (for creating visualizations)

---

## 📊 Dataset Overview

- 9,827 rows and 9 columns
- Columns include: `title`, `genres`, `release_date`, `vote_average`, `popularity`, and more

---

## 🔍 What I Did

### 1. Data Preprocessing
- Removed missing values and duplicates
- Dropped columns not needed: `overview`, `original_language`, `poster_url`
- Converted `release_date` to datetime and extracted the release year
- Cleaned up the `genres` column (some entries had multiple genres)
- Created custom categories based on `vote_average`:
  - Popular
  - Average
  - Below Average
  - Not Popular

### 2. Data Visualization
- Answered basic questions like:
  - What are the most common genres?
  - Which movies are the most/least popular?
  - How many movies are released per year?
  - How do vote averages differ by genre?
- Plotted results using bar charts, pie charts, line graphs, and heatmaps

---

## 💡 Key Insights

- Dramas, comedies, and thrillers are the most frequent genres
- Movie production increased significantly after 2010
- Most movies fall into the "Average" vote category
- Certain genres consistently receive higher/lower votes and popularity

---

## 📷 Visuals

I included several charts to help make the analysis easier to understand:
- Genre frequency
- Vote distribution
- Popularity extremes
- Year-wise trends

Feel free to check the file to explore all plots.

---
## 📧 Contact

**Hafsa Zahoor**  
📬 [hafsazahoor63@gmail.com](mailto:hafsazahoor63@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/hafsa-zahoor-6a4b01373?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)
