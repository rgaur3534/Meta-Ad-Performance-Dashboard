<h1 align="center">📊 Meta Ads Performance Analysis Dashboard</h1>

<p align="center">
<strong>Power BI · Marketing Analytics · Meta (Facebook & Instagram) · Funnel Analysis</strong>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Power%20BI-Data%20Visualization-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Meta%20Ads-Marketing%20Analytics-0866FF?style=for-the-badge&logo=meta&logoColor=white"/>
<img src="https://img.shields.io/badge/Analytics-Full%20Funnel%20Insights-4CAF50?style=for-the-badge"/>
</p>

<p align="center">
<img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square"/>
<img src="https://img.shields.io/badge/Tool-Power%20BI-blue?style=flat-square"/>
<img src="https://img.shields.io/badge/Level-Portfolio%20Project-orange?style=flat-square"/>
</p>

<hr>

🚀 Project Overview
This project presents a Power BI dashboard designed to analyze and optimize Meta (Facebook & Instagram) advertising performance.
The dashboard provides a full-funnel view — from awareness → engagement → conversion — enabling data-driven decisions around targeting, budgeting, and campaign optimization.
It simulates a real-world marketing analytics scenario, closely aligned with how Meta Ads data is structured and analyzed in industry environments.

🎯 Objectives
· Evaluate ad campaign effectiveness using key performance indicators (KPIs)
· Identify funnel drop-offs from impressions to purchases
· Analyze audience demographics and geographic performance
· Discover optimal ad formats, timing, and budget allocation strategies
· Provide actionable insights to improve ROI

📌 Key KPIs Tracked

Metric                                                        	Description
Impressions	                                             Total times ads were shown
Clicks                                                 	 Number of ad clicks
Engagements                                              Clicks, likes, shares, comments
CTR	                                                     Click-through rate
Engagement Rate	                                         Engagements ÷ impressions
Purchases                                                Conversions generated
Conversion                                               Rate	Purchases ÷ clicks
Purchase Rate	                                           Purchases ÷ impressions
Total Budget	                                           Total ad spend
Avg Budget per Campaign	                                 Spend efficiency

📈 High-Level Performance Summary
· 216K Impressions → Strong reach
· 25.4K Clicks → CTR: 11.76% (well above industry average)
· 29K Engagements → Engagement Rate: 13.56%
· 1.3K Purchases → Conversion Rate: 5.21%, Purchase Rate: 0.61%

🔍 Insight:
Ads perform exceptionally well at awareness and engagement, but there is a significant drop-off at the purchase stage, indicating funnel leakage.

👥 Audience Insights
🔹 Gender
· Female: 43%
· Male: 22%
· Other / Not specified: 35%
👉 Females show significantly higher engagement.

🔹 Age Group
· Peak engagement: 18–30 years
· Sharp decline after 35+
👉 Core audience = Young adults, especially females aged 18–30.

🌍 Geographic Analysis
Top engaged countries:
· India
· Brazil
· USA
· Germany
· UK

🔹 Strategy Insight:
· India & Brazil → High volume, high engagement
· Germany & UK → Lower volume, higher purchasing power
👉 Separate strategies for high-volume vs high-value markets.

⏰ Time & Seasonality Analysis
· Hourly Trend: Engagement peaks in afternoon & evening (15–20 hrs)
· Weekly Trend: Stable engagement across weeks
· Calendar View: Spikes observed on 19–21 and 25–27, likely due to promotions or launches
👉 Ads should be scheduled and budget-weighted toward peak hours and event-based days.

🎥 Ad Format Performance
Ad Type	                                                 Performance
Video	                                           Best CTR, Conversion Rate & Engagement
Stories	                                         Strong performance with high reach
Image	                                           Moderate
Carousel                                         Slightly lower conversions
👉 Recommendation: Shift more budget toward Video & Story ads.

📊 Data Model & Architecture
The dataset follows a star schema, similar to real Meta Ads platforms.

⭐ Fact Table
ad_events
 · Stores impressions, clicks, engagements, purchases
 · Drives all KPI calculations

📐 Dimension Tables
ads
 · Ad platform, format, targeting details
campaigns
 · Budget, duration, campaign metadata
users
 · Demographics, age group, country, interests

🔗 Relationships:
 · ad_events → ads → campaigns
 · ad_events → users

🛠 Tools & Technologies
 · Power BI – Dashboard creation & DAX
 · Power Query – Data transformation
 · Data Modeling – Star schema design
 · Marketing Analytics Concepts – Funnel analysis, ROI, segmentation

💡 Key Insights & Recommendations
 1. Strong top-of-funnel performance, weak conversion funnel
 2. Target audience: Females, 18–30, primarily in India & Brazil
 3. Best-performing formats: Video > Stories
 4. Best engagement times: Afternoon & Evening
 5. Improve landing pages, offers & retargeting to increase purchase rate

📁 Use Case
This dashboard can be used by:
 · Marketing teams
 · Growth analysts
 · Performance marketers
 · Business stakeholders
To:
 · Optimize ad spend
 · Improve conversion efficiency
 · Refine targeting strategies
 · Increase ROI

 
