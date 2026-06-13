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

GameZone experienced strong revenue growth throughout the analysis period, generating over $6.15M in sales across multiple product categories and regions. Performance was primarily driven by North America, high-demand gaming products, and direct acquisition channels, with revenue accelerating significantly during 2020. The findings highlight opportunities to diversify geographic revenue, improve mobile conversion, and expand premium product offerings to support future growth.

<img width="1282" height="718" alt="image" src="https://github.com/user-attachments/assets/ac318fa3-50ba-42ea-b7de-ed6a25c20e23" />





# Insights Deep Dive
1. Sales Performance Analysis:

* **Insight 1.** Revenue growth accelerated significantly throughout 2020

Monthly revenue remained relatively stable during 2019 before experiencing strong growth in 2020. Revenue increased consistently from the first quarter of 2020 onwards, indicating growing customer demand and improved sales performance. The positive trendline further confirms a sustained upward trajectory throughout the analysis period.

* **Insight 2.** December 2020 recorded the highest monthly revenue

The company achieved its peak monthly revenue of $549,435.13 in December 2020, making it the strongest-performing month in the dataset. This spike may be attributed to increased consumer spending during the holiday season, successful marketing campaigns, or higher demand for gaming-related products.

* **Insight 3.** Seasonal sales patterns were evident in the second half of 2020

Revenue was generally stronger during the second half of 2020 compared to the first half, with notable increases between August and December. This pattern suggests that sales performance may be influenced by seasonal factors such as product launches, holiday shopping periods, and promotional events.

* **Insight 4.** Early 2021 results should be interpreted with caution

Although revenue appears to decline in January and February 2021, the dataset contains only two months of data for 2021. As a result, these figures represent a partial-year period and should not be directly compared with previous full-year performance.
  

<img width="1052" height="437" alt="image" src="https://github.com/user-attachments/assets/4cb60620-4198-45c8-9209-4017491df4fa" />




2. Product Performance Analysis:

* **insight 1.** 27in 4K Gaming Monitor is the Top Revenue Driver

  The 27in 4K Gaming Monitor generated the highest sales ($1.97M) and attracted 4,358 users. Its relatively affordable AOV of $417 appears to encourage higher purchase volume, making it the strongest contributor to overall revenue.
  
* **insight 2.** Nintendo Switch Leads in Customer Acquisition

  The Nintendo Switch recorded the highest user count (9,686 users), more than double any other product. However, its lower AOV ($160) limits revenue growth, suggesting strong popularity but lower spend per customer.
  
* **insight 3.** Sony PlayStation 5 Bundle Achieves the Highest Customer Spend

  The Sony PlayStation 5 Bundle has the highest AOV ($1,627), driven by its bundled offering. Despite having only 900 users, it generated $1.59M in sales, demonstrating the effectiveness of premium bundles in increasing order value.
  
* **insight 4.** Different Products Play Different Roles in the Portfolio

  Lower-priced products such as the Nintendo Switch and gaming monitor drive customer volume, while premium products such as the PS5 Bundle and Lenovo IdeaPad Gaming 3 drive higher spending per transaction. A balanced mix of volume and premium products is supporting overall sales performance.

  
<img width="1577" height="413" alt="image" src="https://github.com/user-attachments/assets/4f82d420-ef9d-4c2b-a22c-cfdc24b03e2b" />

<img width="1601" height="567" alt="image" src="https://github.com/user-attachments/assets/45f2a7b6-9a23-43db-94c1-14e4cab7c8f9" />

<img width="1674" height="608" alt="image" src="https://github.com/user-attachments/assets/5911eb31-6806-4e3c-8725-7040ba917eb0" />


3. Customer Acquisition and Marketing Effectiveness:

* **insight 1.** Direct Marketing Drives the Majority of Revenue

  The Direct channel contributes approximately 85% of total revenue ($5.2M), significantly outperforming all other acquisition channels. Email and Affiliate channels provide secondary support, while Social Media and Unknown channels contribute minimal revenue.
  
* **insight 2.** Website Is the Dominant Purchase Platform

  The Website platform accounts for 97% of total revenue and 90% of purchasing users, making it the primary driver of online sales. In contrast, Mobile contributes only 3% of revenue, suggesting customers strongly prefer completing purchases through the website.
  
* **insight 3.** Desktop Remains the Primary Customer Entry Point

  Of the 19,850 total users, approximately 75% created accounts via Desktop, compared to 20% via Mobile. Desktop account creation increased consistently from 2019–2021, indicating sustained preference for desktop onboarding despite growing mobile adoption.
  
* **insight 4.** Mobile Adoption Is Growing but Has Not Yet Translated Into Revenue

  Mobile account creation shows an upward trend and is gradually narrowing the gap with Desktop. However, Mobile users contribute only a small share of purchases and revenue, highlighting a potential opportunity to improve the mobile shopping experience and conversion rates.

* **insight 5.** Low Adoption Channels Have Minimal Business Impact

  Tablet (~2% of users), Unknown (~4% of users), and TV (22 users, <1%) account creation methods represent a very small portion of the user base and have remained relatively flat over time. These channels currently have limited impact on acquisition and revenue performance.


<img width="996" height="526" alt="image" src="https://github.com/user-attachments/assets/4b943a1f-77a8-4ba0-9695-a32f93f10f3d" />

<img width="1118" height="452" alt="image" src="https://github.com/user-attachments/assets/b9e8ed47-1c73-41b7-b605-f0cd293030e9" />

