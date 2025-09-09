# Business Insights 360 – Power BI Project

This project is my debut end-to-end Business Intelligence (BI) solution, developed for AtliQ Hardware, a fast-growing consumer electronics company. The goal was to provide actionable insights across multiple business domains using Power BI and modern data practices.

## Problem Statement

AtliQ Hardware heavily relied on Excel for analysis, which created challenges in handling large datasets and limited decision-making speed. This became critical during a major financial setback in Latin America.

## Objective

To build interactive, stakeholder-focused dashboards in Power BI that address business questions from the following perspectives:

- Finance

- Sales

- Marketing

- Supply Chain

- Executive View
  

## Data Overview

- Size: 1.8M+ records

- Source: MySQL Database (extracted using SQL queries) and Excel

- Modeling: Star schema

- Transformations: Power Query for cleaning, merging, and calculated columns


## Tools & Technologies

- SQL – for data extraction

- Power BI Desktop – for dashboard creation

- Excel – for initial exploration

- Power Query – for ETL & transformations

- DAX Studio – for performance optimization

- Power BI Service – for publishing & sharing


 ## Approach

1. Requirement Gathering – Defined needs for 5 dashboards.

2. Data Preparation – Extracted & transformed using SQL + Power Query.

3. Data Modeling – Implemented snowflake schema for optimized analysis.

4. Dashboard Design – Followed 15 design principles for usability & clarity.

5. User Acceptance Testing (UAT) – Incorporated stakeholder feedback.

6. Performance Optimization – Tuned DAX queries for faster insights.

7. Deployment – Published dashboards to Power BI Service.

## Key Insights from the project

### 📊 Finance View
The finance dashboard reveals a major disconnect between top-line growth and bottom-line profitability.

* Massive Revenue Growth: Net sales have surged dramatically from FY 2018 to FY 2022, indicating strong market penetration and sales volume. 
* Declining Profitability: Despite the sales growth, profitability has plummeted. This is a critical red flag for the company's financial health.

* Soaring Operational Expenses: A significant increase in operational costs is the primary driver of the profit decline. This suggests major inefficiencies in the company's processes, such as manufacturing, logistics, or administration.

### 📈 Sales View
The sales view highlights a significant shift in customer dynamics and a potential profitability problem with certain customer segments.

- Customer Portfolio Shift: The top customers have changed dramatically over the years. The emergence of the "AtliQ e-Store" as a top performer indicates a successful shift towards direct-to-consumer sales, while the decline of traditional partners like Amazon may signal a changing landscape or a need for a new strategy with those channels.

- Low-Performing Customers: Two specific customers, Otto and Saturn, are identified as consistently underperforming. This prompts a strategic question: should the company invest resources to improve their performance or cut ties to focus on more profitable relationships?

- Squeezed Margins: The overall gross margin for sales is declining, indicating that while the company is selling more, each sale is becoming less profitable.

### 📢 Marketing View
The marketing insights show that while the team is successfully driving sales volume, they are not addressing the core issue of profitability.

- High Sales, Negative Margins: Every product category is generating high sales, but none are contributing positively to the bottom line. This suggests that the current marketing and pricing strategies are focused solely on driving volume at the expense of profit.

- The "Selling More Isn't Enough" Problem: The data clearly demonstrates that the marketing team needs to pivot from a volume-centric strategy to a value-centric one. This could involve revisiting pricing models, exploring cost-cutting measures in marketing campaigns, or focusing on high-margin product categories.

### 🚚 Supply Chain View
The supply chain dashboard exposes a period of instability and a need for improved demand forecasting.

- Forecast Accuracy Challenges: The dramatic drop in forecast accuracy in March 2020 points to the disruptive impact of the COVID-19 pandemic on the supply chain. This highlights the vulnerability of the company's planning processes to external shocks.

- Inventory Imbalances: The data shows a swing from excess inventory in 2019 to stockouts in 2020. This indicates poor inventory management, which can lead to increased holding costs (excess inventory) or lost sales and customer dissatisfaction (stockouts).

- Significant Improvement: By 2021, the company's demand planning seems to have improved, as evidenced by a significant reduction in stockouts. This shows the company is learning and adapting.

### 📝 Executive View
The executive summary provides a high-level overview of the company's market position, presenting a powerful, but incomplete, story.

- Explosive Market Share Growth: AtliQ's market share has grown exponentially, positioning it as a major competitor in the FMCG space. This is a huge success story and a point of pride.

- The Incomplete Picture: The executive view, while impressive, needs to be paired with the other reports to give a full picture. The rapid market share growth is being achieved at the cost of significant profitability, a trade-off that executives must be aware of to make sound strategic decisions.
   

## Key Outcomes

Delivered a 360° view of business operations.

Empowered stakeholders to make data-driven decisions faster.

Replaced Excel-based analysis with a scalable BI solution.

🙏 Acknowledgements

Special thanks to Dhaval Patel Sir & Hemanand Vadivel Sir for their guidance, entire Codebasics team for their 24x7 support, and Ashish Babaria Sir for inspiring creativity in this project.
