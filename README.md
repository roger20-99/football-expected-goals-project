# Final Project Title

## Introduction

This project concerns football and statistics, specifically expected goals. This is a new concept for someone who watches the sport for more than 10 years. I decided to take a closer at how this statistic impact each club's performance per season based on the number of chances they create and number of goals they actually score. 

In a low-scoring sport such as football, the final score alone is not a true reflection of how the game unfolds. This is why sports statisticians turn to model like expected goals to measure the quality of chances created and conceded in each game. The following report covers the entire season for 6 of European's most elite football leagues: England, Italy, Spain, Germany, France, and Russia

## Data Dictionary

| Field | Description |
| :--- | :--- |
| league | Name of the domestic leagues |
| year | Year that the season start |
| date | Date of the game |
| team | Name of the football club |
| h_a | Home or Away games |
| scored | Goals scored |
| missed | Goals conceded |
| result | Result of the game for the team |
| pts | Points gained (3 for a win, 1 for a draw, 0 for a loss) |
| xG | Expected goals |
| xGA | Expected goals against/conceded |
| npxG | Expected goals scored without penalties and own goals. |
| npxGA | Expected goals against without penalties and own goals |
| xpts | Expected points in that game |
| npxGD | Difference between "for" and "against" expected goals without penalties and own goals. |
| xG_diff | Difference between actual goals scored and expected goals |
| xGA_diff | Difference between actual goals missed and expected goals against/conceded |
| xpts_diff | Difference between actual and expected points |
## Important Links

* [Final Report Notebook](report.ipynb)
* [EDA Notebook](eda.ipynb)
* [Link 1](https://www.goal.com/en-us/news/what-is-xg-football-how-statistic-calculated/h42z0iiv8mdg1ub10iisg1dju#:~:text=Return%20to%20top-,How%20is%20xG%20calculated%3F,what%20informs%20its%20xG%20rating.) - An article on Goal.com that explains about expected goals and how it is calculated
* [Link 2](https://understat.com/) - This website contains the original source of data I've used for the project
* [Link 3](https://theshortfuse.sbnation.com/2017/11/15/16655916/how-to-calculate-xpoints-analysis-stats-xg) - This website explains about how expected points per match can be calculated based on the statistics of expected goals
