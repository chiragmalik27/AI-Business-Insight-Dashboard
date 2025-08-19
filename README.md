🛒 AI-Powered Business Insights Dashboard








📊 This project builds an AI-powered Business Insights Dashboard using Power BI, with preprocessing in Python.
The goal is to analyze e-commerce sales, customer behavior, and performance metrics to generate actionable insights.

⚡ Project Workflow
1️⃣ Data Collection

Raw dataset: e_commerce_dataset.csv

Contains order ID, customer ID, product details, sales, quantity, price, and order date

2️⃣ Data Cleaning

Removed missing values, duplicates, and inconsistencies

Cleaned dataset: e_commerce_dataset_clean.csv (main file for Power BI)

3️⃣ Data Processing

monthly_metrics.csv → Pre-aggregated sales metrics for time-series analysis

rfm_analysis.csv → Customer segmentation using Recency, Frequency, Monetary (RFM) analysis

4️⃣ Power BI Dashboard Development

📌 Built visuals to answer key business questions:

📊 Sales Trends → Revenue growth by month/year

👥 Customer Segmentation → RFM groups (Loyal, At Risk, Champions, etc.)

🏆 Top Products & Categories → Contribution to revenue

💰 Regional Revenue → Which locations generate the most sales

📦 Order Patterns → Discounts, quantities, shipping analysis

5️⃣ Insights Generation

Used Power BI AI Visuals & Smart Narratives

Identified:
✅ Seasonal demand patterns
✅ High-value customers
✅ Products to stock more / discount less
✅ Retention opportunities

🚀 Getting Started
🔹 Clone the Repository
git clone https://github.com/chiragmalik27/AI-Business-Insight-Dashboard.git
cd AI-Powered-Business-Insights

🔹 Load Data in Power BI

Open Power BI Desktop

Load e_commerce_dataset_clean.csv as the main dataset

Connect supporting datasets:

monthly_metrics.csv

rfm_analysis.csv

Build visuals & publish dashboard

📌 Key Features

✔ Cleaned & structured dataset for analytics
✔ Pre-processed Monthly Metrics & Customer Segmentation
✔ End-to-end Business Intelligence workflow
✔ AI-driven insights using Power BI Smart Narratives

🧑‍💻 Tech Stack
Tool	Purpose
🐍 Python	Data cleaning & preprocessing
📦 Pandas, NumPy	Data wrangling
📊 Power BI	Dashboard & AI-driven insights
📈 Sample Business Insights

🏆 Most valuable customers (RFM Champions & Loyal Customers)

💸 Products driving the highest revenue

📅 Sales seasonality trends (monthly/quarterly spikes)

📍 Top regions contributing to revenue

⚠ At-risk customers who need re-engagement

📷 Dashboard Preview (Screenshots)

👉 (Add screenshots of your Power BI dashboard here)

📜 License

This project is licensed under the MIT License.

✨ With this dashboard, businesses can make data-driven decisions in marketing, inventory, and customer retention.
