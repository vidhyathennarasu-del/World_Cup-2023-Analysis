# World_Cup-2023-Analysis

# 🏏 ICC Cricket World Cup 2023 Analysis using Python

## 📌 Project Overview

The **ICC Cricket World Cup 2023 Analysis** project focuses on analyzing player performances, team statistics, match outcomes, and venue trends from the **ICC Men’s Cricket World Cup 2023** using **Python**.

The objective of this project is to transform raw cricket data into meaningful insights through **data cleaning, exploratory data analysis (EDA), visualization, and performance analysis**.

The analysis was performed using **four Excel datasets**:

- Batting Performance Data
- Bowling Performance Data
- Match Schedule & Results
- World Cup Player Information

The ICC Men’s Cricket World Cup 2023 was hosted in **India**, featuring **10 teams and 48 matches** in a round-robin and knockout format. Australia won the tournament by defeating India in the final. :contentReference[oaicite:1]{index=1}

---

## 🎯 Project Objectives

This project aims to:

- Analyze batting and bowling performances.
- Identify top run scorers and wicket takers.
- Evaluate player strike rate and bowling economy.
- Study venue-wise match trends.
- Analyze match-winning patterns.
- Explore player roles and playing styles.
- Compare team performances throughout the tournament.
- Generate visual insights using Python.

---

## 🗂 Dataset Information

This project uses **4 Excel datasets**.

### 1️⃣ Batting Dataset (`batting.xlsx`)

Contains player batting performance details:

| Column Name | Description |
|-------------|-------------|
| Match_no | Match number |
| Match_Between | Teams playing |
| Team_Inn | Batting team |
| Batsman_Name | Player name |
| Batsman_Batting_Position | Batting order |
| Dismissal | Dismissal type |
| Runs | Runs scored |
| Balls | Balls faced |
| 4s | Number of fours |
| 6s | Number of sixes |
| Strike_Rate | Batting strike rate |

---

### 2️⃣ Bowling Dataset (`bowling.xlsx`)

Contains bowling performance details:

| Column Name | Description |
|-------------|-------------|
| Match_no | Match number |
| Match_Between | Match teams |
| Bowling_Team | Bowling team |
| Bowler_Name | Bowler name |
| Overs | Overs bowled |
| Maidens | Maiden overs |
| Runs | Runs conceded |
| Wickets | Wickets taken |
| Economy | Economy rate |

---

### 3️⃣ Match Schedule Results Dataset (`match_schedule_results.xlsx`)

Contains match details and outcomes:

| Column Name | Description |
|-------------|-------------|
| Match_no | Match number |
| Date | Match date |
| Venue | Match venue |
| Team1 | First team |
| Team2 | Second team |
| Winner | Winning team |
| Scorecard | Match score summary |

---

### 4️⃣ World Cup Player Information Dataset (`world_cup_player_info.xlsx`)

Contains player profile information:

| Column Name | Description |
|-------------|-------------|
| player_name | Player name |
| team_name | Team |
| image_of_player | Player image |
| battingStyle | Batting style |
| bowlingStyle | Bowling style |
| playingRole | Playing role |
| description | Player description |

---

## 🛠 Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| Python | Data analysis |
| Pandas | Data cleaning & manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Plotly | Interactive charts |
| Google Colab | Development environment |
| Excel | Dataset storage |

---

## 🧹 Data Preparation

Before analysis, the datasets were cleaned and prepared.

### Data Cleaning Process

- Loaded Excel datasets into Python
- Inspected data structure and column types
- Handled missing values
- Removed duplicate records
- Converted string columns into numeric values
- Standardized column names
- Merged datasets for advanced analysis

---

## 🔗 Dataset Merging

To perform advanced cricket analytics, datasets were merged using:

### Match-Level Join
- `Match_no`

### Player-Level Join
- `Batsman_Name → player_name`
- `Bowler_Name → player_name`

This helped combine:

**Player Profile + Batting + Bowling + Match Results**

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

### 🏏 Batting Analysis
- Top run scorers
- Strike rate analysis
- Boundary analysis (4s & 6s)
- Batting position analysis
- Dismissal patterns

### 🎯 Bowling Analysis
- Top wicket takers
- Economy rate analysis
- Maiden overs analysis
- Bowling efficiency

### 🏟 Venue Analysis
- Matches played by venue
- Venue-wise team performance
- Stadium trends

### 🏆 Match Analysis
- Match winners
- Team winning patterns
- Team performance comparison

### 👤 Player Analysis
- Playing role analysis
- Batting style performance
- Bowling style performance

---

## 📈 Key Visualizations

The project includes multiple visualizations such as:

- Bar Charts
- Pie Charts
- Interactive Plotly Charts
- Team Comparison Charts
- Venue Performance Analysis
- Player Performance Charts

---

## 📌 Key Insights Generated

✔️ Top-performing batsmen and bowlers were identified.

✔️ Team-wise batting and bowling strengths were analyzed.

✔️ Venue patterns revealed stadium performance trends.

✔️ Playing role analysis showed player contribution distribution.

✔️ Match outcome analysis highlighted team consistency.

✔️ Batting and bowling styles were compared for performance impact.

---

## 🚀 Project Workflow

```text
Import Excel Files
        ↓
Data Inspection
        ↓
Data Cleaning
        ↓
Handle Missing Values
        ↓
Convert Data Types
        ↓
Merge Datasets
        ↓
Exploratory Data Analysis (EDA)
        ↓
Data Visualization
        ↓
Insight Generation
```

---

## 📂 Project Structure

```text
Cricket-World-Cup-2023-Analysis/
│
├── batting.xlsx
├── bowling.xlsx
├── match_schedule_results.xlsx
├── world_cup_player_info.xlsx
│
├── Cricket_World_Cup_2023_Analysis.ipynb
│
├── README.md
```

---

## 🎯 Conclusion

This project successfully transformed **ICC Cricket World Cup 2023 data into meaningful insights using Python**.

By combining multiple datasets and performing detailed **EDA and visualization**, the project provides a deeper understanding of:

- Player performance
- Team strategies
- Match outcomes
- Venue impact
- Batting & bowling effectiveness

This project demonstrates practical skills in:

**Python | Pandas | Data Cleaning | EDA | Data Visualization | Sports Analytics**

---

## 👩‍💻 Author

**Vidhya Thennarasu**  
Data Analyst | Python | SQL | Excel | Power BI
