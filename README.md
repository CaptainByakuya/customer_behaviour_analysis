🛍️ Customer Shopping Behavior Analysis

📘 Project Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI.
The analysis explores purchasing patterns, customer demographics, and product preferences from 3,900 anonymized transactions to uncover insights that can guide marketing strategies and business decisions.

🧰 Tools & Technologies

Python (Pandas, NumPy, Matplotlib, Seaborn) – Data cleaning, exploration, and feature engineering
PostgreSQL – SQL queries for structured data analysis
Power BI – Interactive dashboards and visual storytelling
Microsoft Excel / CSV – Dataset formatting and initial inspection

📊 Dataset Summary

Rows: 3,900
Columns: 18
Key Features:
Customer demographics: Age, Gender, Location, Subscription Status
Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
Shopping behavior: Discount Applied, Promo Code Used, Previous Purchases, Review Rating, Shipping Type
Missing Values: 37 in Review Rating column
Dataset Source:
The dataset was obtained from an open online source and represents anonymized customer shopping transactions used for educational and analytical purposes.

🧮 Exploratory Data Analysis (Python)

Cleaned and standardized dataset (snake_case column names)
Handled missing values in the Review Rating column using median imputation by product category
Created new features:
age_group – customer age binned into ranges
purchase_frequency_days – derived from purchase history
Verified redundancy between discount_applied and promo_code_used
Loaded cleaned data into PostgreSQL for further analysis

🗃️ SQL Analysis

Performed SQL queries in PostgreSQL to answer key business questions, including:
Revenue by Gender – comparison of total revenue by male vs. female customers
Top Product Categories – identification of high-performing categories
Customer Subscription Impact – correlation between subscription and spending behavior

📈 Power BI Dashboard

An interactive Power BI dashboard was created to visualize:
Customer segmentation by demographics and subscription status
Product category performance
Revenue trends and seasonal spending patterns
Review ratings distribution

💡 Key Insights & Recommendations

Boost Subscriptions: Promote exclusive benefits for subscribers to improve retention.
Review Discount Policy: Balance discount frequency with profit margins.
Product Positioning: Highlight top-rated and best-selling products in marketing campaigns.
Targeted Marketing: Focus efforts on high-revenue age groups and express-shipping users.

📜 License

This project is released under the MIT License.
You are free to use and modify the materials with proper credit.

👤 Author

Kareem Temitope
📧 [temitopejoseph27@yahoo.com]
🔗 [LinkedIn](http://linkedin.com/in/temitope-kareem-3ab8b3153)
