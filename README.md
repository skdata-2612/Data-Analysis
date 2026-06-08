# Project Background
I work as a Data Analyst at GameZone Inc., a global e-commerce company specializing in gaming consoles, gaming accessories, and digital entertainment products. The company operates primarily through its Website and Mobile App, serving customers across multiple regions including North America, Europe, and Asia-Pacific.

Founded in 2020, GameZone Inc. has experienced steady growth due to the increasing demand for online gaming products and digital commerce. The company partners with leading gaming brands and offers a wide range of products, including gaming consoles, controllers, accessories, and related merchandise.

The company's business model is based on direct-to-consumer online sales, where customers purchase products through digital platforms. To acquire and retain customers, GameZone Inc. invests in multiple marketing channels such as Email Marketing, Social Media Campaigns, Affiliate Marketing, and Direct Traffic. Revenue is generated through product sales, while customer growth is driven through effective marketing and platform engagement strategies.

As the company continues to expand, management relies on data-driven decision-making to improve operational efficiency, increase revenue, enhance customer satisfaction, and identify new growth opportunities.

Insights and recommendations are provided on the following key areas:

1. Sales Performance Analysis
2. Product Performance Analysis
3. Customer Acquisition & Marketing Analysis 
4. Regional Performance Analysis

The complete SQL script containing data cleaning, exploratory analysis, and business-focused queries can be found (https://github.com/skdata-2612/Data-Analysis/blob/71521a1f812266977796976ca51e0e440d517280/SQL%20queries).


# Data Structure & Initial Checks

The company's database consists of two primary tables containing order-level and region-level information. A description of each table is as follows:

- Orders Table (21,864 records)

Contains transactional data related to customer purchases.

Key fields include:

- Order ID
- User ID
- Purchase Date
- Ship Date
- Refund Date
- Product Name
- Product ID
- Revenue (USD Price)
- Purchase Platform
- Marketing Channel
- Account Creation Method
- Country Code

 Regions Table:

 Contains geographic information used to classify customers into business regions.

 Key fields include:

 - Country Code
 - Region

 Initial data checks were performed to:

- Identify duplicate orders
- Verify missing values
- Validate refund records
- Confirm date consistency
- Standardize categorical values
- Create Net Revenue metrics

 

<img width="893" height="536" alt="erd" src="https://github.com/user-attachments/assets/800394f1-7ea8-459a-b8f1-551d5ae102cd" />



# Executive Summary

### Overview of Findings

Explain the overarching findings, trends, and themes in 2-3 sentences here. This section should address the question: "If a stakeholder were to take away 3 main insights from your project, what are the most important things they should know?" You can put yourself in the shoes of a specific stakeholder - for example, a marketing manager or finance director - to think creatively about this section.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
1. Sales Performance Analysis:

* **Insight 1.**: Revenue growth accelerated significantly throughout 2020

Monthly revenue remained relatively stable during 2019 before experiencing strong growth in 2020. Revenue increased consistently from the first quarter of 2020 onwards, indicating growing customer demand and improved sales performance. The positive trendline further confirms a sustained upward trajectory throughout the analysis period.

* **Insight 2.**: December 2020 recorded the highest monthly revenue

The company achieved its peak monthly revenue of $549,435.13 in December 2020, making it the strongest-performing month in the dataset. This spike may be attributed to increased consumer spending during the holiday season, successful marketing campaigns, or higher demand for gaming-related products.

* **Insight 3.**: Seasonal sales patterns were evident in the second half of 2020

Revenue was generally stronger during the second half of 2020 compared to the first half, with notable increases between August and December. This pattern suggests that sales performance may be influenced by seasonal factors such as product launches, holiday shopping periods, and promotional events.

* **Insight 4.**: Early 2021 results should be interpreted with caution

Although revenue appears to decline in January and February 2021, the dataset contains only two months of data for 2021. As a result, these figures represent a partial-year period and should not be directly compared with previous full-year performance.
  

<img width="1052" height="437" alt="image" src="https://github.com/user-attachments/assets/4cb60620-4198-45c8-9209-4017491df4fa" />




2. Product Performance Analysis:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]


3. Customer Acquisition and Marketing Effectiveness:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


4. Regional Performance Analysis:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 4]



# Recommendations:

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  


# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Assumption 1 (ex: missing country records were for customers based in the US, and were re-coded to be US citizens)
  
* Assumption 1 (ex: data for December 2021 was missing - this was imputed using a combination of historical trends and December 2020 data)
  
* Assumption 1 (ex: because 3% of the refund date column contained non-sensical dates, these were excluded from the analysis)
