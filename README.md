# Customer_Behaviour_Analysis
Data Analytics Project Showcasing Customer Behavior Analysis Using Python, SQL, Power Bi.
🔎 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The objective is to understand spending patterns, customer segments, product performance, discount behavior, and subscription trends to support data-driven business decisions.

The workflow follows a complete analytics lifecycle:

1) Load and explore data using Python

2) Perform EDA and cleaning

3) Run SQL business queries in PostgreSQL

4) Build an interactive Power BI dashboard

5) Prepare a report summarizing insights

6) Create a clean PPT presentation using Gamma

📂 Dataset Description

Rows: 3,900

Columns: 18

Type: Customer shopping transactions

Key Features

Demographics: Age, Gender, Location, Subscription Status

Purchase Info: Item Purchased, Category, Purchase Amount, Season, Size, Color

Behavior: Discount Applied, Previous Purchases, Purchase Frequency

Feedback: Review Rating

Shipping: Standard / Express

Data Quality

37 missing review ratings → filled using category-wise median

Dropped redundant columns (e.g., promo_code_used)

Standardized column names (snake_case format)

🛠 Tools & Technologies
Tool                                                                                     Purpose                          
-------------------------------------------------------------------------------------------------------------
 Python (Pandas, NumPy, Matplotlib)           Data loading, EDA, cleaning      
 Jupyter Notebook                                             Analysis environment             
 PostgreSQL + SQLAlchemy                             SQL querying & database analysis 
 Power BI                                                             Dashboard & visual insights      
 Gamma                                                                Final project presentation       
 PDF Report                                                         Written summary of insights 

🚀 Steps Performed

1️⃣ Data Loading (Python)

Loaded the CSV file using Pandas

Reviewed structure with info() and summary stats with describe()

Identified missing values and data types

2️⃣ Exploratory Data Analysis (EDA)

Distribution analysis for age, purchase amount, ratings

Revenue trends across gender, age groups, and shipping types

Identified top categories and products

Visualized patterns using bar charts, histograms, and correlations

3️⃣ Data Cleaning

Imputed missing review ratings

Removed redundant fields

Created new features:

age_group

purchase_frequency_days

Ensured consistency in discount and subscription fields

4️⃣ SQL Business Analysis (PostgreSQL)

Using your SQL file, the following were analyzed:

Revenue by gender

Discount users who spent above average

Top 5 highest-rated products

Standard vs Express shipping comparison

Subscribers vs Non-Subscribers revenue

Top products within each category

Customer segments: New, Returning, Loyal

Relationship between repeat buyers and subscription

Revenue by age group

5️⃣ Dashboard (Power BI)

The dashboard includes:

Revenue by gender (Male ~68%, Female ~32%)

Customer segmentation (New, Returning, Loyal)

Subscription vs Non-Subscription spend

Product performance and ratings

Discount behavior analysis

Shipping type comparison

Category-wise and product-wise insights

6️⃣ Final Report

A detailed PDF summarizing:

Dataset overview

Python EDA

SQL results

Dashboard findings

Business recommendations

7️⃣ PPT (Gamma)

A clean and professional presentation covering:

Problem Overview

Analysis Steps

Insights & Visuals

Final Recommendations

📊 Results & Insights
⭐ Key Findings

Male customers contribute ~68% of total revenue, almost double female customers.

839 discount users still spent above the average purchase amount → strong promotional opportunity.

Top-rated products include Gloves, Sandals, Boots, Hat, and Skirt.

Loyal customers dominate, with 3,116 buyers making multiple repeat purchases.

Express shipping users spend more on average than standard shipping customers.

Young adults and middle-aged customers generate the highest revenue.

⭐ Recommendations

Promote subscription plans—73% non-subscribers is a growth opportunity.

Strengthen loyalty programs to support the large repeat-buyer segment.

Review discount strategy for high discount-dependent products.

Highlight top-rated products in marketing campaigns.

Focus marketing on high-value age groups and express-shipping buyers.
