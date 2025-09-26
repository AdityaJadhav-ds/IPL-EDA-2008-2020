# 🏏 IPL Data Analysis (2008–2020) – Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.10-blue.svg) 
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.5-blue.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.8-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-0.12-blueviolet.svg)

---

## 📌 Project Overview
This project provides a **comprehensive analysis of the Indian Premier League (IPL) from 2008 to 2020** using Python.  

It uncovers insights on **team performance, player statistics, toss outcomes, match trends, and seasonal patterns** through **Exploratory Data Analysis (EDA)** and **data visualization**.

⚠️ **Data Note:** Some ball-by-ball data for the first few overs may be missing, so totals and averages may slightly differ from official IPL records. Analysis emphasizes **trends and patterns** rather than exact numbers.  

🖼️ **Visualizations:** All plots and screenshots are stored in the `images/` folder.

---

## 📂 Dataset
Datasets are stored in the `data/` folder:

- `data/IPL Matches 2008-2020.csv` – Match-level details (season, venue, toss, winner, etc.)  
- `data/IPL Ball-by-Ball 2008-2020.csv` – Delivery-level details (runs, wickets, extras, etc.)

> **Note:** If downloading from external sources, place the CSV files in the `data/` folder for the notebook to run correctly.

---

## 🎯 Problem Statement
Perform a **detailed IPL analysis** by answering 35+ key questions:

- Matches & total runs per season  
- Toss decisions & their impact on match outcomes  
- Teams with most wins, highest win %, and 200+ totals  
- Top players: most runs, most wickets, most 4s/6s, highest strike rates  
- Venues hosting most matches & “lucky grounds”  
- Powerplay & death-over performance  

---

## 🔎 Analysis & Visualizations
Key insights and trends include:

- 📊 Season-wise match and run trends (2008–2020)  
- 🏆 Teams with most wins & best winning percentages  
- 🎯 Players with highest runs, most wickets, and top strike rates  
- 🔥 Boundary analysis (4s, 6s, contribution to total runs)  
- ⚡ Highest team totals & biggest win margins  
- 📌 Venue-based winning patterns  

All insights are supported by **Matplotlib** & **Seaborn**, and plots are saved in the `images/` folder.

---

## 📁 Project Structure
The repository is organized as follows:

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
└── SUMMARY.pdf # Key insights and visualizations

---

## 📌 How to Use
1. **Clone the repository:**
```bash
git clone https://github.com/AdityaJadhav-ds/IPL-EDA-2008-2020.git
cd IPL-EDA-2008-2020


