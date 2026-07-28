# Sales Analysis

### Table of contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data CleaningPreparation](#data-cleaningpreparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis/Key Findings](#data-analysiskey-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)



### Project Overview

This data analysis project aims identifying peak sales periods, determining top-performing products, evaluating profitability drivers, and recommending operational improvements.

<img width="634" height="354" alt="Fast Food Dashbaord" src="https://github.com/user-attachments/assets/2b47b50d-2b76-4db3-ae37-40d06f88e9f8" />




### Data Sources

Sales Data: The Primary dataset used for this analysis is the "restaurant_sales_data.xlsx" file, containing detailed information about each sale made by the company
### Tools

- Excel 
  - [Download Here](https://docs.google.com/spreadsheets/d/1h6teNTG8KtBPpWFASK0iwJMhXwcXeCoo/edit?usp=drive_link&ouid=113380697195263828971&rtpof=true&sd=true)
 
### Data Cleaning/Preparation

In the initial data preparation phase, the following tasks were performed:
  1. Data loading and inspection.
  2. Handling Outlier.
  3. Data cleaning/ Formatting/ transformation.

### Exploratory Data Analysis

EDA involves exploring the sales data to answer key questions, such as:

 - What is overall sales trend?
 - Which products are most profitable?
 - What are the peak sales periods?

### Data Analysis/Key Findings

1. Fast Food is the best performing categories in terms of revenue and profit.
   - Fast Food contributed 39% of Revenue but lowest margin. Desserts being the lowest in revenue generation, had 54% margin.
2. Evening periods experienced the highest customer traffic.
   - 51% of total revenue came from evenng transactions
3. Dine-in orders has the highest profit margin compared to delivery orders and Takeaway orders.
  - Reasons:
    - Delivery fees
    - Packaging costs
    - Discounts
4. Long Wait times Reduced Customer Satisfaction.
   - Average waiting above 21 minutes caused poor ratings
5. Some Popular Products like Shawarma, Smoothie, and Ice Cream Were Less Profitable.
   - High ingredients costs reduced profit margins

### Recommendations

Based on the analysis, we recommend the following actions:
1. Reduce Wait Time
   - Increase evening staff
   - improve kitchen workflow
2. Improve Menu Profitability
   - Increase price slightly on low-margin products
   - Promote high-profit meals 
3. Increase Customer Retention
   - Introduce loyalty rewards
   - Improve delivery efficiency
  
### Limitations
I had to clean product and Category fields which had inconsistency, misspelt values and leading spaces and  outlier in the quantity field replaced with median value because they have affected the accuracy of the analysis.
