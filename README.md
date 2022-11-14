# Group-02-UCB
Project Repository for the final project. 

## Table of Contents

1. [Team Members](#team-members)

2. [Question](#question)

3. [Project Summary](#project-summary)

4. [Data Sources](#data-sources)

5. [Tools](#tools)

6. [Task Breakdown](#task-breakdown)

7. [Communication Methods](#communication-methods)
 
## Team Members
#### Rohan Arun
#### Jigisha Bengali
#### Ryan Chapman
#### Andrew In
#### Akbar Saidakramov

## Question
Government Spending Analysis: 
How does the US government spending contracts correlate to the natural gas prices?

## Project Summary
Using Government Spending Contracts API to visualize and identify trends compared to natural gas prices.

## Project Outline 
<img width="1408" alt="Project Outline" src="https://user-images.githubusercontent.com/89552059/201586595-5146f804-204e-46db-9401-866a113f01ec.png">

## Why it's important?
The government and its spending are essential to us as taxpayers, and we want to analyze/visualize the government's expenditure to help improve or understand the reason prices of certain items fluctuate. Natural gas is a non-renewable source of energy, it is important as we use it on a daily basis in our households in places like our stove and the heating of our houses. It is a crucial source of energy because it is reliable (there are rarely any outages in a year) and it is also relatively clean compared to other non-renewable sources of energy such as coal and oil.

## Data Sources
 - Commodity Market Data Montly: www.worldbank.org/en/research/commodity-markets
 - US Fed Spending API: https://api.usaspending.gov/api/v2/search/spending_by_award
 
## Data Exploration
- Our team used Python to merge (contracts.csv) and (prices.csv) into a DataFrame. We then cleaned the data and trimmed row outputs to get the essential information relevant to our question. We exported the relevant information into new csvs after reducing the data from approximately 10,000 rows to 1,500 relevant rows. 

## Data Analysis & Visualization
- We used matplotlib, scipy, and numpy to create plots and linear regressions between awarded government contracts and US natural gas prices.

### Description of the Data Source
 -Comparing federal contracts spending for natural gas to the natural gas index. 
 
## Tools
- Python
- Pandas
- Matplotlib
- NumPy
- SciPy
- Tableau

## Task Breakdown
Ryan Chapman: Setting up APIs, Webpage, Pandas/Tableau, Machine Learning Modules 6, 10,13, 17/18 ish

Rohan: Pandas/Repository management/Tableau 1, 2, 3 ,4, 5, 14, 15, 16

Jigisha Bengali: Collect/Clean the data, Python: 4,7 & 8 (SQL, Pandas,ETL)

Andrew: Dashboard, slides, Python, 1, 2, 3, 4, 5, 7(ish), 14

Akbar: Databases, SQL, Pandas 3,4,5,6,7,8,9,13,16,17

## Communication Methods
Slack, Email, iMessage, 3 days a week general meetup via Zoom and discuss tasks/deliverables.

## Link to slides
https://docs.google.com/presentation/d/1BtSJ0rQH5krcPL6SDq5D2viGjvZ8zvCgHsRkYwpSSaE/edit?usp=sharing
