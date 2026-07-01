#  Exploratory Data Analysis (EDA) on AFL Player Dataset

## Overview

This project performs **Exploratory Data Analysis (EDA)** on a cleaned and merged Australian Football League (AFL) player dataset. The objective is to uncover meaningful patterns, trends, and insights related to player performance, team statistics, fantasy points, and seasonal participation through data visualization.

The analysis follows standard data analysis practices by answering specific business questions using visualizations and supporting each chart with observations and actionable insights.

---

## Objectives

- Explore the cleaned AFL player dataset.
- Analyze team and player performance.
- Identify trends across seasons.
- Visualize player demographics and statistics.
- Generate business insights from the data.
- Present findings using clear and informative visualizations.

---

## Dataset

The analysis is based on the **merged AFL player dataset** created during the data cleaning and preprocessing stage.

The dataset contains:

- Player Information
- Team Information
- Player Age
- Player Weight
- Seasonal Statistics
- Fantasy Points
- Goals
- Games Played
- Season Information

---

## Business Questions Answered

The notebook addresses the following questions:

1. Which teams have played the most games?
2. What is the distribution of player ages (`last_age`)?
3. Which teams have the highest number of players?
4. How does player weight vary across different teams?
5. Which teams have the highest average fantasy points?
6. Who are the Top 15 goal scorers?
7. How many player records are available for each season?

---

## Visualizations Included

- 📊 Bar Chart – Games Played by Team
- 📈 Histogram – Distribution of Player Ages
- 📊 Bar Chart – Number of Players by Team
- 📦 Box Plot – Player Weight Across Teams
- 📊 Bar Chart – Average Fantasy Points by Team
- 📈 Horizontal Bar Chart – Top 15 Goal Scorers
- 📉 Line Chart – Records Available Per Season

Each visualization includes:

- Business Question
- Appropriate Chart
- 2–3 Observations
- Business Insight

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```text
EDA_AFL/
│
├── merged_players.csv
├── EDA_AFL.ipynb
├── chart1_games_by_team.png
├── chart2_age_distribution.png
├── chart3_players_by_team.png
├── chart4_weight_distribution.png
├── chart5_average_fantasy_points.png
├── chart6_top_goal_scorers.png
├── chart7_records_per_season.png
└── README.md
```

---

## Key Insights

- Teams differ significantly in the total number of games played, highlighting variations in player participation.
- Most AFL players fall within a common age range, suggesting teams primarily rely on athletes in their peak competitive years.
- Player weight varies across teams, reflecting differences in team composition and playing strategies.
- Fantasy point averages reveal notable differences in overall team performance.
- Goal scoring is concentrated among a small group of high-performing players, emphasizing their impact on team success.

---
## Author

**Mehreen Fatima**
