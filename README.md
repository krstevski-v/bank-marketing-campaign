 # Strategic Marketing Analysis: Enhancing Cross-Sell Efficiency in Retail Banking Campaigns
Tools: Excel, Power BI

## 1. Project Overview

This project looks at telemarketing data from a bank's marketing campaign to answer the business question:

> How can we analyze direct marketing campaign performance to improve cross-sell rates and optimize contact strategies for bank term deposit subscriptions?



## 2. Data

### Dataset Overview
  
This project analyzes a direct marketing campaign by a Portuguese retail bank to promote term deposit subscriptions among existing clients.

The dataset contains **45211** records, each representing one telemarketing contact, covering:

* Client demographics: age, occupation, marital status, education
* Financial profile: balance, credit defaults, outstanding loans
* Campaign logistics: communication channel, timing, call duration

The data had no duplicates. Unknown values in Job, Education, and Contact Type were retained to preserve sample size.

Three attributes were added to deepen the analysis:

1. Job Type: Blue Collar, White Collar, Not in Labor Force, or Unknown
2. Balance Group: Above or Below the median client balance
3. Age Group: five age segments


## 3. Analysis & Insights

### A. What is the overall cross-sell rate for the campaign?

The overall cross-sell rate for the campaign is **11,7%** - which means that **5289** out of the **45211** targeted clients agreed to the new service.

### B. Which client segments contribute most to the overall cross-sell share? Which client segments have the biggest cross-sell rate?


<img width="1157" height="883" alt="image" src="https://github.com/user-attachments/assets/fee33a5a-ec67-4af4-97f0-abb73b4add26" />
  

### C. How does cross-sell success vary by timing?



By day of month:

<img width="418" height="323" alt="image" src="https://github.com/user-attachments/assets/76ebcdf7-098c-4203-a370-bdb068b4ad3d" />

---

By quarter:

<img width="403" height="233" alt="image" src="https://github.com/user-attachments/assets/2f8b4003-19f6-42c8-b60d-5cbd3f252658" />



### D. How does cross-sell success vary by customer engagement?

  
By number of contacts:

<img width="349" height="427" alt="image" src="https://github.com/user-attachments/assets/9f8b58d3-5d56-4169-9e00-42d4c7f37546" />

---
By previous campaign outcome:

<img width="397" height="118" alt="image" src="https://github.com/user-attachments/assets/0f5998dc-aa9c-4040-abed-b24d1f44bb0c" />


---

By call duration:

<img width="404" height="230" alt="image" src="https://github.com/user-attachments/assets/8b81072e-60c1-4b8d-9d6b-358fa3c7a998" />


## 4. Conclusions

* **Volume vs. Efficiency:** Clients aged 30-44 drive volume with a 46% contribution share, while clients 60+ have the highest cross-sell rates.
* **Affluence:** Clients with above-median balances account for 61% of successful subscriptions, with a 14% cross-sell rate.
* **Job Type:** White-collar clients outperform blue-collar clients in both volume and efficiency. Clients not in the labor force (retirees, students) have the highest cross-sell rate (22%) despite smaller volume.
* **Timing:** Outreach in the first five days of the month and during Q1 or Q4 had the highest success rates (15-18%).
* **Contact Frequency:** Effectiveness peaks within the first three contacts and drops sharply afterward, reaching 0% after 33 attempts, which points to customer fatigue.
* **Prior Campaign Outcome:** A strong lead-scoring signal. Clients who accepted a previous offer converted at 65%, versus 13% for those who declined.
* **Call Duration:** Calls under 5 minutes rarely convert (6%), and calls over 80 minutes have 0% success. The sweet spot is 20-35 minutes (63% success).

