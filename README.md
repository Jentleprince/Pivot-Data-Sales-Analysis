# Sakhigbe Resources Sales Analysis
## Project Review
---
This data analysis project aim to give an insight on the sales performance of Sakhigbe Resources over a period of 2 years (2014 & 2015). By analyzing the various aspects of the sales data, we intend to find trends, make data - driven recommendations and also get a deeper understanding of the company's performance with regards to revenue and units sold in various regions, market, store, model etc.

## Data Source
---
The primary data source used for this analysis is the "Pivot Table Data xlsx" file containing detailed information of the sales made by the company from the region, market, stores etc.

## Tools Used
---
- Ms Excel - used for data cleaning [download here "https://microsoft.com)
- Pivot Table - used for data summarization
- Excel Dashboard - used for data visualization

## Data cleaning and Preparation
---
  in the course of preparing this data set for analysis, the following was done;
  1. Data loading and inspection
  2. categorization of unit sold into "High", "medium" and "low" using the "if" condition
  3. separated the trade date into day, month and year for proper analysis and inference
     
## Exploratory Data Analysis
---
  a. What are the top 5 Market by Revenue	
  
  b. what are the top 10 Stores by Revenue
  
  c. what is the total Revenue by Region	
  
  d. which are the bottom 5 stores by Unit Sold	
  
  e. what is the company's revenue by Month	

  f. what is the sales and percentage total per year

  g. which quarter has the highest revenue

  h. what is the revenue by models sold

  i. what is the total unit sold by month

  j. what is the total revenue by day categories

  k. what is the total revenue by sale categories

  l. which line of business recorded the highest revenue
  
## Data Analysis
---
'''
Excel
=IF(M2<=20,"Low", IF(M2<=50, "Medium", IF(M2>50, "High")))
'''
