📊 Superstore Retail Analytics — Exploratory Data Analysis

🚀 Project Overview

This project performs Exploratory Data Analysis (EDA) on a global Superstore retail dataset to uncover insights about sales performance, profitability, customer segments, and regional trends.

The objective is to transform raw transactional data into meaningful business insights using Python data analysis tools.

Through this analysis we investigate:

• Sales and profit distributions
• Impact of discounts on profitability
• Product category performance
• Customer segment behavior
• Regional and market-level patterns

📂 Dataset Summary

The dataset contains retail transaction records including information about orders, customers, products, and shipping.

Feature	Description
Sales	Revenue generated from an order
Profit	Profit from the transaction
Quantity	Number of items purchased
Discount	Discount applied
Category	Product category
Segment	Customer segment
Market	Global market region
Country	Country of order
City	City where order was placed
Shipping Cost	Cost of shipping

Each row represents one order transaction.

🧰 Tech Stack

Python
Pandas
NumPy
Matplotlib
Seaborn
Google Colab

These tools were used for data cleaning, exploration, visualization, and insight generation.

🔍 Project Workflow
1️⃣ Data Cleaning

Initial preprocessing ensured the dataset was reliable for analysis.

Steps included:

✔ Checking dataset structure
✔ Handling missing values
✔ Removing duplicate records
✔ Dropping irrelevant columns

2️⃣ Univariate Analysis

Analyzed individual variables to understand distributions.

Visualizations used:

📈 Histograms
📦 Boxplots
📊 Distribution plots

Goals:

• Identify skewness
• Detect outliers
• Understand value distributions

3️⃣ Categorical Feature Analysis

Explored categorical features such as:

Category
Segment
Country
City

This helps understand how sales and customers are distributed across groups.

4️⃣ Bivariate Analysis

Investigated relationships between variables.

Examples:

Sales vs Profit
Discount vs Profit
Sales by Category
Profit by Segment

These relationships reveal drivers of profitability and performance differences across segments.

5️⃣ Market & Regional Insights

This analysis explores how performance varies across:

Markets
Regions
Countries

This helps identify geographic demand concentration and global sales patterns.

💡 Key Insights

📌 Sales and profit distributions are right-skewed, indicating most orders are small with a few very large transactions.

📌 Higher discounts show a negative relationship with profit, suggesting excessive discounting reduces margins.

📌 Some product categories generate high sales but inconsistent profits, indicating pricing or cost structure differences.

📌 Orders are concentrated in specific markets and cities, revealing geographic demand clusters.

📁 Repository Structure

Retail-Sales-Analytics-EDA
│
├── superstore.csv

├── retail_sales_eda_analysis.ipynb

└── README.md

🎯 Skills Demonstrated

✔ Data Cleaning

✔ Exploratory Data Analysis

✔ Data Visualization

✔ Statistical Interpretation

✔ Business Insight Generation

✔ Python Data Analysis Stack

👤 Author

Neema Hamza

Aspiring Data Analyst | Data Engineer | Machine Learning Enthusiast

Passionate about transforming raw data into actionable insights and meaningful analytics solutions.
