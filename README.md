# Sakhigbe Resources Sales Analysis

## Table of Content
 [Project Review](#project-review)
 
 [Data Source](#data-source)
 
 [Tools Used](#tools-used)
 
 [Data cleaning and Preparation](#data-cleaning-and-preparation)
 
 [Exploratory Data Analysis](#exploratory-data-analysis)
 
 [Data Analysis](#data-analysis)
 
 [Charts](#charts)
 
 [Results&Findings](#results-findings)
 
 [Recommendations](#recommendations)
 
 
 
 
 
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

  h. what is the models sold with the highest revenue

  i. what is the total unit sold by month

  j. what day categories has the highest revenue

  k. what is the total revenue by sale categories

  l. which line of business recorded the highest revenue
  
## Data Analysis
---
'''
Excel
=IF(M2<=20,"Low", IF(M2<=50, "Medium", IF(M2>50, "High")))
'''

## Charts

[Pivot Tables File.xlsx](https://github.com/user-attachments/files/17356846/Pivot.Tables.File.xlsx)

## Results&Findings
  - the top 5 markets by revenue are Ekiti, Abia, Bayelsa, Akwa Ibom and Kogi
  - the top 10 stores are;
    - Ankpa
    - Ajaokuta
    - Arochukwu
    - Ekiti South-West
    - Nembe
    - Ekiti East
    - Ado-Odo/Ota
    - Dukku
    - Bauchi
    - Askira/Uba

  - the total revenue by region is  ₦ 73,031,990,280
  - the bottom 5 stores by unit sold are; Boki, Kwali, Chibok, Isiala Ngwa South, Akinyele
  - company revenue by month is same as total revenue by region with March having the highest revenue of ₦ 8,458,780,440 for the years under review
  - 2014 had the highest total sales and percentage of ₦ 48,464,608,200 which accounts for 66% of the total sales and 2015 had ₦ 24,567,382,080 which accounts for 34% of the total sales
  - Quarter 1 accounted for the highest sales with ₦ 24,538,923,000 which is 33.6% of the total revenue
  - Model 3002P has the highest revenue of ₦ 26,213,998,800 which is 35.89% of the total revenue
  - June had the highest unit sold for the months under review with 90,022 units
  - "workday category" had the highest revenue of ₦ 69,049,294,920 which accounts for 94.55% of the total revenue
  - Total revenue by sales categories is;
      High	₦ 16,032,449,520
      Low	₦ 26,476,629,720
      Medium	₦ 30,522,911,040
      Grand Total	₦ 73,031,990,280
  - "service plan" line of business recorded the highest revenue with a total of ₦ 51,866,481,960 accounting for 71.02% of the total revenue

## Recommendations
  - invest in product awareness in Boki and Kwali to improve patronage and sales
  - introduce promotional activities in the North central to attract more people to the product and enhance sales and revenue
  - get more professionals or organize on the job training for sales reps in the copier sales, parts and printer sales line of business to improve performance and productivity
  - give incentives to staff in the service plan line of business to encourage them and also challenge others to improve
  - create more awareness on product models with low revenue and consider dropping them entirely where no improvement is forthcoming after 2 months of intense awareness








