# Bank-of-America-Complaints-Analysis

## **TOC**

- [Bank of America Complaints Analysis](#bank-of-america-complaints-analysis)
  - [Project Background](#project-background)
  - [Executive Summary](#executive-summary)
  - [Data Schema Overview](#data-schema-overview)
  - [Insights Deep-Dive](#insights-deep-dive)
    - [Peak Complaint Month in July 2023](#peak-complaint-month-in-july-2023)
    - [Seasonal Complaint Trends](#seasonal-complaint-trends)
    - [Product and Issue Concentration](#product-and-issue-concentration)
    - [Complaint Resolution Outcomes](#complaint-resolution-outcomes)
    - [Digital Shift and Response Delays During COVID-19](#digital-shift-and-response-delays-during-covid-19)
    - [Complaints with untimely responses](#complaints-with-untimely-responses)
  - [Recommendations](#recommendations)
    - [Strengthen Peak Period Readiness  ](#strengthen-peak-period-readiness)
    - [Improve Banking Product Experience](#improve-banking-product-experience)
    - [Boost Resolution Quality and Clarity  ](#boost-resolution-quality-and-clarity)
    - [Optimize Digital Complaint Handling](#optimize-digital-complaint-handling)
    - [Address Root Causes of Delayed Responses](#address-root-causes-of-delayed-responses)
  - [Assumptions, and Caveats](#assumptions-and-caveats)

# Bank of America Complaints Analysis

## Project Background

This project analyzes consumer complaints submitted to the CFPB about Bank of America from 2017 to 2023, covering submission dates, product types, reported issues, and company responses. The goal is to identify patterns in complaint trends, resolution effectiveness, and response timeliness to guide recommendations that improve customer service and operational processes.

---
## Executive Summary

Analysis of consumer complaints data from 2017-2023 reveals a significant pattern in financial service issues, with total complaints reaching 62,516. July 2023 marked a notable spike of 1,743 complaints, 174% above the monthly average. Banking services, particularly checking and savings accounts, represent 46% of all complaints, followed by credit card issues (28%). The timely response rate stands at 93.8%, though resolution effectiveness varies with 65.7% closed with explanation and 23.5% resulting in monetary relief. Geographic analysis shows concentration in California, Florida, and Texas, accounting for 35% of total complaints. Implementing enhanced account management systems and strengthening response protocols could significantly improve customer satisfaction and operational efficiency.

![Complaint trend over time](images/20250506233003.png) 

![Product breakdown](images/20250506233031.png) 

--- 
## Data Schema Overview

![Data schema](images/20250506233223.png)

--- 
## Insights Deep-Dive

### Peak Complaint Month in July 2023

Complaint volumes have generally trended upward since 2020, with a dramatic spike in July 2023. This surge, representing a 174% increase over the monthly average,  was driven by the increase of complaints related to checking or savings accounts, which accounted for 869 cases. 

![July 2023 spike](images/20250506210942.png)  

The most common issues within this category were managing an account, opening an account, and problems with lenders or companies charging accounts. This suggests that consumers faced notable challenges with their banking services during this period, possibly due to changes in account management processes, new fees, or disruptions in service.

![Common issues](images/20250506235906.png) 

Credit card and prepaid card complaints also contributed to the spike, with 486 cases. The leading issues here were problems with purchases shown on statements, other features or terms, and fees or interest. This indicates that many consumers experienced difficulties with their credit card transactions and account features.

![Credit card issues](images/20250507000003.png)  

Geographically, the spike was most pronounced in states with large populations, such as California, Florida, and Texas, but the trend was observed nationwide.

![Geographic distribution](images/20250507135006.png) 

### Seasonal Complaint Trends
Complaint volumes tend to rise consistently in Q3 that shows 23% higher complaint volumes than Q1. Indicating a possible seasonal effect that companies should anticipate and plan for.

MoM
2017 
![2017 trends](images/20250506210732.png) 

2018
![2018 trends](images/20250506210759.png) 

2019
![2019 trends](images/20250506210832.png)

2020 
![2020 trends](images/20250506210853.png)

2021 
![2021 trends](images/20250506210920.png)

2022
![2022 trends](images/20250506210929.png)

2023 
![2023 trends](images/20250506210942.png)

### Product and Issue Concentration

Banking products, particularly checking and savings accounts, are at the heart of consumer dissatisfaction, accounting for 46% of all complaints. Credit card and prepaid card issues follow closely, making up 28%. The most common issues reported include managing accounts, incorrect information on credit reports, and problems with purchases or account charges. These recurring themes point to systemic challenges in account management, transaction transparency, and credit reporting accuracy.
   
![Product concentration](images/20250506225318.png) 

![Issue breakdown](images/20250506225407.png)

### Complaint Resolution Outcomes

While companies respond to most complaints in a timely manner (93.8%), the nature of these resolutions varies. The majority (65.7%) are closed with an explanation, while 23.5% result in monetary relief and 8.4% in non-monetary relief. Only a small fraction remain in progress. This distribution suggests that while companies are generally responsive, there is room to improve the quality and impact of their resolutions, especially for complex or recurring issues.

![Resolution outcomes](images/20250506225830.png) 

### Digital Shift and Response Delays During COVID-19

From 2017 to 2023, **web** became the dominant complaint channel, surging during the **COVID-19 pandemic**. 

2017
![2017 channels](images/20250507134443.png) 

2018
![2018 channels](images/20250507134529.png) 

2019
![2019 channels](images/20250507134540.png) 

2020
![2020 channels](images/20250507134553.png) 

2021
![2021 channels](images/20250507134611.png)

2022
![2022 channels](images/20250507134622.png) 

2023
![2023 channels](images/20250507134634.png) 


This shift strained response systems. Complaints submitted online saw **more untimely responses** in 2020 vs 2021, suggesting that financial firms struggled to keep up with rising digital volumes.

2020
![2020 responses](images/20250507134828.png) 

2021
![2021 responses](images/20250507134843.png) 


### Complaints with untimely responses

The data shows a sharp increase in untimely complaint responses beginning in 2020 and peaking in 2021, indicating a strong COVID-19 impact on operational efficiency. Although there's a downward trend post-2021, 2022 (560 complaints) and 2023 (529 complaints) figures remain above pre-pandemic levels, suggesting a "new normal" in response times.

![Untimely responses trend](images/20250506225939.png)

Untimely responses during this period were related to basic banking services (checking/savings accounts), suggesting that banks may have been particularly challenged in maintaining response times. On the other hand, the most delayed issues involved "Managing an account" and "Incorrect information on reports," implying that these complex or high-touch cases are more difficult to resolve within standard timeframes.

![Delayed services](images/20250507115544.png) 

![Delayed issues](images/20250507115604.png) 


--- 
## Recommendations
### Strengthen Peak Period Readiness  
* Proactive Monitoring & Resource Allocation: Allocate additional resources and staff training ahead of anticipated complaint surges, particularly in the summer months, to maintain service quality during high-demand periods.
* **Crisis-Responsive Playbooks**: Develop flexible response protocols to handle sudden complaint influxes tied to account management or credit product issues.

### Improve Banking Product Experience
* Audit High-Issue Products: Conduct end-to-end reviews of checking/savings account workflows and credit card transaction systems to identify pain points causing consumer frustration.
* **Enhance Issue Transparency**: Provide clearer, real-time updates to consumers on disputes, account actions, and fees to reduce complaints related to confusion or misinformation.

### Boost Resolution Quality and Clarity  
* **Refine Resolution Strategies**: Shift toward more impactful complaint resolutions, including monetary/non-monetary relief, especially for recurring and complex issues.
* **Follow-Up Mechanism**: Implement post-resolution follow-ups for select cases to confirm consumer satisfaction and gather feedback for service improvement.

### Optimize Digital Complaint Handling
* **Scale Digital Support Systems**: Invest in automation and AI triaging tools to manage growing online complaint volumes and minimize response delays.
* **Channel-Specific Training**: Equip teams with the tools and training to resolve web-submitted complaints efficiently, especially during crisis periods.

### Address Root Causes of Delayed Responses
* Specialized Support Teams: Create task forces focused on handling complex issues like "Managing an account" and "Incorrect credit information" to reduce resolution times.
* **Process Benchmarking**: Analyze and streamline internal processes for banking-related complaints to eliminate bottlenecks causing repeated delays.

---
## Assumptions, and Caveats

* Assumption of Data Accuracy: The analysis assumes that the complaint records are correctly logged and categorized by the Consumer Financial Protection Bureau (CFPB), with no major reporting errors or duplicates.
* Subset of Complaints: The dataset may not represent all consumer complaints, only those submitted and published by CFPB, which could underrepresent certain industries or regions.
* No Direct Causality: Observed correlations (e.g., untimely responses during COVID-19 or seasonal spikes) are not definitive proof of causation and may be influenced by other external factors.
* Focus on Key Categories: The analysis prioritized top categories and issues to highlight major trends, which may omit less frequent but important complaint types.


