# Sales-Insights_Data-Analysis-using-SQL-and-PowerBI
## Problem Statement:
AtliQ Computer Hardware and peripherals manufacturer is facing issues with sales analysis. The sales director is not able to get useful information from the company sales dataset. Therefore, data analysis and a dashboard are required to get Sales insight so that the sales director can make data-driven decisions.

## Data Processing:
It is a structured dataset in SQL format. Following data preprocessing is made
1. Completed Data Model – Star Schema 
2. Removed rows with incomplete data from the sales market 
3. Removed outliers (–1 and 0) from sales transaction - sales amount 
4. Normalized all sales_amount in the same currency

```sql   
SELECT * FROM sales.transactions order by sales.transactions.sales_amount ASC limit 15;
```

## Data Visualization
The dashboard is made in Microsoft PowerBI to get Sales insight. This dashboard can be deployed on websites and mobile devices. 

The following useful information is extracted from the dashboard.
1. From 2019 to 2020, the Profit margin % of the Delhi market has drastically reduced from 3.1 to 0.6 respectively.
2. Delhi has generated maximum Revenue but the Profit Margin Contribution % is lower than Mumbai in 2020.
3. Lucknow generated a maximum Profit margin % in 2019 but it has now become negative in 2020. 
4. Only one customer is generating 46% of Revenue for the company.
5. Overall the Revenue trend is declining with time.

## Dashboard View
### First Page:
![PowerBIFile_001](https://github.com/alishafique3/Sales-Insights_Data-Analysis-using-SQL-and-PowerBI/assets/17300597/a6cca4de-1cb7-4caa-9f40-3342cf8ae51a)
### Second Page:
![PowerBIFile_002](https://github.com/alishafique3/Sales-Insights_Data-Analysis-using-SQL-and-PowerBI/assets/17300597/4b8024e6-acd1-4b4b-97ac-7cb45ece820c)

## Acknowledgement
I would like to acknowledge the YouTube channel **codebasics** and website https://codebasics.io/ by Dhaval Patel for guidance on this project.
