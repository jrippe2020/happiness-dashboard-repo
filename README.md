# Happines Dashboard (Interactive LookerStudio/DataStudio Dashboard)  
## **Background & Rationale:** 
This project explores factors that influence happiness around the world using both the World Happiness Report (scraped from this [site](https://data.worldhappiness.report/table)) and my own happiness dataset collected over 9 months. This dashboard is designed to allow you to explore trends in how different countries rank for predictors of happiness around the world. Additionally, this dashboard includes a tab exploring my own habits and how they've contributed to my happiness ratings. I hope this dashboard is as fun to play around with as it was to build - Happy Visualizing! 

**Data Sources:** World Happiness Report, my own happiness dataset 

**Date Range:** 
* World Happiness Report: 2015-2025 (score refresh = annual)
* My happiness dataset: July 2025-March 2026 (score refresh = daily)

## **Project Objectives:** 
1. To analyze factors that influence happiness ranking of countries included in the WHR (global factors) 
2. To analyze the impact of different habits on my own happiness score (individual habits)

## **Questions Explored (KPIs)**
*World Happiness Report*
- What are the top and bottom happiest countries on average over the last 10 years?
- What countries & regions rank the highest for caring behavior?
- How satisfied are respondents with their lives (scale of 0-10) on average in different regions?
- Which countries are ranked number 1 for each of the following categories: Inequality,	Social support,	GDP per capita,	Healthy life expectancy, Freedom,	Generosity,	Perception of corruption,	Positive emotions,	Negative emotions,	Donated,	Volunteered, &	Helped a stranger?

*My dataset*
- How consistent was I with each habit?
- What was my average happiness rating on days when I practiced each habit?
- How did my happiness rating change over time?

## Process
*WHR*
- Scrape rankings data from 2015-2025 from the World Happiness Report site
- Clean the data: identify nulls, outliers, and formatting issues and resolve; QCing with original site
- Add columns mapping countries to regions, subregions, and intermediate regions
- Connect GSheet to DataStudio dashboard and build dynamic charts to answer the questions stated above
- QC dashboard with underlying GSheet 

*My dataset*
- Clean the data: identify nulls & outliers and QC with original paper trackers
- Connect GSheet to DataStudio dashboard and build dynamic charts to answer the questions stated above
- QC dashboard with underlying GSheet

## Dashboard: Example View
- Filtering for Region = Americas OR Europe <a href="https://github.com/jrippe2020/happiness-dashboard-repo/blob/main/Happiness_Dashboard.pdf">View Dashboard</a>

### ***BONUS:*** 
If you found this dashboard interesting, I have a longer analysis pulling out some key trends from these data and providing a predictive model on what drives happiness! Check out my Google Colab Notebook for the analysis [here](https://github.com/jrippe2020/happiness-python-analysis-repo).
