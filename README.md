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
#### <a href="https://github.com/WeirdFishez"> Ryan Chapman - Machine Learning Engineer </a>
#### Andrew In - Data Analyst
#### Akbar Saidakramov - Web Developer

## Question
How does US Federal award contract spending impact natural gas prices?

## Project Summary
Exploratory analysis using publically availible federal award contract data to identify and visualize correlations with historic US natural gas prices.

## Project Outline 
<img width="1408" alt="Project Outline" src="https://user-images.githubusercontent.com/89552059/201586595-5146f804-204e-46db-9401-866a113f01ec.png">

## Why it's important?
The government and its spending are essential to us as taxpayers, and we want to analyze/visualize the government's expenditure to help improve or understand the reason prices of certain items fluctuate. Natural gas is a non-renewable source of energy, it is important as we use it on a daily basis in our households in places like our stove and the heating of our houses. It is a crucial source of energy because it is reliable (there are rarely any outages in a year) and it is also relatively clean compared to other non-renewable sources of energy such as coal and oil.

# Data Analysis
### Feature Data: US Federal Award Contract Spending in Energy (2016-2021)
 - Source: <a href="https://www.usaspending.gov/search/?hash=96e9318d4713b23d03e6f45310388055">USASPENDING.gov</a><br />
 - Description: US Government website that links data from many government systems, including agency financial systems and governmentwide award systems.<br />
 - Subdata: Contract Recipient, Awarding Agency, Amount, NAIC,  SIC<br />
 - Fed Energy Contract Spending (2016-2021) by Award Recipient

  **Subdata: Awarding Agency**<br />
![image](https://user-images.githubusercontent.com/107438816/203439363-e03fcbb8-4185-43eb-a30d-3c348a4f836e.png)
<br /><br />
  **Subdata: Award Recipient**<br />
![image](https://user-images.githubusercontent.com/107438816/203439217-341eec48-3446-4b19-a3b1-3c4bfc753291.png)
<br /><br />
  **Subdata: North American Industry Classification System (NAICS)**
 - System used by Federal statistical agencies in classifying business establishments for the purpose of collecting, analyzing, and publishing statistical data related to the U.S. business economy.<br />

![image](https://user-images.githubusercontent.com/107438816/203439412-effbae38-2a16-4416-9cc2-363a208e44e5.png)
<br /><br />
  **Subdata: Product Services Code (PSC)**
 - Categorizing codes to describe products, services, research and development (R&D) purchased by the Federal government. <br />

![image](https://user-images.githubusercontent.com/107438816/203439434-1d0f0aae-b54a-44a7-9870-f788bf3646dc.png)<br /><br />


### Target Data: Historical US Natural Gas Prices
 - Source: <a href="https://www.worldbank.org/en/research/commodity-markets"> World Bank Commodity Market Data </a> "Pink Sheet" <br />
 - Description: UN associated international financial institution.<br />
  ![image](https://user-images.githubusercontent.com/107438816/203439851-312217f5-2d95-419a-8799-95cdae5a6991.png)

  
## Machine Learning

### Data Preprocessing: Encode the Data
![image](https://user-images.githubusercontent.com/107438816/203438047-eed47b4b-2917-4927-ac5a-ea3a55b7883d.png) <br /><br />
### Data Preprocessing: Scale the Data
![image](https://user-images.githubusercontent.com/107438816/203438182-c7490620-013d-4045-8f6f-ea13a3ea56b1.png)


### Model: Random Forest Regression
 - Result Summary: This model scored a MSE of 0.5426 with target prices ranging from 5.11 to 1.61. After printing our the top 10 features list, we highlighted the awardees in the overall data and noticed that while 9 companies received 50% of the funding, none of these companies had high feature impact. Because Random Forest is not the most sophisticated model, we then tried a boosting model next.
![image](https://user-images.githubusercontent.com/107438816/203445005-b2e73d54-21ee-46d4-9438-c48fbff86e97.png)
<br />
![image](https://user-images.githubusercontent.com/107438816/203444741-c2886ce0-9c12-438f-90e9-532a81293316.png)

### Model: Extreme Gradient Boost
 - Result Summary: This model scored a MSE of 0.5426 with target prices ranging from 5.11 to 1.61. After printing our the top 10 features list, we highlighted the awardees in the overall data and noticed that while 9 companies received 50% of the funding, none of these companies had high feature impact. Because Random Forest is not the most sophisticated model, we then tried a boosting model next.

![image](https://user-images.githubusercontent.com/107438816/203444941-ca33565d-4094-449b-9ae9-7c8fd3f150fe.png)
<br />
![image](https://user-images.githubusercontent.com/107438816/203444883-e7ec1faa-5c81-4cba-b8eb-3eedf7fbbef1.png)

### ML Finding #1
9 companies receive half of all US Energy Contract Awards.<br />
Counterintuitively, smaller awardees demonstrate a higher correlation with Natural Gas prices.<br />

### Recommendation
Further exploratory analysis into company and contract details<br />
“How do these companies differ from competitors?”<br />
“Why do the 9 companies receiving  50% of all awards not appear on the top 10 feature list?”<br />

![image](https://user-images.githubusercontent.com/107438816/203433678-c0fa23a7-20d8-4049-9bda-442a6e8ede80.png)

![image](https://user-images.githubusercontent.com/107438816/203433736-94e41b02-60b2-4724-880c-a95228258ed8.png)

### ML Finding #2
The ‘Crushed and Broken Limestone Mining and Quarrying’ industry demonstrates a consistent feature correlation to US natural gas prices in our machine learning models.<br />

### Recommendation
In depth research analysis on correlations between Natural Gas and Limestone Industries for future models.<br />

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
Ryan Chapman: Setting up APIs, Data Cleaning with Pandas, Visualization with Tableau, Machine Learning with Python

Rohan: Pandas/Repository management/Tableau 1, 2, 3 ,4, 5, 14, 15, 16

Jigisha Bengali: Collect/Clean the data, Created Join Tables, Top_20 queries, Python: 4,7 & 8 (SQL, Pandas,ETL)

Andrew: Dashboard, slides, Python, 1, 2, 3, 4, 5, 7(ish), 14

Akbar: Databases, SQL, Pandas, JavaScript, CSS, HTML


## Link to slides
https://docs.google.com/presentation/d/1BtSJ0rQH5krcPL6SDq5D2viGjvZ8zvCgHsRkYwpSSaE/edit?usp=sharing

## Link to website
[Our website link](https://saidakramov.github.io/Group_2_website/)
