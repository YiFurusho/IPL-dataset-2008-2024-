# IPL-dataset-2008-2024
Cricket Analytics Dashboard showing key stats like total runs, wickets, strike rate, and economy. Includes top 10 batsmen and bowlers, death overs (16-20) analysis, batsman vs bowler matchups, inning-wise performance, term trends, and extras impact. A beginner-friendly project for cricket data insights.

# Cricket Analytics Dashboard

Exploratory analysis and interactive dashboard for IPL cricket data (2008-2024).

## Project Overview

This project analyzes ball-by-ball IPL match data to reveal player performance patterns, team strategies, and match dynamics through interactive visualizations.

## Author Information

**Author:** I Furusho  
**Role:** Up Coming Data Analyst  
**Date:** 27/04/2025

## Dataset

**Source:** [IPL Complete Dataset (2008-2024)](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)  
**Description:** Contains ball-by-ball data, player statistics, and match details from 13 IPL seasons.

## Data Description

**Key Features:**

`total_runs` - Runs scored per ball  
`wicket` - Wicket-taking deliveries  
`strike_rate` - Batsman efficiency metric  
`economy_rate` - Bowler performance metric  
`over_number` - Match phase (1-20)  
`player_dismissed` - Batsman dismissal records

## Methodology

1. **ETL with Power BI:**
Used Power Query Editor for data cleaning and transformation (handled missing values, created calculated columns, categorized overs).
Loaded transformed data into Power BI Desktop for modeling.
Built DAX measures for key metrics (strike rate, economy rate).
Created interactive visualizations and dashboards for analysis.

2. **Analysis Focus:**  
   - Top performers (batsmen/bowlers)  
   - Team comparison metrics  
   - Batsman vs bowler matchups  
   - Extras impact analysis

## Data Cleaning

**Handled:**
- Missing player names → "Unknown"
- Negative economy rates → Data validation
- Duplicate ball entries → Removal

## Key Observations

**Batting Insights:**
- Strike rates increase dramatically in death overs
- Top batsmen show 140+ average strike rates

**Bowling Patterns:**
- Economy rates below 7.0 in powerplay
- Spinners dominate middle overs

**Team Strategies:**
- Wide variations in death over tactics
- Correlation between extras and match outcomes

## Figures

`assets/` contains:
- Strike rate distribution by over
- Top batsmen comparison radar chart
- Economy rate heatmaps

## Insights

**Key Insights**
1. **Death Overs (16-20) Are Crucial**
Teams that give away more than 10 runs per over in the last 5 overs lose most matches (around 7 out of 10).
Why it matters: Bowlers need to stay calm under pressure – small mistakes here cost big!

2. **Top 3 Batsmen Carry the Team**
The top 3 scorers in a team usually make nearly half of all runs.
What this means: Teams rely heavily on a few star players – if they fail, the team often struggles.

3. **Extras Add Up Quickly**
Every extra run (wides/no-balls) slightly increases the chance of losing.
Actionable tip: Bowlers should focus on accuracy – even 1-2 fewer extras per match can make a difference.

## Limitations
 
- **Missing Context:** Player fitness/weather data unavailable

## Image
![image alt](https://github.com/YiFurusho/IPL-dataset-2008-2024-/blob/0b685ca4f9e6fa32bd9526758b8543f2404782d8/Screenshot%202025-04-27%20182659.png)
![image alt](https://github.com/YiFurusho/IPL-dataset-2008-2024-/blob/e3971a61719360e476e98d27aeaf54582bfcd37c/Screenshot%202025-04-27%20182723.png)
![image alt](https://github.com/YiFurusho/IPL-dataset-2008-2024-/blob/73e10b261844a06bdb2f9e9e8dd5ce1daaeec02a/Screenshot%202025-04-27%20182740.png)










