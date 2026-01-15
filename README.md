# Analysis of a bank's marketing campaign
Tools: Excel, Tableau

## 1. Project Overview

This project looks at telemarketing data from a bank's marketing campaign to answer the business question:

> How can we analyze direct marketing campaign performance to improve conversion rates and optimize contact strategies for bank term deposit subscriptions?]


## 2. Data

### Dataset Overview

All data used in this project is based on a direct marketing campaign of a Portuguese banking institution, whose goal was to get clients to subscribe to a term deposit.

The dataset contains **45 211** records. Each record represents a call to a certain customer. Data was collected on the customer's demographics(age, job, marital status, education level), financial status(balance, credit, loans) and internal campaign metrics(contact communication type, day of contact, contact duration etc.)

There were no duplicate rows in the dataset, and most rows were structurally solid. A few columns, such as Job, Education and Contact Type, featured missing values, but records with unknown data for these columns were not removed, as they contained enough information based on the other columns to have analytical value[note: probably needs to be re-written for more brevity and clarity].

The dataset was enriched with three new columns based on the pre-existing data:
  1. **Job Type**: Classified customers into **Blue Collar, White Collar, Not in Labor Force, or Unknown** based on job status
  2. **Balance Group**: Classified customers into **Above Median or Below Median** based on their balance levels and the median balance.
  3. **Age Group**: Segmented customers into 5 distinct groups based on their age.


## 3. Analysis & Insights

### A. What is the overall conversion rate for the campaign?

The overall conversion rate for the campaign is **11,7%** - which means that **5289** potential customers were converted into clients out of **45211** total.

### B. Which customer segments have the highest conversion rates?

Based on Job Type:
  * Blue-collar customers represent 50,26% of clients and 38,31% of conversions.
  * White-collar customers represent 39,14% of clients and 42,39% of conversions.
  * Clients who are Not in Labor Force represent 9,96% of clients and 18,66% of conversions.
  * Clients with an unknown job status represent 0,64% of clients and 0,64% of conversions.

Based on Age Group:
  * 
