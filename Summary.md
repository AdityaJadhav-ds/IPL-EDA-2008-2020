# IPL Data Analysis (2008–2020) – Summary

## Project Overview

This project performs a **comprehensive exploratory data analysis (EDA)** of the **Indian Premier League (IPL)** spanning **2008–2020**. Using Python, Pandas, NumPy, Matplotlib, and Seaborn, the project uncovers insights into:

- Team performance trends
- Player statistics and achievements
- Toss decisions and their impact
- Match outcomes and seasonal patterns
- Scoring patterns in powerplay and death overs
- Venue-based performance trends

⚠️ **Data Note:** Some ball-by-ball data for the first few overs may be missing, so totals and averages may slightly differ from official records. The analysis emphasizes **patterns and trends** rather than exact numbers.

---

## 📂 Dataset
Datasets are stored in the `data/` folder:

- `data/IPL Matches 2008-2020.csv` – Match-level details (season, venue, toss, winner, etc.)  
- `data/IPL Ball-by-Ball 2008-2020.csv` – Delivery-level details (runs, wickets, extras, etc.)

> Datasets are stored in the `data/` folder.
  
---

## Methodology

1. Load and clean datasets using **Pandas and NumPy**.
2. Perform **EDA** to answer 35+ IPL-related questions.
3. Visualize patterns using **Matplotlib and Seaborn**.
4. Analyze trends for matches, teams, players, boundaries, run rates, toss decisions, and venues.
5. Save all plots in the `images/` folder for easy reference.

---

## Key Analysis Areas

### Team & Match Analysis
- Total matches and runs per season
- Teams with most wins and highest win percentages
- Matches with 200+ totals and highest run margins

### Player Performance
- Leading run-scorers and wicket-takers
- Players with most balls faced, highest strike rates, most 4s/6s
- Most MOM awards

### Toss & Strategy
- Toss winners and decisions (bat/field)
- Correlation between toss wins and match outcomes

### Venue & Scoring Patterns
- Stadiums hosting most matches
- “Lucky grounds” for teams
- Runs scored in first 6 overs (powerplay) and last 4 overs (death overs)
- Run-rate trends and boundary contributions

---

## Key Insights

- 📈 Matches and total runs have increased over IPL seasons (2008–2020).  
- 🏆 **Dominant Teams:** Mumbai Indians and Chennai Super Kings consistently perform better.  
- 🎯 **Top Players:** Virat Kohli, David Warner, Lasith Malinga, and Amit Mishra lead in runs and wickets.  
- ⚡ **High Scores & Boundaries:** Teams consistently exploit powerplay and death overs for higher scores; boundaries contribute significantly to totals.  
- 📊 **Venue Insights:** Certain stadiums favor specific teams, revealing “lucky grounds.”  
- ⚖️ **Toss Analysis:** Winning the toss does not guarantee a win; strategic decisions vary across seasons.

---

## Project Structure
IPL_EDA_2008-2020/
│
├── data/
│ ├── IPL Matches 2008-2020.csv
│ └── IPL Ball-by-Ball 2008-2020.csv
│
├── images/
│ ├── highest_runs.png
│ ├── top_batsmen.png
│ └── season_trends.png
│
├── ipl_eda.ipynb # Main Jupyter notebook
├── LICENSE # MIT License
├── README.md # Project documentation
└── SUMMARY.md # Project summary

---

## 8. Tools & References
- Python: Pandas, NumPy, Matplotlib, Seaborn  
- Jupyter Notebook for analysis  
- IPL datasets (2008–2020)  

---

## 9. Conclusion
- IPL analysis provides **patterns, trends, and insights** from 2008–2020  
- Team and player performance trends are consistent across seasons  
- Toss, venue, and innings strategies influence outcomes  
- Focus is on **patterns over exact statistics** due to minor missing data
