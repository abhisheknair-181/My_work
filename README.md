📌 Project Overview
This project performs a Time-Based Cohort Analysis on an e-commerce dataset containing over 500,000 transactions. The objective is to analyze customer retention patterns, identify seasonal sales trends, and provide data-driven recommendations to improve Customer Lifetime Value (CLV).

By grouping users based on their first purchase date (acquisition cohort), we track how engagement evolves over a 12-month lifecycle.

📊 Key Insights
The December 2010 "Power Cohort": This initial cohort showed significantly higher long-term retention compared to subsequent groups, maintaining a ~35% return rate.

The 2011 Q4 Volatility: A sharp spike in sales was observed between August and November 2011, followed by a systemic decline in December across all cohorts.

Retention vs. Quantity: Despite a natural drop in retention after the first month, the average quantity per order remained stable. This indicates that while the platform loses casual shoppers, the "power users" who remain are highly valuable and consistent.

🛠 Tech Stack
Language: Python

Data Manipulation: Pandas, NumPy

Visualization: Seaborn, Matplotlib

Techniques: Data Cleaning, Bivariate Analysis, Pivot Tables, Time-series Transformation

📂 Dataset
The analysis uses ecommerce_cohort_analysis.csv, which includes:

InvoiceNo: Transaction identifier

CustomerID: Unique customer identifier (used for cohort tracking)

Quantity & UnitPrice: Sales metrics

Country: Geographical data for market segmentation

InvoiceDate: The primary timestamp for time-based grouping

🚀 Recommendations
Based on the analysis, the following strategies are proposed:

High-Value Target Marketing: Focus retention efforts on countries where "Quantity per Purchase" is high rather than purely where acquisition is high.

Churn Prevention: Implement a re-engagement campaign specifically for Month 2, where the largest drop in retention occurs across all cohorts.

Stable User Incentives: Reward the "Power Users" identified in the stable average-quantity segments to maximize CLV.

📈 Visualizations Included
Retention Matrix (Heatmap): Visualizing the percentage of active users over time.

Monthly Sales Trends: Identifying macro-economic or seasonal impacts on the business.

Geographical Bar Charts: Comparing quantity vs. customer count by country.

👤 About the Author
Abhishek Nair

MSc Data Science at the University of Greenwich.

6+ Years Professional Leadership in technical consulting and team management.

Passionate about: Sports Analytics (Cricket Predictive Modeling), E-commerce Strategy, and Graph Databases.
