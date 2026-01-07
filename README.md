Customer Behavior Analysis
================================================================================================================================


Overview:

This project presents an end-to-end Customer Behavior Analysis workflow using Python, SQL, and Power BI. The goal is to analyze customer demographics, purchasing behavior, subscriptions, discounts, and revenue trends, and to communicate insights through a dashboard, analytical report, and presentation.
The project demonstrates practical skills in data cleaning, exploratory data analysis (EDA), SQL querying, data visualization, and business insight generation.

Dataset:

The dataset contains 3,900 customer transaction records with attributes related to:
Customer demographics (age, gender, location)
Product information (category, item purchased)
Transaction details (purchase amount, discounts, shipping type)
Customer behavior (previous purchases, purchase frequency, subscription status)
Customer feedback (review ratings)
Tools & Technologies
Python (Pandas, NumPy) – Data loading, EDA, cleaning, and feature engineering
SQL (PostgreSQL / MySQL / SQL Server) – Business-driven analytical queries
Power BI – Interactive dashboard and KPI visualization
Gamma AI – Presentation (PPT) creation
Git & GitHub – Version control and project documentation

Project Steps:

Data Loading:
Imported the dataset using Pandas.

Exploratory Data Analysis (EDA):
Examined data structure using df.info()
Generated summary statistics using df.describe()
Analyzed distributions and key trends.

Data Cleaning:
Handled missing values in review ratings using median imputation by category.
Standardized column names using snake_case.
Removed redundant columns after consistency checks.

Feature Engineering:
Created age_group to segment customers.
Converted purchase frequency into numeric purchase_frequency_days.

SQL Analysis:

Loaded cleaned data into a relational database.
Executed SQL queries to analyze:
Revenue by gender and age group
Subscription impact on spending
Discount usage patterns
Top-performing products and categories
Customer segmentation (New, Returning, Loyal)

Visualization & Reporting:

Built an interactive Power BI dashboard.
Created a structured analytical report.
Designed a professional presentation using Gamma AI.

Dashboard:

The Power BI dashboard includes:

KPI cards for total customers, average purchase amount, and average review rating
Revenue and sales by product category
Revenue contribution by age group
Subscription status distribution
Interactive filters for deeper analysis

Results & Insights:

Clothing is the highest revenue-generating category.
Subscribed customers show higher average spending and total revenue.
Young Adult customers contribute the largest share of revenue.
Discounts do not necessarily reduce spending and can increase basket size.
A strong base of returning and loyal customers indicates good retention.
