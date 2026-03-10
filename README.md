# IPL 2022 Data Analysis and Visualization

This project analyzes match data from the Indian Premier League (IPL) 2022 season using Python.  
The goal of this analysis is to explore patterns in team performance, match outcomes, 
and venue characteristics through data analysis and visualization.

## Project Overview

The dataset contains match-level information from the IPL 2022 season, including match results, 
venues, toss decisions, player awards, and scoring details.  
Using Python libraries such as Pandas and Matplotlib, the data was cleaned, 
analyzed, and visualized to generate meaningful insights.

## Key Insights

**1. Toss Impact**

Winning the toss did not significantly influence match outcomes.  
Teams that won the toss won the match approximately **48.65% of the time**, suggesting that 
overall match performance had a greater impact than toss advantage.

**2. Venue Analysis**

Eden Gardens (Kolkata) recorded the highest average first innings score during the 2022 season, 
indicating that it was one of the more batting-friendly venues.

**Top Performances**

The analysis highlights strong performances from players such as **Jos Buttler** and **Yuzvendra Chahal**, who featured prominently in batting and bowling statistics.

**Match Result Trends**

Match results were analyzed to understand whether teams were more successful chasing targets or defending totals.  
The distribution of wins by runs and by wickets provides insight into match strategies during the season.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure
ipl-2022-data-analysis

├── data
 └── IPL.csv

├── notebook
 └── ipl_analysis.ipynb

├── images
 └── visualizations generated during analysis

├── README.md
└── requirements.txt


## How to Run the Project

1. Clone the repository
2. Install the required libraries

pip install -r requirements.txt

3. Open the notebook
jupyter notebook

4. Run `ipl_analysis.ipynb`
