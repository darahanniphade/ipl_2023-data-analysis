# ipl_2023-data-analysis
# 🏏 IPL Data Analysis Project

This project provides a comprehensive analysis of IPL match data, focusing on performance metrics and match outcomes. The goal is to extract insights using Python, pandas, and visualization libraries like Matplotlib and Seaborn.

---

## 📂 Features

### 1. 🧹 Data Cleaning
- Removed null and duplicate entries.
- Standardized column names for ease of use.
- Converted data types (e.g., date columns to datetime format).
- Handled missing values in key columns like `best_bowling_figure`, `player_of_the_match`, etc.

### 2. 🥇 Best Scorer Analysis
- Extracted highest scorers by aggregating `first_ings_score` and `second_ings_score`.
- Visualized top teams and players contributing the most runs.
- Bar plot and pie chart representations of team-wise scoring distributions.

### 3. 🎯 Best Bowling Analysis
- Parsed and cleaned the `best_bowling_figure` column to extract wickets and runs.
- Identified top performers based on number of wickets and best economy.
- Plotted best bowling figures using Seaborn barplots.

### 4. 🧠 Toss Analysis
- Analyzed toss outcomes to find patterns (win/loss relation with toss decision).
- Grouped data by `toss_winner` and `toss_decision`.
- Plotted count of bat/field decisions after winning toss.
- Insight: Whether batting or fielding first correlates with winning the match.

### 5. 🎳 Bowling Team Analysis
- Compared teams based on their bowling performances.
- Aggregated number of wickets taken per team across matches.
- Visualized with horizontal bar plots for clearer comparison.
- Insight: Top bowling teams were consistent in restricting scores and taking wickets.

---

## 📈 Libraries Used
- `pandas` – for data manipulation and cleaning
- `numpy` – for numerical operations
- `matplotlib` – for static plotting
- `seaborn` – for statistical plotting

---

## 📝 How to Run
1. Clone the repository or download the `.ipynb` file.
2. Ensure the `IPL.csv` dataset is in the same directory.
3. Run the notebook step-by-step to explore insights.
4. Modify/extend any section as needed for deeper analysis.

---

## 📊 Future Improvements
- Add player vs player performance metrics.
- Include win prediction model using machine learning.
- Integrate venue-based performance filtering.

---

## 🤝 Contributions
Feel free to raise issues or submit pull requests to add new insights or clean up the code.

---

## 📌 Author
**Darshan Anil Niphade**  
Python | Data Science | IPL Enthusiast

