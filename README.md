# 🏏 Cricket Player Performance Analysis

## 📌 Project Overview

This project analyzes cricket player performance using Python, Pandas, NumPy, and Matplotlib.

The analysis covers batting, bowling, and fielding statistics to identify top-performing players, compare teams and player roles, perform statistical analysis, and create visualizations.

## 🎯 Objectives

- Clean and preprocess cricket player data
- Handle missing values
- Calculate Mean, Median, and Standard Deviation
- Analyze player performance by team and role
- Identify top run scorers
- Identify top wicket takers
- Analyze strike-rate distribution
- Create data visualizations
- Generate a cricket performance summary

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

## 📂 Dataset

The dataset contains the following columns:

- Player
- Team
- Role
- Matches
- Innings
- Runs
- Balls_Faced
- Batting_Average
- Strike_Rate
- Wickets
- Overs_Bowled
- Runs_Conceded
- Economy_Rate
- Catches

## 🧹 Data Cleaning

Missing values were handled using statistical methods:

- `Catches` → Median
- `Economy_Rate` → Mean
- `Batting_Average` → Mean

After cleaning, there were no missing values remaining in the dataset.

## 📊 Statistical Analysis

The project calculates statistical measures for:

- Runs
- Strike Rate
- Wickets

### Runs

- Mean: 897.45
- Median: 914.5
- Standard Deviation: 327.36

### Strike Rate

- Mean: 53.86
- Median: 53.3
- Standard Deviation: 13.28

### Wickets

- Mean: 24.7
- Median: 24.0
- Standard Deviation: 14.00

## 🔎 Analysis Performed

### Team Analysis

Player performance was analyzed across:

- Australia
- England
- India
- New Zealand
- South Africa

Metrics analyzed include:

- Runs
- Wickets
- Catches

### Role Analysis

Performance was compared across:

- Batsman
- Bowler
- All-Rounder
- Wicketkeeper

Metrics include:

- Runs
- Wickets
- Strike Rate

## 🏆 Top Performers

### Top Run Scorers

The project identifies the top 10 run scorers.

The highest run scorer in the dataset is:

**Aakash Jain — 1,433 Runs**

### Top Wicket Takers

The project identifies the top 10 wicket takers.

The highest wicket totals shown are:

**Kabir Sethi — 43 Wickets**

**Yash Gupta — 43 Wickets**

## 📈 Visualizations

The project includes the following visualizations:

1. Runs Scored by Players — Line Chart
2. Top 10 Run Scorers — Bar Chart
3. Top 10 Wicket Takers — Bar Chart
4. Strike Rate Distribution — Histogram

## 📌 Final Performance Summary

The project generates a summary containing:

- Highest Run Scorer
- Highest Wicket Taker
- Highest Strike Rate
- Average Runs
- Average Wickets

### Results

- Average Runs: **897.45**
- Average Wickets: **24.7**

## 📁 Project Structure

```text
Cricket-Player-Performance-Analysis/
│
├── cricket_player_analysis.ipynb
├── cricket_players.csv
└── README.md
```

## Dashboard Preview
## 📊 Power BI Dashboard<img width="1077" height="591" alt="Screenshot 2026-09-27 170540" src="https://github.com/user-attachments/assets/df45a556-26ab-4d6b-a4c8-855041272b61" />
<img width="783" height="642" alt="Screenshot 2026-09-27 170507" src="https://github.com/user-attachments/assets/9df2b78b-4001-4dd9-9339-1f004ed92a7f" />
<img width="797" height="622" alt="Screenshot 2026-09-27 170440" src="https://github.com/user-attachments/assets/33c7f950-8a60-41b2-ba67-29e7234ddb85" />
