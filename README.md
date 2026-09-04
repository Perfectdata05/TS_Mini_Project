# TS_Mini_Project

### Project Title : E commerce Sales Analysis

### Project Overview
---
This project focuses on developing an interactive Sales and Customer Analytics Dashboard using Power BI to provide a comprehensive view of business performance. The dashboard analyses key performance indicators including revenue, cost, profit, sales, and customer performance.
The analysis explores brand profitability, product purchasing patterns, customer acquisition trends, income-level segments, and regional performance. Interactive filters allow users to analyse the data by product category and customer region, making it easier to identify trends, performance variations, and areas that require business attention.
The project demonstrates the use of data preparation, data modelling, DAX, Power BI visualisation, and interactive dashboard design to transform business data into meaningful insights for data-driven decision-making.

### Data Sources
---
This primary source of Data used here is Excel dataset Sale.xlsx and this is an open source data that can be freely download from an open source online such as Kaggle or any other data repository site.

### Tools Used
---
- **PowerBI** *[Download Here](https://www.microsoft.com)*
   1.  Power Query for Data Cleaning
   2.  Data modelling and DAX calculations to create the required KPIs and analytical measures.
   3.  Visualizations
- Github for Portfolio Building

## Data Cleaning And Preparations
---
In the initial phase of the Data cleaning and preparations, we perform the following action;
1. Data loading and Inspection
2. Handling missing Variables
3. Data Cleaning and formatting

#### Exploratory Data Analysis
---
EDA involved the exploring of the Data to answer some questions about the Data such as:
  - Which brand of product is the most profitable
  - Which colour is top sellers
  - which is the worst performing month?
  - Which level of income has the highest profit?
  - What is the yearly revenue?

### Data Analysis 
---
 This is where include some basic lines of code or even some of the DAX expressions used during your analysis;
 
 ```DAX
Total Sales =
SUM(Sales[SalesAmount])

Total Cost =
SUMX(
    Sales,
    Sales[Quantity] * Sales[Unit Cost])

Profit =
[Total Sales] - [Total Cost]

Total Customers =
DISTINCTCOUNT(Sales[CustomerID])
```
