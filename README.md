# Retail-Customer-Analytics-Dashboard

## Project Overview
This project analyzes online retail transaction data to uncover revenue trends, customer purchasing behavior, and product performance.

Using SQL, Python, and Tableau, I built an analytics pipeline to transform raw transaction data into actionable business insights, including monthly revenue trends, top-performing products, customer rankings, and RFM customer analysis.

This is a **personal data scienc projects** completed to gain hands-on experience with real-world transactional data beyond coursework.

## Dashboard Preview
![Retail Analytics Dashboard](/dashboard.png)

## Objectives

The goal of this project was to answer key business questions:

- How does revenue change over time?
- Which products generate the most revenue?
- Which customers contribute the most to overall sales?
- How can customers be categorized based on purchasing behavior?
  
## Dataset
- **Source:** Online Retail Transaction Dataset
- **Description:** This is a transactional dataset containing all transactions occuring between **01/12/2010 and 09/12/2011** for a **UK-based, registered, non-store online retail business**.
- **Contents:** Invoice numbers, product codes and descriptions, quantities, unit prices, customer IDs, countries, and transaction timestamps
- **Size:** ~540,000 transactions

## Data Processing

The raw transaction data was cleaned and transformed before analysis:

- Removed missing customer IDs
- Removed invalid transactions
- Converted invoice dates into datetime format
- Created revenue features:
    - Revenue = Quantity × Unit Price
- Aggregated transaction-level data into customer and product-level summaries

## Key Findings
- A **small percentage of customers** contributes a disproportionately large share of total revenue.
- Revenue is also highly concentrated among a **small subset of products**.
- Concentration remains persistently high over time, indicating exposure to churn and demand risk.

## Business Insights
- Heavy reliance on top customers increases revenue volatility.
- Best selling products require careful inventory and demand planning.
- Diversifying the customer base and product portfolio may improve long-term stability.

## Tools & Technologies

- Python
  - Pandas
  - NumPy
  - Data Cleaning & Feature Engineering

- SQL
  - Data aggregation
  - Customer and product analysis
  - RFM calculation

- Tableau
  - Interactive dashboard creation
  - Data visualization
    
 ## Dataset

The project uses an online retail transaction dataset containing:

- Invoice information
- Product descriptions
- Quantity purchased
- Purchase dates
- Unit prices
- Customer IDs
- Country information

## Project Structure
├── data/
│ └── online_retail.csv
├── notebooks/
│ └── revenue_concentration_analysis.ipynb
├── README.md

## Future Improvements
- Segment concentration by geography or product category
- Compute Gini coefficients for inequality measurement
- Extend analysis to customer lifetime value

## Author
Youmin Hong
Undergraduate Data Science Student -- University of Michigan 
Github: https://github.com/ymh-13
