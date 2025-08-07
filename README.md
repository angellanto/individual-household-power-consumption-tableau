# Design & Implementation of E2E Pipeline using Snowflake and Tableau
## Dataset Source: https://archive.ics.uci.edu/dataset/235/individual+household+electric+power+consumption
## Tableau: https://public.tableau.com/app/profile/angel.lanto/viz/HouseholdElectricPowerConsumption/Dashboard
## Snowflake: https://app.snowflake.com/viyauhd/av36986/w3Yd7aRtDrHP#query
### Business Intelligence | Individual Assignment Grade: 94/100
### Professor Comment:
This is a highly professional and technically rigorous assignment that demonstrates clear alignment with the objectives of an end-to-end BI pipeline. You framed the business problem well — reducing peak consumption and improving energy efficiency — and supported it with a rich, real-world dataset that spanned multiple years at a minute-level frequency.

Your ETL pipeline in Snowflake was strong. You applied data cleaning, timestamp parsing, handling of missing values, and numerical casting using SQL logic. You also implemented thoughtful feature engineering (e.g., peak hour labels, weekday/weekend categorisation) and built both a minute-level and an aggregated daily-level table, which improved analytical flexibility and dashboard performance. This modular and scalable design reflects a mature approach to pipeline building.

Your SQL queries were comprehensive and well targeted. You explored usage patterns across time, appliance types, and days of the week. You also included variability checks, anomaly detection, and correlation analysis — a standout in terms of technical completeness.

The Tableau dashboard followed the expected layout: KPIs and summary indicators at the top, trends and consumption patterns in the middle, and drill-down elements including heatmaps and anomaly flags at the bottom. The design supported exploration by policy analysts or energy planners, and the interactivity was well described.

Referencing was consistent, and the entire report showed strong clarity and structure.
### Assignment Instructions:
Description of Assignment:

You will design and implement a data pipeline to solve a real-world business problem using a large-scale dataset. The pipeline will handle data extraction, transformation, storage, analysis, and visualization, culminating in insights presented via an interactive Tableau/LookerStudio dashboard and a final report.

You should aim to work with large-scale datasets from a real-world domain, extracting insights to solve a business problem for instance:

E-Commerce & Customer Review Analytics (example questions for this domain)
• Business Problem: Identify key customer sentiment trends, fake reviews, and pricing impact on ratings
Three Key Insights to Extract:
• Analyze customer sentiment using reviews
• Detect fake reviews using frequency and text analysis (e.g., find reviews per reviewer, find reviewers posting multiple reviews a day etc.)
• Compare product pricing vs. rating trends
• Expected Visualizations (Tableau)
• Sentiment trends, top-reviewed products, fake review detection
Healthcare & Patient Appointment Analytics (example questions for this domain)
• Business Problem: Improve hospital scheduling and no-show patient predictions.
Three Key Insights to Extract:
• Identify peak hospital admission times
• Analyze no-show trends by patient demographics
• Forecast ICU occupancy to optimize resources
• Expected Visualizations (Tableau)
• Occupancy heatmaps, patient no-show patterns, predictive scheduling
Energy & Sustainability Analytics (example questions for this domain)
• Business Problem: Optimize power consumption and renewable energy planning.
Three Key Insights to Extract:
• Analyze regional electricity demand patterns
• Compare renewable vs. non-renewable power usage
• Forecast future energy demand
• Expected Visualizations (Tableau)
• Regional energy usage trends, renewable energy impact, demand forecasting
ETL Pipeline in Snowflake
• Extract: Ingest JSON or CSV data into Snowflake
• Transform: Clean & structure data
• Load: Store in structured tables for analysis
SQL Queries & Insights
• Write queries to extract business insights from the dataset
• Document transformations applied
Tableau Dashboard
• Create an interactive BI dashboard showcasing key findings
Final Report (3-4 Pages - 1,250 words (+/- 10%))
• Business problem statement & dataset details
• Step-by-step ETL pipeline explanation
• SQL queries & Tableau insights
 