<img width="1241" height="450" alt="image" src="https://github.com/user-attachments/assets/a702b274-66a1-4b4e-af65-bda04b625b3d" />

<img width="869" height="537" alt="image" src="https://github.com/user-attachments/assets/57af80de-ef47-46c9-9e37-9f2256c5ff93" />

<img width="599" height="450" alt="image" src="https://github.com/user-attachments/assets/fe050ce5-acaa-4bba-8ecb-71c88c14d60a" />


4. Regional Performance Analysis:

* **insight 1.** North America is the Primary Revenue Driver

  North America generated $3.21M, accounting for 52% of total revenue. Revenue remained consistently higher than all other regions throughout the analysis period, with a notable surge during the second half of 2020 and a peak in December 2020. The region's dominance indicates a highly established customer base and strong market penetration.
  
* **insight 2.** Revenue Concentration is Highly Dependent on the US Market

  The United States contributed approximately $2.96M, representing 48% of total company revenue. Since North America accounts for 52% of revenue overall, the majority of the region's performance is driven by the US alone. This highlights both a major strength and a potential business risk, as revenue is heavily concentrated in a single country.
  
* **insight 3.** EMEA Provides Stable Secondary Growth

  EMEA generated $1.86M, contributing 30% of total revenue. The region demonstrated steady performance across the entire period and followed a growth pattern similar to North America, particularly during late 2020. Additionally, the United Kingdom ($475K) and Germany ($256K) ranked among the top-performing countries, reinforcing EMEA's importance as the second-largest revenue contributor.
  
* **insight 4.** Emerging Regions Present Expansion Opportunities

  APAC contributed $743K (12%) and LATAM generated $336K (5%) of total revenue. While these regions currently lag behind North America and EMEA, the time-series chart shows gradual growth during 2020, particularly in APAC. Countries such as Japan ($221K) and Australia ($188K) indicate existing market traction that could be leveraged through targeted expansion strategies to diversify revenue sources and reduce dependence on mature markets.

<img width="1413" height="583" alt="image" src="https://github.com/user-attachments/assets/41143796-c0d4-4f29-a599-abb9b42b2a37" />

<img width="1811" height="696" alt="image" src="https://github.com/user-attachments/assets/fefde266-5e68-48f2-8dfb-184f98921e2a" />

<img width="1301" height="379" alt="image" src="https://github.com/user-attachments/assets/95cc338b-25cd-424b-ad3a-691aee58ebe9" />


# Recommendations:

Based on the insights and findings above, we would recommend the Sales, Marketing, and Business Strategy teams to consider the following: 

* **Recommendation 1**: Expand Growth Efforts in Emerging International Markets.

 **Observation:** North America contributes 52% of total revenue, while the United States alone accounts for 48% of company revenue.

 Recommendation: Increase marketing investment and localized campaigns in high-potential markets such as Japan, Australia, Germany, and the United Kingdom to diversify revenue sources and reduce reliance on a single geographic market.
  
* **Recommendation 2:** Leverage High-Performing Products for Cross-Selling Opportunities

**Observation:** The 27in 4K Gaming Monitor and Nintendo Switch generate the highest revenue and customer volumes.

**Recommendation:** Bundle complementary accessories, warranties, and gaming peripherals with these products to increase average order value and maximize revenue from existing customer demand.

* **Recommendation 3:** Expand Premium Product Bundling Strategies

**Observation:** The Sony PlayStation 5 Bundle generated $1.59M in revenue despite serving only 900 customers due to its exceptionally high average order value.

**Recommendation:** Develop additional premium bundles across other product categories to encourage higher customer spending while maintaining a balanced product portfolio.

* **Recommendation 4:** Improve Mobile Conversion Performance

**Observation:** Mobile account creation continues to grow, yet mobile purchases contribute only 3% of total revenue.

**Recommendation:** Review the mobile shopping experience, checkout process, and application performance to identify barriers preventing mobile users from converting into paying customers.

* **Recommendation 5:** Prepare for Seasonal Revenue Peaks

**Observation:** Revenue increased significantly during the second half of 2020, with December 2020 recording the highest monthly sales.

**Recommendation:** Align inventory planning, promotional campaigns, and operational resources ahead of peak seasonal periods to capitalize on predictable increases in customer demand.
  

# Assumptions and Caveats:

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* **Caveat 1:** Partial-Year Data for 2021

   The dataset contains only January and February 2021 transactions. Consequently, revenue trends observed for 2021 represent a partial-year period and should not    be directly compared with full-year performance from 2019 or 2020.

* **Caveat 2:** Analysis Focuses on Revenue Rather Than Profitability

All performance evaluations were based on revenue, customer counts, and average order values. Product costs, marketing expenses, shipping costs, and profit margins were not available and therefore could not be incorporated into the analysis.

* **Caveat 3:** Marketing Attribution Is Based on Available Acquisition Data

Customer acquisition effectiveness was assessed using the marketing channel associated with each transaction. Multi-channel customer journeys and attribution effects were not available, which may understate the contribution of supporting marketing channels.

* **Caveat 4:** Regional Insights Depend on Country Mapping Accuracy

Regional performance analysis assumes that all country codes were accurately mapped to their corresponding geographic regions. Any classification errors could affect regional revenue calculations.

* **Caveat 5:** Historical Trends Do Not Guarantee Future Performance

The analysis is based solely on historical transaction data collected between 2019 and early 2021. Future business performance may be influenced by market conditions, consumer behavior changes, competitive actions, and product launches that are not captured within the dataset.
