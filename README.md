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

### Data preprocessing
Encode the Data <br />
![image](https://user-images.githubusercontent.com/107438816/203438047-eed47b4b-2917-4927-ac5a-ea3a55b7883d.png)
Scale the Data <br />
![image](https://user-images.githubusercontent.com/107438816/203438182-c7490620-013d-4045-8f6f-ea13a3ea56b1.png)



Feature selection
How data was split into training and testing sets
Model choice, including limitations and benefits
Changes in model choice
Description of how model was trained (or retrained, if they are using an
existing model)
Description and explanation of model’s confusion matrix, including final
accuracy score

![image](https://user-images.githubusercontent.com/107438816/203433372-3be51e14-44f5-4646-8703-9735c11fb18b.png)

![image](https://user-images.githubusercontent.com/107438816/203433466-069a3d3a-bc31-4786-988d-de22843881e2.png)

![image](https://user-images.githubusercontent.com/107438816/203433522-c71f34a8-6dcb-45d3-8d79-206b9b6f92fe.png)

![image](https://user-images.githubusercontent.com/107438816/203433573-613ff3a4-3172-4f4f-bace-a8fe25e36ca3.png)

## ML Finding #1
9 companies receive half of all US Energy Contract Awards.
Counterintuitively, smaller awardees demonstrate a higher correlation with Natural Gas prices.

## Recommendation
Further exploratory analysis into company and contract details
“How do these companies differ from competitors?”
“Why do the 9 companies receiving  50% of all awards not appear on the top 10 feature list?”

![image](https://user-images.githubusercontent.com/107438816/203433678-c0fa23a7-20d8-4049-9bda-442a6e8ede80.png)

![image](https://user-images.githubusercontent.com/107438816/203433736-94e41b02-60b2-4724-880c-a95228258ed8.png)

## ML Finding #2
The ‘Crushed and Broken Limestone Mining and Quarrying’ industry demonstrates a consistent feature correlation to US natural gas prices in our machine learning models.

## Recommendation
In depth research analysis on correlations between Natural Gas and Limestone Industries for future models.

![image](https://user-images.githubusercontent.com/107438816/203433808-d75a5da6-529b-4a77-a7ab-fc0c4871c717.png)

 
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

## Link to website
[Our website link](https://saidakramov.github.io/Group_2_website/)
