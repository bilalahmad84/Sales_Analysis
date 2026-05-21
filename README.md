# Sales_Analysis
Sales Data Analysis using Python — EDA, A/B Testing, Forecasting &amp; Customer Segmentation
A complete sales data analysis project built with Python in Jupyter Notebook, structured around 10 analytical questions — 5 foundational and 5 advanced — covering business performance, customer behavior, marketing effectiveness, and machine learning-based predictions.

🔍 Project Overview
This project explores a sales dataset to extract meaningful business insights using Python's data science ecosystem. The analysis progresses from basic KPIs to machine learning models, making it a full end-to-end analytical workflow.

📁 Dataset
The dataset (sales_data.xlsx) contains fields including Order ID, Order Date, Customer ID, Customer Segment, Region, Country, Category, Subcategory, Net Sales, Profit, Marketing Campaign, and Website Conversion status.

✅ Basic Analysis

Business Overview — Total revenue, total profit, and average order value
Category Performance — Sales and profit comparison across product categories
Regional & Country Sales — Identifying top-performing regions and countries
Monthly Trends — Time-series view of how sales and profits shift month over month
Campaign Conversion Rates — Comparing website conversion rates across marketing campaigns
Bonus — Top 10 most profitable product subcategories


🚀 Advanced Analysis

Customer Segment Value — Aggregating sales, profit, and order frequency per segment to identify the most valuable customer groups
Margin Risk Detection — Scatter analysis to flag products with high sales volume but low profit margins
Statistical A/B Testing — Chi-Square test (scipy.stats) to determine whether differences in campaign conversion rates are statistically significant
Sales Forecasting — Linear Regression model (scikit-learn) trained on monthly time-series data, evaluated using MAE and R² score
K-Means Customer Segmentation — Unsupervised clustering of customers by spending, profit contribution, and order frequency, with StandardScaler normalization


🛠️ Tools & Libraries
Language: Python | Environment: Jupyter Notebook
pandas · numpy · matplotlib · scipy · scikit-learn

💡 Key Takeaways
This project demonstrates how Python can power the full analytics pipeline — from loading raw Excel data to delivering statistical tests and predictive models — providing actionable insights for sales strategy, customer targeting, and campaign optimization.
