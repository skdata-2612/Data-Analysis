# Project Background
I work as a Data Analyst at GameZone Inc., a global e-commerce company specializing in gaming consoles, gaming accessories, and digital entertainment products. The company operates primarily through its Website and Mobile App, serving customers across multiple regions including North America, Europe, and Asia-Pacific.

Founded in 2020, GameZone Inc. has experienced steady growth due to the increasing demand for online gaming products and digital commerce. The company partners with leading gaming brands and offers a wide range of products, including gaming consoles, controllers, accessories, and related merchandise.

The company's business model is based on direct-to-consumer online sales, where customers purchase products through digital platforms. To acquire and retain customers, GameZone Inc. invests in multiple marketing channels such as Email Marketing, Social Media Campaigns, Affiliate Marketing, and Direct Traffic. Revenue is generated through product sales, while customer growth is driven through effective marketing and platform engagement strategies.

As the company continues to expand, management relies on data-driven decision-making to improve operational efficiency, increase revenue, enhance customer satisfaction, and identify new growth opportunities.

Insights and recommendations are provided on the following key areas:

- **Category 1: Sales Performance Analysis** 
- **Category 2: Product Performance Analysis** 
- **Category 3: Customer Acquisition & Marketing Analysis** 
- **Category 4: Regional Performance Analysis** 

The SQL queries used to inspect and clean the data for this analysis can be found here [link].

Targed SQL queries regarding various business questions can be found here [link].

An interactive Power BI dashboard used to report and explore sales trends can be found here [link].



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
 
  
[Entity Relationship Diagram here]



# Executive Summary

### Overview of Findings

Explain the overarching findings, trends, and themes in 2-3 sentences here. This section should address the question: "If a stakeholder were to take away 3 main insights from your project, what are the most important things they should know?" You can put yourself in the shoes of a specific stakeholder - for example, a marketing manager or finance director - to think creatively about this section.

[Visualization, including a graph of overall trends or snapshot of a dashboard]



# Insights Deep Dive
### Category 1:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 1]


### Category 2:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 2]


### Category 3:

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


### Category 4:

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
