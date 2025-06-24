# Analysing custommer churn in Power BI

## Table of Contents  
[Project Overview](#project-overview)  
[Data Sources](#data-sources)  
[Data Transformation](#data-transformation)    
[Findings](#findings)  
[Recommendations](#Recommendations)  
[Limitations](#Limitations)

### Project Overview
Customer churn is the rate of customers leaving the business. This Power BI project focuses on analyzing customer churn patterns to help businesses understand why customers leave and identify opportunities for retention.

### Data Sources

[Databel-Data.csv](https://github.com/riteshgogade/Analysing-Customer-Churn-in-Power-BI/blob/main/Databel%20-%20Data.csv)

### Data Transformation
1. Removal of duplicate and null customer records.
2. Categorisation of customers into 3 groups as per age (Under 30, Above 60, Other) and 3 groups as per data consumption (0 to 5 GB, 5 to 10 GB, More than 10 GB).
3. Creation of measures for churn calculations.

### Findings
1. Month-to-month contracts have the highest churn rate of 51%.
2. Customers older than 60 show higher churn of 30% and keep on increasing gradually through age.
3. Non-group contracts have more churn of 32% against 6% of group contracts.
4. Monthly contract with paper check payment method has highest churn of 57% and lowest average contract length of 8 months while yearly contract with credit card payment have highest average contract length of 46 months and lowest churn of 4%.
5. Customers with monthly payment contracts with direct debit had on average 1.4 calls per customer.
6. Customers with unlimited plan consuming less than 5 GB per month have the highest churn of 34%.
7. Consumers with limited plan consuming more than 10 GB end up paying 31$ extra on average.
8. California has the highest churn but the average customer call duration (0.65 mins) is less than the corresponding total average (0.92 mins). 

### Recommendations
1. Urging customers to other contract types (1 year, 2 year) might reduce churn.
2. Payment mathod for direct debit monthly contracts might have solve some problem leading to higher customer calls.
3. Customers from California can be contacted for finding out churn reason or more marketing campaigns can be encouraged in the state.

### Limitations
The data is static in nature and does not showcase how customers left business wrt time. 


