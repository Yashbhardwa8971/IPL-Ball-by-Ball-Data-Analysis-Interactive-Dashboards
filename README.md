# IPL Ball-by-Ball Data Analysis & Interactive Dashboard

## Project Overview

This project analyzes Indian Premier League (IPL) ball-by-ball data from 2008 onwards using Python and data visualization techniques.

The objective is to uncover insights related to:

* Team performance
* Player performance
* Orange Cap winners
* Purple Cap winners
* Venue analysis
* Toss analysis
* Season-wise trends
* Boundary analysis
* Strike rate analysis

The project demonstrates data cleaning, exploratory data analysis (EDA), visualization, and dashboard development skills.

---

## Dataset Information

The dataset contains ball-by-ball IPL match data with information such as:

* Match ID
* Date
* Venue
* Batting Team
* Bowling Team
* Batter
* Bowler
* Runs
* Wickets
* Toss Winner
* Match Winner
* Player of the Match

**Total Features:** 65+

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Streamlit
* Jupyter Notebook

---

## Data Cleaning

Performed the following preprocessing tasks:

* Removed duplicate records
* Handled missing values
* Standardized venue names
* Converted date columns into datetime format
* Extracted season information
* Created derived metrics for analysis

---

## Exploratory Data Analysis

### Team Analysis

* Most Successful IPL Teams
* Team Boundary Analysis
* Team Win Distribution
* Toss Impact Analysis

### Player Analysis

* Top Run Scorers
* Top Wicket Takers
* Orange Cap Winners by Season
* Purple Cap Winners by Season
* Best Strike Rates

### Venue Analysis

* Most Used Venues
* Venue-wise Match Distribution

### Season Analysis

* Runs Scored Per Season
* Season-wise Performance Trends

---

## Visualizations

### Team Wins

> Upload image as: `images/team_wins.png`

---

### Top Run Scorers

> Upload image as: `images/top_run_scorers.png`

---

### Top Wicket Takers

> Upload image as: `images/top_wicket_takers.png`

---

### Orange Cap Winners

> Upload image as: `images/orange_cap_winners.png`

---

### Purple Cap Winners

> Upload image as: `images/purple_cap_winners.png`

---

### Runs Per Season

> Upload image as: `images/runs_per_season.png`

---

### Team Heatmap

> Upload image as: `images/team_heatmap.png`

---

## Key Insights

- Virat Kohli is the highest run scorer in IPL history.
- The Orange Cap winners consistently scored 500+ runs in their respective seasons.
- Leading wicket-taking bowlers dominated multiple IPL seasons and influenced match outcomes significantly.
- Certain venues such as Wankhede Stadium, Eden Gardens, and M. Chinnaswamy Stadium hosted a large number of IPL matches.
- Teams winning the toss showed clear preferences for batting or bowling first depending on venue conditions.
- IPL scoring rates have increased over the years, indicating a more aggressive batting approach.
- Boundary frequency (fours and sixes) has increased significantly in recent seasons.
- Strike rate analysis highlights the growing importance of power hitters in modern T20 cricket.
- Team performance varies considerably across venues and seasons.
- Historical trends reveal the evolution of batting strategies and match dynamics throughout IPL history.

---

## Dashboard

A Streamlit dashboard was developed to provide:

* Interactive filtering
* Team analysis
* Player analysis
* Season analysis
* Visual exploration

Run locally using:

```bash
streamlit run app.py
```

---

## Project Structure

```text
IPL-Analysis-Project/
│
├── IPL.csv
├── notebook/
│   └── IPL_Analysis.ipynb
│
├── images/
│   ├── team_wins.png
│   ├── top_run_scorers.png
│   ├── top_wicket_takers.png
│   ├── orange_cap_winners.png
│   ├── purple_cap_winners.png
│   ├── runs_per_season.png
│   └── team_heatmap.png
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Run Streamlit Dashboard:

```bash
streamlit run app.py
```

---

## Author

**Yash Bhardwaj**

Aspiring Data Analyst | Python | SQL | Machine Learning | Data Visualization
