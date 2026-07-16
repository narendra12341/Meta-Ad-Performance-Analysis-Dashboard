# 📊 Meta Ad Performance Analysis Dashboard

<p align="center">

!\[Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi\&logoColor=black)
!\[DAX](https://img.shields.io/badge/DAX-Measures-blue)
!\[Power Query](https://img.shields.io/badge/Power%20Query-ETL-green)
!\[Data Modeling](https://img.shields.io/badge/Data-Modeling-orange)
!\[Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</p>

\---

## 🚀 Overview

This repository contains an interactive **Meta Ad Performance Dashboard** built using **Microsoft Power BI**.

The dashboard analyzes advertising campaign performance across **Facebook** and **Instagram**, enabling marketers to evaluate campaign effectiveness, audience engagement, conversion performance, and budget utilization through interactive visualizations and KPI metrics.

This project demonstrates practical skills in:

* 📊 Business Intelligence
* 📈 Marketing Analytics
* 📉 Data Visualization
* 🧮 DAX Calculations
* 🔄 Data Modeling
* 📌 Business Insights



\---

## 🛠️ Tech Stack

* Microsoft Power BI
* Power Query
* DAX
* Data Modeling
* Star Schema
* Marketing Analytics

\---

## 📷 Dashboard Preview

> \*\*Interactive Meta Ad Performance Dashboard\*\*

The dashboard provides a comprehensive overview of advertising campaign performance across Meta platforms, enabling users to monitor key metrics, identify trends, and make data-driven marketing decisions.

### Dashboard Overview

<p align="center">
<img width="1401" height="804" alt="image" src="https://github.com/user-attachments/assets/a1db6190-3cac-4961-b4e4-fd5d5da433c7" />

</p>

\---

### ✨ Dashboard Highlights

✔ Executive KPI Cards

* Impressions
* Clicks
* Engagements
* Purchases
* CTR (Click-Through Rate)
* Engagement Rate
* Conversion Rate
* Purchase Rate
* Total Budget
* Average Budget per Campaign

✔ Interactive Visualizations

* 👥 Audience Engagement by Gender
* 🎯 Target Age Group Analysis
* 🌍 Country Performance Map
* 📅 Calendar Heat Map
* 📈 Weekly Engagement Trend
* 🕒 Hourly Activity Analysis
* 📊 Ad Type Performance Matrix

\---

### 🎛 Interactive Features

* Dynamic KPI Selection
* Interactive Slicers
* Cross Filtering
* Drill-down Analysis
* Responsive Dashboard Layout
* Business-focused Data Visualizations

\---



\---

## 🎯 Business Problem

Digital advertising campaigns generate large volumes of performance data across multiple channels. Without a centralized analytics solution, it becomes difficult for marketing teams to evaluate campaign effectiveness, understand audience behavior, and optimize advertising budgets.

This project addresses these challenges by developing an interactive Power BI dashboard that transforms raw advertising data into meaningful insights. The dashboard enables users to monitor campaign performance, compare key marketing metrics, and identify opportunities for improving engagement and conversions.

\---

## 🎯 Project Objectives

The primary objectives of this project are to:

* 📊 Monitor advertising campaign performance using key marketing KPIs.
* 👥 Analyze audience engagement across different demographic segments.
* 🌍 Evaluate campaign performance by geographic location.
* 📈 Identify engagement trends over time.
* 🎯 Compare the effectiveness of different advertisement formats.
* 💰 Support better budget allocation through data-driven insights.
* 📌 Present business information using clear and interactive visualizations.

\---

## 💼 Business Value

This dashboard helps marketing teams answer important business questions, such as:

* Which advertising campaigns generate the highest engagement?
* Which audience segments interact the most with advertisements?
* Which countries contribute the highest campaign performance?
* Which advertisement formats deliver better results?
* When is the best time to display advertisements?
* Where can campaign performance be improved to increase conversions?

By answering these questions, organizations can make informed marketing decisions, improve return on investment (ROI), and optimize future advertising strategies.

\---

\---

# ✨ Features

This dashboard provides a comprehensive set of interactive analytics features designed to help users monitor, analyze, and optimize Meta advertising campaigns.

## 📊 Executive KPI Dashboard

Monitor key marketing metrics at a glance, including:

* Total Impressions
* Total Clicks
* Total Engagements
* Total Purchases
* Click-Through Rate (CTR)
* Engagement Rate
* Conversion Rate
* Purchase Rate
* Total Campaign Budget
* Average Budget per Campaign

\---

## 👥 Audience Analysis

Understand audience behavior through demographic insights.

* Gender-wise engagement analysis
* Target age group comparison
* Audience interaction patterns

\---

## 🌍 Geographic Performance Analysis

Visualize campaign performance across different countries to identify high-performing regions and support location-based marketing decisions.

\---

## 📅 Time-Based Analysis

Analyze user engagement over time to identify trends and peak activity periods.

* Weekly performance trends
* Hourly engagement analysis
* Calendar heat map

\---

## 📈 Advertisement Performance

Compare the effectiveness of different advertisement formats.

* Image Ads
* Video Ads
* Carousel Ads
* Story Ads

\---

## 🎛 Interactive Dashboard Experience

The dashboard includes several interactive features for enhanced data exploration.

* Dynamic KPI selection
* Interactive slicers
* Cross-filtering between visuals
* Responsive report navigation
* Drill-down analysis

\---

## 📌 Business Insights

Transform raw advertising data into meaningful business insights that support:

* Campaign optimization
* Audience targeting
* Budget allocation
* Marketing decision-making
* Performance monitoring

\---



\---

# 🏗️ Data Architecture

The dashboard is built using a **Star Schema** data model, a widely adopted design in Business Intelligence and Data Warehousing. This structure improves query performance, simplifies relationships, and enables efficient analytical reporting.

<p align="center">
   <img width="1269" height="787" alt="image" src="https://github.com/user-attachments/assets/593c08c2-cd51-40ce-9321-7b71c3d029e5" />

</p>

\---

## 📊 Data Model

The project consists of **one fact table** and **three dimension tables**.

|Table|Type|Description|
|-|-|-|
|**ad\_events**|Fact Table|Stores user interactions such as impressions, clicks, shares, comments, and purchases.|
|**ads**|Dimension Table|Contains advertisement details including platform, ad type, and targeting information.|
|**campaigns**|Dimension Table|Stores campaign information such as campaign name, duration, and budget.|
|**users**|Dimension Table|Contains demographic information including gender, age group, interests, and country.|

\---

## 🔗 Data Relationships

The relationships between the tables enable comprehensive campaign analysis:

* **Campaigns → Ads**

  * One campaign can contain multiple advertisements.
* **Ads → Ad Events**

  * Each advertisement can generate many user interaction events.
* **Users → Ad Events**

  * Each event is associated with a user, allowing demographic and geographic analysis.

This relational model supports flexible slicing and filtering across campaigns, advertisements, users, and engagement metrics.

\---

## 📌 Why a Star Schema?

The Star Schema was selected because it offers several advantages for analytical reporting:

* ⭐ Simplifies data relationships
* ⚡ Improves report performance
* 📈 Optimizes DAX calculations
* 📊 Enables efficient aggregation of KPIs
* 🔄 Supports scalable reporting and future enhancements

\---

\---

# 📊 Key Performance Indicators (KPIs)

The dashboard tracks a collection of marketing KPIs that provide insights into campaign reach, engagement, conversion performance, and budget utilization.

|KPI|Description|Business Purpose|
|-|-|-|
|👁️ **Impressions**|Total number of times advertisements were displayed.|Measure campaign reach and visibility.|
|🖱️ **Clicks**|Total number of user clicks on advertisements.|Evaluate audience interest and engagement.|
|💬 **Comments**|Number of comments received on advertisements.|Measure audience interaction and feedback.|
|🔄 **Shares**|Number of times advertisements were shared.|Assess content virality and organic reach.|
|🛒 **Purchases**|Total completed purchases generated from advertisements.|Measure campaign conversions.|
|❤️ **Engagements**|Combined total of clicks, comments, and shares.|Evaluate overall audience engagement.|
|🎯 **Click-Through Rate (CTR)**|Percentage of impressions that resulted in clicks.|Measure advertisement effectiveness.|
|📈 **Engagement Rate**|Percentage of impressions that generated engagement.|Understand how well the content resonates with users.|
|💰 **Conversion Rate**|Percentage of clicks that resulted in purchases.|Measure the efficiency of converting visitors into customers.|
|📦 **Purchase Rate**|Percentage of impressions that resulted in purchases.|Evaluate the effectiveness of the complete marketing funnel.|
|💵 **Total Budget**|Total advertising budget allocated across campaigns.|Monitor campaign investment.|
|📊 **Average Budget per Campaign**|Average advertising budget allocated to each campaign.|Compare budget distribution across campaigns.|

\---

## 📈 Performance Areas

The dashboard evaluates campaign performance across four key business areas:

### 📢 Reach

* Impressions
* Campaign Visibility

### 🤝 Engagement

* Clicks
* Comments
* Shares
* Engagement Rate

### 🛍️ Conversion

* Purchases
* Conversion Rate
* Purchase Rate

### 💰 Budget

* Total Budget
* Average Budget per Campaign

These KPIs help marketing teams identify high-performing campaigns, optimize advertising spend, and improve overall campaign effectiveness.



\---

# 📊 Dashboard Visualizations

The dashboard combines multiple interactive visualizations to provide a comprehensive view of campaign performance, audience behavior, and marketing effectiveness.

\---

## 📌 Executive KPI Cards

The KPI cards provide a high-level summary of campaign performance, enabling stakeholders to monitor key business metrics at a glance.

**Metrics Displayed**

* 👁️ Impressions
* 🖱️ Clicks
* ❤️ Engagements
* 🛒 Purchases
* 🎯 Click-Through Rate (CTR)
* 📈 Engagement Rate
* 💰 Conversion Rate
* 📦 Purchase Rate
* 💵 Total Budget
* 📊 Average Budget per Campaign

**Business Value**

Provides an instant overview of campaign performance without requiring users to explore detailed reports.

\---

## 👥 Audience Engagement Analysis

**Visualization:** Donut Chart

Displays engagement distribution across different target gender groups.

**Business Question**

> Which audience segment interacts most with our advertisements?

\---

## 🎯 Target Age Group Analysis

**Visualization:** Bar Chart

Compares campaign performance across different target age groups.

**Business Question**

> Which age group responds most effectively to our advertising campaigns?

\---

## 🌍 Geographic Performance

**Visualization:** Map

Displays campaign performance across different countries.

**Business Question**

> Which geographic regions contribute the highest campaign engagement?

\---

## 📅 Calendar Heat Map

**Visualization:** Calendar View

Highlights daily engagement activity to identify high-performing dates and seasonal trends.

**Business Question**

> Are there specific dates or periods when campaigns perform better?

\---

## 📈 Weekly Performance Trend

**Visualization:** Stacked Column Chart

Analyzes campaign performance across different weeks while comparing advertisement types.

**Business Question**

> How does campaign performance change over time?

\---

## 🕒 Hourly Engagement Trend

**Visualization:** Area Chart

Displays engagement activity throughout the day.

**Business Question**

> What are the peak hours for audience engagement?

\---

## 📊 Advertisement Performance Matrix

**Visualization:** Matrix

Compares advertisement formats using key performance metrics.

**Advertisement Types**

* 🎥 Video
* 🖼️ Image
* 📚 Carousel
* 📱 Story

**Business Question**

> Which advertisement format delivers the best marketing performance?

\---

## 🎛 Interactive Dashboard Features

The dashboard includes several interactive capabilities to improve user experience.

* Dynamic KPI Selection
* Interactive Filters \& Slicers
* Cross-Filtering Between Visuals
* Responsive Layout
* Drill-Down Analysis
* Interactive Report Navigation

\---

## 💼 Business Impact

Together, these visualizations enable marketing teams to:

* Monitor campaign performance
* Analyze audience behavior
* Identify high-performing advertisement formats
* Optimize advertising budgets
* Improve targeting strategies
* Support data-driven marketing decisions

\---



\---

# 🧮 DAX Measures

The dashboard uses several DAX measures to transform raw advertising data into meaningful business metrics. These measures provide real-time insights into campaign performance and support interactive analysis throughout the report.

\---

## 📊 Core Measures

|Measure|Description|
|-|-|
|**Impressions**|Total number of advertisement impressions.|
|**Clicks**|Total number of advertisement clicks.|
|**Comments**|Total number of comments received.|
|**Shares**|Total number of advertisement shares.|
|**Purchases**|Total completed purchases generated from advertisements.|
|**Engagements**|Combined total of clicks, comments, and shares.|

\---

## 📈 Performance Measures

### 🎯 Click-Through Rate (CTR)

Measures the percentage of impressions that resulted in clicks.

```DAX
CTR = (Clicks / Impressions) × 100
```

\---

### ❤️ Engagement Rate

Measures the percentage of impressions that generated user engagement.

```DAX
Engagement Rate = (Engagements / Impressions) × 100
```

\---

### 🛒 Conversion Rate

Measures the percentage of clicks that resulted in purchases.

```DAX
Conversion Rate = (Purchases / Clicks) × 100
```

\---

### 📦 Purchase Rate

Measures the percentage of impressions that resulted in purchases.

```DAX
Purchase Rate = (Purchases / Impressions) × 100
```

\---

## 💰 Budget Measures

|Measure|Description|
|-|-|
|**Total Budget**|Total advertising budget allocated across all campaigns.|
|**Average Budget per Campaign**|Average budget assigned to each campaign.|

\---

## ⚡ Dynamic KPI Selection

This project implements **Power BI Field Parameters** to allow users to dynamically switch between different KPIs across multiple visualizations.

Users can seamlessly analyze metrics such as:

* 👁️ Impressions
* 🖱️ Clicks
* ❤️ Engagements
* 🛒 Purchases

without changing or rebuilding report visuals.

This approach improves dashboard flexibility and enhances the interactive reporting experience.

\---

## 💡 Why DAX?

DAX measures allow business metrics to be calculated dynamically based on user selections, filters, and slicers. This ensures that every visualization updates instantly, providing accurate and context-aware insights for decision-making.

\---

> \*\*Note:\*\* The dashboard leverages reusable DAX measures and dynamic calculations to deliver a responsive and interactive analytical experience.

\---

\---

# 📈 Key Business Insights

The dashboard uncovers valuable insights into advertising performance by analyzing campaign reach, audience engagement, conversion efficiency, and user behavior. These findings help stakeholders make informed marketing decisions and identify areas for improvement.

\---

## 🚀 Campaign Performance

The advertising campaigns generated strong visibility and user engagement, indicating that the creatives successfully captured audience attention. High engagement levels suggest that the content resonates well with the target audience.

**Key Takeaways**

* High campaign visibility across Meta platforms.
* Strong user interaction with advertisements.
* Consistent engagement throughout the campaign period.

\---

## 👥 Audience Insights

Audience analysis reveals that engagement varies across demographic groups, allowing marketers to identify the most responsive customer segments.

### Observations

* Certain gender groups interact more frequently with advertisements.
* Younger audiences demonstrate higher engagement than older age groups.
* Audience segmentation provides opportunities for more personalized marketing campaigns.

\---

## 🌍 Geographic Performance

Campaign performance differs across geographic regions, highlighting markets with higher engagement potential.

### Observations

* Some countries consistently generate stronger audience engagement.
* Geographic analysis supports region-specific marketing strategies.
* High-performing regions can be prioritized for future advertising investments.

\---

## 📊 Advertisement Performance

Different advertisement formats produce varying levels of engagement and conversion performance.

### Observations

* Video advertisements generate strong audience interaction.
* Story advertisements maintain consistent performance across campaigns.
* Comparing advertisement formats helps optimize future creative strategies.

\---

## 📅 Time-Based Analysis

User engagement changes over time, making scheduling an important factor in campaign success.

### Observations

* Engagement remains relatively stable throughout the reporting period.
* Certain days experience noticeable increases in user activity.
* Audience interaction tends to increase during specific hours of the day.

\---

## 💰 Conversion Analysis

Although campaigns attract significant attention and engagement, not every interaction results in a successful conversion.

### Observations

* Strong upper-funnel performance demonstrates effective audience reach.
* Opportunities exist to improve the conversion journey after users engage with advertisements.
* Optimizing landing pages, offers, and retargeting strategies may improve overall conversion performance.

\---

## 📌 Summary

Overall, the dashboard provides a comprehensive view of advertising performance by combining campaign metrics, audience analysis, geographic insights, and behavioral trends. These insights enable marketing teams to optimize campaigns, improve targeting strategies, and support data-driven decision-making.

\---

# 💡 Business Recommendations

Based on the dashboard analysis, the following recommendations can help improve campaign effectiveness and maximize marketing return on investment (ROI).

\---

## 🎯 Optimize Audience Targeting

Use demographic insights to better align advertisements with high-performing audience segments.

**Recommendations**

* Focus campaigns on the most responsive age groups.
* Refine targeting based on audience interests and engagement behavior.
* Continuously evaluate demographic performance to improve targeting accuracy.

\---

## 🎥 Invest in High-Performing Ad Formats

Compare advertisement formats regularly and allocate budgets to those delivering the strongest performance.

**Recommendations**

* Increase investment in high-performing ad creatives.
* Test new creative variations to improve audience engagement.
* Reduce spending on underperforming advertisement formats.

\---

## 🌍 Prioritize High-Value Markets

Geographic analysis can help identify regions with stronger engagement and conversion potential.

**Recommendations**

* Increase campaign investment in high-performing countries.
* Develop localized marketing strategies for different regions.
* Monitor regional performance to identify emerging market opportunities.

\---

## 🕒 Improve Campaign Scheduling

User engagement varies throughout the day and across different time periods.

**Recommendations**

* Schedule advertisements during peak engagement hours.
* Align campaign launches with periods of increased audience activity.
* Continuously evaluate performance trends to optimize scheduling.

\---

## 📈 Improve Conversion Performance

Strong engagement does not always translate into successful conversions.

**Recommendations**

* Optimize landing page experience.
* Improve call-to-action messaging.
* Strengthen retargeting campaigns.
* Conduct A/B testing to improve conversion rates.
* Reduce friction within the customer journey.

\---

## 📊 Monitor Campaign Performance

Marketing performance should be continuously monitored to support informed decision-making.

**Recommendations**

* Track KPI trends regularly.
* Compare campaign performance over time.
* Evaluate budget utilization.
* Identify opportunities for continuous optimization.

\---

## 🚀 Future Enhancements

This project can be extended with additional analytical capabilities, including:

* Predictive campaign performance analysis
* Customer segmentation using machine learning
* Real-time dashboard refresh
* Sentiment analysis from user comments
* Campaign ROI forecasting
* Executive summary dashboard
* Mobile-optimized report layout
* Integration with live Meta Ads data

\---

## ✅ Conclusion

This dashboard demonstrates how business intelligence can transform advertising data into actionable insights. By combining interactive visualizations, marketing KPIs, and data-driven recommendations, the solution supports more effective campaign management, smarter budget allocation, and continuous performance improvement.

\---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience in designing and developing an interactive Power BI dashboard for marketing analytics. The project strengthened both my technical and analytical skills by applying business intelligence concepts to a real-world scenario.

### Skills Developed

* 📊 Interactive Dashboard Development
* 🏗️ Data Modeling with Star Schema
* 🧮 DAX Measure Development
* 🔄 Data Transformation using Power Query
* 📈 Marketing KPI Analysis
* 📌 Business Insight Generation
* 📖 Data Storytelling
* 💼 Business Intelligence Reporting

\---

# 👨‍💻 Author

**Narendra Peyyala**

🎓 Electronics Ans Communication Engineering
🏫 PBR Visvodaya Institute Of Technology And Science

### 🌐 Connect with Me

* 💼 LinkedIn: https://www.linkedin.com/in/narendra-peyyala/
* 💻 GitHub: https://github.com/narendra12341

\---

