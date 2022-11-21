# Group-02-UCB
Project Repository for the final project. 

## Table of Contents

1. [Team Members](#team-members)

2. [Question](#question)

3. [Project Summary](#project-summary)

4. [Data Sources](#data-sources)

5. [Tools](#tools)

6. [Task Breakdown](#task-breakdown)

 
## Team Members
#### Rohan Arun - Project Manager
#### Jigisha Bengali - Database Designer
#### Ryan Chapman - Machine Learning Engineer
#### Andrew In - Data Analyst
#### Akbar Saidakramov - Web Developer

## Question
Government Spending Analysis: 
How does the US government spending contracts correlate to the natural gas prices?

## Project Summary
Using Government Spending Contracts API to visualize and identify trends compared to natural gas prices.

## Project Outline 
<img width="1408" alt="Project Outline" src="https://user-images.githubusercontent.com/89552059/201586595-5146f804-204e-46db-9401-866a113f01ec.png">

## Why it's important?
The government and its spending are essential to us as taxpayers, and we want to analyze/visualize the government's expenditure to help improve or understand the reason prices of certain items fluctuate. Natural gas is a non-renewable source of energy, it is important as we use it on a daily basis in our households in places like our stove and the heating of our houses. It is a crucial source of energy because it is reliable (there are rarely any outages in a year) and it is also relatively clean compared to other non-renewable sources of energy such as coal and oil.

# Data Analysis
## Input Data
### US Government Energy Award Contracts (2016-2021)
  Source: USASPENDING.gov
  Description: US Government website that links data from many government systems, including agency financial systems and governmentwide award systems.<br />
  Subdata: Contract Recipient, Awarding Agency, Amount, NAIC,  SIC

### Historical Raw Material Market Prices (Pink Sheet)
  Source: UN associated international financial institution. <br />
  Description: UN associated international financial institution.

## Machine Learning
Model: XGBoost
N-Estimators:
Training Score:
Testing Score:
Mean Squared Error (MSE) on test set:
Results: 

Model: RandomForrest
N-Estimators: 700
Training Score: 0.4014
Testing Score: -0.0782
Mean Squared Error (MSE) on test set: 0.5155
Results:

 
## Tools, Technologies, & Languages
- Excel
- PostgreSQL
- SQL
- Python
- Pandas
- Matplotlib
- NumPy
- SciPy
- Tableau
- SQL Alchemy
- HTML

## Task Breakdown
Ryan Chapman: Setting up APIs, Webpage, Pandas/Tableau, Machine Learning Modules 6, 10,13, 17/18 ish

Rohan: Pandas/Repository management/Tableau 1, 2, 3 ,4, 5, 14, 15, 16

Jigisha Bengali: Collect/Clean the data, Created Join Tables, Top_20 queries, Python: 4,7 & 8 (SQL, Pandas,ETL)

Andrew: Dashboard, slides, Python, 1, 2, 3, 4, 5, 7(ish), 14

Akbar: Databases, SQL, Pandas, JavaScript, CSS, HTML


## Link to slides
https://docs.google.com/presentation/d/1BtSJ0rQH5krcPL6SDq5D2viGjvZ8zvCgHsRkYwpSSaE/edit?usp=sharing
