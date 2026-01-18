 # Strategic Marketing Analysis: Enhancing Cross-Sell Efficiency in Retail Banking Campaigns
Tools: Excel, Power BI

## 1. Project Overview

This project looks at telemarketing data from a bank's marketing campaign to answer the business question:

> How can we analyze direct marketing campaign performance to improve cross-sell rates and optimize contact strategies for bank term deposit subscriptions?



## 2. Data

### Dataset Overview

<details>
  

This project analyzes a direct marketing campaign from a Portuguese retail bank aimed at promoting **term deposit subscripions** among the existing client base.

The dataset comprises of **45211** individual records, with each entry representing a specific telemarketing contact. The data provides a comprehensive view of three key areas: **client demographics**(age, occupation, marital status, educational background), **financial profile**(balance, credit defaults, outstanding loans), and **campaign logistics**(communication channel, timing, call duration).

While the dataset was structurally sound with no duplicate entries, several attributes such as Job, Education and Contact Type contained unknown values. These records were intentionally retained rather than discarded to ensure a more robust sample size.

To enhance the analytical depth, the data was enriched with three new attributes:
  1. **Job Type**: Classified clients into **Blue Collar, White Collar, Not in Labor Force, or Unknown** based on job status
  2. **Balance Group**: Classified clients into **Above Median or Below Median** based on the client median balance.
  3. **Age Group**: Segmented clients into 5 distinct groups based on their age.

</details>

## 3. Analysis & Insights

### A. What is the overall cross-sell rate for the campaign?

The overall cross-sell rate for the campaign is **11,7%** - which means that **5289** out of the **45211** targeted clients agreed to the new service.

### B. Which client segments contribute most to the overall cross-sell share? Which client segments have the biggest cross-sell rate?

<details>

<img width="1157" height="883" alt="image" src="https://github.com/user-attachments/assets/fee33a5a-ec67-4af4-97f0-abb73b4add26" />
  
</details>

### C. How does cross-sell success vary by timing?

<details>

By day of month:

<img width="418" height="323" alt="image" src="https://github.com/user-attachments/assets/76ebcdf7-098c-4203-a370-bdb068b4ad3d" />

---

By quarter:

<img width="403" height="233" alt="image" src="https://github.com/user-attachments/assets/2f8b4003-19f6-42c8-b60d-5cbd3f252658" />


</details>

### D. How does cross-sell success vary by customer engagement?

<details>
  
By number of contacts:

<img width="349" height="427" alt="image" src="https://github.com/user-attachments/assets/9f8b58d3-5d56-4169-9e00-42d4c7f37546" />

---
By previous campaign outcome:

<img width="397" height="118" alt="image" src="https://github.com/user-attachments/assets/0f5998dc-aa9c-4040-abed-b24d1f44bb0c" />


---

By call duration:

<img width="404" height="230" alt="image" src="https://github.com/user-attachments/assets/8b81072e-60c1-4b8d-9d6b-358fa3c7a998" />


</details>

## 4. Conclusions & Recommendations

Based on the data presented in the charts and tables of the previous sections, we can draw the following conclusions:

* **Volume vs. Efficiency Gap**: Clients aged 30-44 have the highest contribution share at 46%, acting as the campaign's volume driver. Older customers(60+) have significantly higher cross-sell rates, making them the most efficient segment.
* **Affluence as a Predictor**: Financial health is a driver of success; clients with above-median balances account for 61% of all successful subscriptions with a 14% cross-sell rate.
* **Professional Segmentation**: White-collar clients outperform blue-collar clients in both volume and efficiency. Interestingly, those not in the labot force (retirees, students) provide the highest cross-sell rate(22%), despite their smaller total volume.
* **Optimal Timing**: Outreach in the first five days of the month and during Q1 or A4 yielded the highest success rates(15-18%).
* **Diminishing returns on Contact**: Effectiveness peaks within the first three contacts. Success drops sharply as contact frequency increases, reaching 0% after 33 attempts, suggesting a clear point of customer fatigue.
* **Historical Momentum**: Prior campaign disposition is a powerful lead-scoring metric. Clients who accepted a previous offer showed a 65% cross-sell rate, compared to only 13% for those who previously declined.
* **Golden window of Duration**: Calls under 5 minutes rarely convert(6%), and calls over 80 minutes have a 0% success rate. The sweet spot for conversion lies between 20 and 35 minutes(63% success).

Recommendations:

The following strategic adjustmetns are recommended to optimize future cross-sell campaigns:

1. **Prioritize "Warm" Leads**: Future campaigns should first target clients who have accepted offers in the past. Due to their high conversion rate, this segment should be prioritized before cold-calling the broader base to ensure a high early-campaign ROI.

2. **Implement a Contact Cap**: To preserve brand reputation and reduce campaign cost, outreach should be stopped after the 5th unsuccessful attempt. The data shows that after this point, the likelihood of conversion is marginal and does not justify the operational cost.

3. **Improve Scripts**: Sales training should focus on moving clients past the 5 minute mark. Scripts should be designed to build enough value to reach the 20-minute threshold, where the probability of a "Yes" increases tenfold.

4. **Balance-Based Leads:** Use the Above-Median balance flag as a primary filter for lead assignment. High-balance clients represent 61% of total potential revenue and should be assigned to the most experienced sales agents.
