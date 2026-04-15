# 🏏 IPL Data Analysis & Visualization (2008-2024)
### *Exploratory Data Analysis (EDA) of 1,000+ Indian Premier League Matches*

---

## 📌 Project Overview
As a Computer Science student (BCA), I conducted this analysis to uncover the hidden patterns in IPL history. This project dives into match results, toss decisions, venue impacts, and team performance over the last 16 years.

## 🚀 Key Insights
* **The Toss Myth:** Data proves winning the toss only gives a **50.5%** advantage—statistically, it's a coin flip.
* **Chasing Dominance:** 60% of modern captains choose to **Field First**, showing a massive shift in T20 strategy.
* **Standardization:** I successfully merged inconsistent team names (e.g., *Kings XI Punjab* to *Punjab Kings*) to ensure 100% data accuracy.

---

## 📊 Visualization Gallery

### 1. Team Performance & Efficiency
While looking at total wins shows historical dominance, the **Win Percentage** reveals which teams are truly the most efficient.

| Total Wins per Team | Win Percentage by Team |
| :---: | :---: |
| ![Total Wins](./01_total_wins.png) | ![Win %](./08_team_win_percentage.png) |

### 2. The Toss Factor
Captains almost always prefer to field first, but the outcome of the match remains highly competitive regardless of who wins the coin toss.

| Toss Decision Frequency | Toss Win vs. Match Win |
| :---: | :---: |
| ![Toss Decision](./03_toss_decision.png) | ![Toss Impact](./04_toss_impact_logic.png) |

### 3. Venue & Historical Trends
Using boxplots, we can see how winning margins differ across the top 10 stadiums in India, alongside how the league has grown season by season.

| Winning Margin by Venue | Matches Played per Season |
| :---: | :---: |
| ![Venue Boxplot](./06_venue_boxplot.png) | ![Growth Chart](./10_matches_per_season.png) |

---

## 💡 Final Conclusions
- **Toss Strategy:** Most captains now prefer **Fielding First**, reflecting a strong trend toward chasing targets in the T20 format.
- **Consistency:** Teams like **CSK and Mumbai Indians** show high consistency not just in win counts, but in their overall win-to-loss ratio.
- **Venue Impact:** Ground size and pitch conditions at venues like the Chinnaswamy Stadium significantly impact winning margins.

---

## 🛠️ Technical Tools
- **Language:** Python 3.x
- **Libraries:** - `Pandas`: Data cleaning and team name standardization.
    - `Seaborn` & `Matplotlib`: Advanced statistical data visualization.
- **Environment:** Jupyter Notebook / VS Code

## 📁 Project Structure
- `IPL Cricket.ipynb`: The complete Python source code.
- `matches.csv`: The raw dataset used for the analysis.
- `*.png`: 11 high-resolution plots generated during the EDA process.

---
**Created by Sanket Chimaji Gawate** *Day 3 of the 30-Day Data Science Journey*
