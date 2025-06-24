## ♟ Chess Game Analysis with Data Visualization

This project performs a complete exploratory data analysis (EDA) on a Kaggle chess dataset containing 20,000+ games from [Lichess.org](https://lichess.org). It includes both text-based analysis and data visualizations to uncover patterns in player behavior, openings, outcomes, and ratings.

---

### 📁 Dataset

**Source:** [Kaggle - Chess Games Dataset](https://www.kaggle.com/datasets/datasnaek/chess)
**Features include:**

* Player details (`white_id`, `black_id`, ratings)
* Game metadata (`created_at`, `last_move_at`, `turns`, `duration`)
* Game results (`winner`, `victory_status`)
* Chess-specific details (`moves`, `opening_name`, `opening_eco`, `opening_ply`)

---

### 📊 Project Objectives

* Understand patterns in game outcomes
* Identify impact of openings, player ratings, and duration on results
* Analyze player behavior across time and game types (rated/unrated)
* Visualize key metrics and distributions

---

### 🔍 Key Questions Explored (with Visuals)

1. What is the win rate of White vs Black?
2. Which openings lead to the highest win rates?
3. How long do games typically last?
4. Do rated games last longer than unrated?
5. How does rating difference affect outcome?
6. Which victory statuses are most common?
7. When are games most often played (hour/day)?
8. Do longer openings correlate with wins or losses?
9. How does player rating vary by outcome?
10. What are the most common openings?

And 10+ more, including:

* Game duration by opening
* Turns per result
* Active players
* Top openings by average turns

---

### 🧰 Tools & Libraries

* **Python**
* **Pandas** (data wrangling)
* **Matplotlib & Seaborn** (visualizations)
* **Jupyter Notebook**

---

### 🚀 How to Use

1. Download the dataset from Kaggle and save as `games.csv`.
2. Open the provided Jupyter notebook `Chess_Analytics_Visualizations.ipynb`.
3. Run cells step-by-step to explore and visualize insights.
4. Optionally modify or extend with your own visualizations!

---

### ✅ Future Improvements

* Add interactive dashboard (Streamlit or Dash)
* Integrate time-series trends
* Filter by individual players

---
