Customer Shopping Behavior Analysis 🛍️
1. Project Overview
This project focuses on analyzing a retail company's consumer behavior dataset to identify key trends and optimize marketing strategies. The analysis aims to help management understand purchasing patterns across various demographics and sales channels (online vs. offline) to improve long-term customer loyalty.

2. Dataset Summary
Records: 3,900 rows of transactional data.

Features: Includes demographics (age, gender), purchase details (item, category, amount, season), and shopping behavior (discounts, review ratings, shipping type).

Quality: Addressed 37 missing values in the "Review Rating" column during data preparation.

3. Tech Stack & Tools
Data Preparation: Python (Pandas) for cleaning and feature engineering.

Analysis: PostgreSQL for structured data queries.

Visualization: Power BI for building interactive dashboards.

Presentation: Gamma AI for stakeholder communication.

4. Implementation Steps
Python EDA: Imported the dataset, performed initial exploration, and standardized columns for better readability.

Data Cleaning: Imputed missing ratings using median values and handled redundant features like promo_code_used.

Database Integration: Loaded the cleaned dataset into PostgreSQL for deeper analysis.

SQL Analysis: Queried revenue metrics by gender and age group to find primary spending drivers.

Dashboarding: Designed a Power BI dashboard to enable data-driven decision-making for stakeholders.

5. Results & Insights
Top Revenue Source: The 20-40 age group is the highest contributor, generating $91,392 in revenue.

Consumer Trends: Review ratings and discount applications are major factors driving repeat purchases.

Strategic Outcome: Recommended focusing marketing efforts on the high-performing 20-60 age demographic.

6. How to Run
All Python scripts and SQL queries are documented in this repository for reproducibility.

To view the full strategic presentation, refer to the uploaded report and presentation materials.# Customer_Shopping_Behavior_Analysis
Data Analytics project showcasing customer behavior analysis using python, sql and power Bi.
