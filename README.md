# NBA Scoring Analysis

This project investigates how a player’s height and age impact their scoring performance in the NBA. Using real-world NBA season statistics, we conducted an exploratory data analysis to uncover trends and patterns in scoring output based on physical and demographic variables

## Overview

In the NBA, scoring ability is a core metric used to assess player value, performance, and potential. However, it’s often assumed that taller players or younger, more athletic players naturally score more. This project challenges those assumptions by asking:
- Do taller players actually score more points per game?
- At what age are NBA players in their scoring peak?
- Is there an optimal combination of height and age for maximizing scoring output?

We cleaned and analyzed a multi-season dataset of NBA player statistics using R. Through visualizations and statistical summaries, we drew evidence-based conclusions to these questions. The results help contextualize how physical traits (like height) and player development stages (like age) relate to actual on-court performance.

### Interesting Insight

One of the most compelling findings was that height does not strongly correlate with scoring. In fact, many of the league’s top scorers fall within a moderate height range, between 6’3” and 6’7”. These players, often guards or wing players, tend to have more offensive control and scoring opportunities.
Additionally, players peak in scoring between the ages of 26 and 28, highlighting a blend of physical prime and in-game maturity.
Below is a heatmap that visualizes the scoring “sweet spot” across both height and age:
![Screenshot 2025-05-05 at 10 14 47 PM](https://github.com/user-attachments/assets/c25b619c-ace1-4abc-ad97-e96e1a1a9c99)

## Repo Structure

This repository includes all components necessary to reproduce and review our STAT 184 Final Project analysis. Below is a description of each file:
- nba_scoring_analysis_final.qmd- The main Quarto file containing our full analysis, including code, visuals, and narrative.
- NBA Scoring Analysis.pdf – The final rendered PDF report for submission, generated from the .qmd file.
- all_seasons.csv – The raw dataset used for the analysis, containing multi-season NBA player statistics.
- README.md – This document, providing an overview of the project, repo structure, and key insights.
- Project_Guidelines.md – A copy of the STAT 184 course project guidelines for easy reference.


## Data Sources and Acknowledgements

This project relies on publicly available data and academic tools. We’d like to acknowledge the following:
Dataset: Justinas. “NBA Players Data.” Kaggle, 2023.
https://www.kaggle.com/datasets/justinas/nba-players-data
R Packages Used:
- 	tidyverse for data manipulation and visualization
- 	ggplot2 for elegant and powerful plotting
- 	 nitr and quarto for reproducible reporting

## Authors

Varun Gullanki, Anirudh Ganesan, Zezhou Zhuang. 
If you have further questions please contact vsg5067@psu.edu.
