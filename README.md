# NBA Data Analysis & Visualization

This project provides an in-depth analysis of NBA player and team performance using **regular season** and **playoffs** data over multiple seasons. It leverages per-game statistics to visualize player trends, team performance, and highlights improvements during playoffs.

---

## Project Structure
NBA-Analysis/
│
├── data/
│ ├── Regular_Season.csv # Raw regular season data
│ └── Playoffs.csv # Raw playoffs data
│
├── notebooks/
│ └── nba_analysis.ipynb # Jupyter Notebook with analysis & visualizations
│
├── outputs/
│ └── leaderboard_*.csv # Exported leaderboards (PTS, REB, AST)
│
├── README.md # Project overview
└── requirements.txt # Python dependencies


---

## Technologies Used

- Python 3.x  
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `pathlib`  
- Jupyter Notebook for interactive analysis

---

## Analysis & Visualizations

The notebook includes:

1. **Descriptive Statistics**  
   Summary of key player metrics (`PTS`, `REB`, `AST`, `MIN`, `GP`) for regular season and playoffs.

2. **Player-Season Averages**  
   Compute per-game averages (`PTS_AVG`, `REB_AVG`, `AST_AVG`, `MIN_AVG`) for each player.

3. **Team-Season Averages**  
   Aggregate team stats per game, using 82 GP for regular season and max GP per team for playoffs.

4. **Leaderboards**  
   Top 20 players per per-game metric (points, rebounds, assists) for the regular season.

5. **Visualizations**  
   - Distribution of player points per game (histogram with KDE)  
   - Top scorers and top performers per season (bar plots)  
   - Minutes vs points scatter plots  
   - Correlation heatmaps of player stats  
   - Radar charts for top players’ per-game stats  
   - Bubble plots comparing PTS, AST, and REB  
   - Team performance stacked bar plots  
   - Heatmaps for players’ points across seasons  
   - Comparison of regular season vs playoffs performance  

6. **Player Improvement Analysis**  
   Players who improved most in playoffs compared to the regular season.

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/YourUsername/NBA-Analysis.git
cd NBA-Analysis


