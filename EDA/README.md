Credit Card Exploratory Data Analysis (EDA) Project
Project Overview
This project undertakes a comprehensive Exploratory Data Analysis (EDA) of a credit card dataset, delving into customer demographics and transaction behavior. The core objective is to reveal crucial patterns, relationships, and trends in card usage and financial metrics, ultimately delivering actionable insights for strategic product development, targeted marketing campaigns, and enhanced customer retention.

The analysis is divided into two main parts, explored in separate Jupyter notebooks:

Credit_CardEDA.ipynb: Focuses on transaction-level data, including card usage patterns, expense types, credit limits, annual fees, and their monthly trends.

Customer_Dataset_EDA.ipynb: Explores customer demographics, such as age, income, education level, job, and their relationship with customer satisfaction.

Key Insights
Through this EDA, several key insights were uncovered:

From Transaction Data (Credit_CardEDA.ipynb):
Transaction Methods: "Swipe" is the dominant transaction method, significantly more frequent than "Chip" or "Online" transactions.

Expense Patterns: "Bills" represent the most frequent expense type, followed by "Entertainment" and "Fuel," while "Travel" is the least common.

Card Categories: The "Blue" card category overwhelmingly dominates the dataset, with premium categories like "Platinum" and "Gold" being very rare.

Financial Metrics Trends: Various financial metrics (e.g., Customer Acquisition Cost, Annual Fees, Credit Limit, Total Transaction Amount, Total Transaction Volume, Interest Earned) exhibit clear monthly fluctuations, with many showing peaks during mid-year (e.g., July-August).

Credit Limit & Fees: Credit limits and annual fees are assigned in discrete tiers, and there isn't a strong linear correlation between them or with total transaction amounts.

Transaction Amount vs. Volume: A strong positive linear relationship exists between total transaction amount and total transaction volume, indicating higher spending generally corresponds to more transactions.

Outlier Retention: Outliers in metrics like Credit Limit, Total Transaction Amount, Total Transaction Volume, Annual Fees, Customer Acquisition Cost, and Interest Earned were intentionally retained. These extreme values are considered genuine data points, representing high-value customers or unique card characteristics crucial for comprehensive insights.

From Customer Demographics (Customer_Dataset_EDA.ipynb):
Data Quality: The dataset is clean with no missing values, ensuring reliability of analysis.

Age Distribution: Age distribution varies by gender, providing insights into different demographic segments.

Job & Satisfaction: Distinct average customer satisfaction scores are observed across different job categories.

Education & Income: Average income levels vary significantly with education level, highlighting economic disparities.

Education & Satisfaction: Customer satisfaction scores also show variations across different education levels.

Technologies Used
Python: Programming Language

Pandas: Data manipulation and analysis

NumPy: Numerical operations

Matplotlib: Data visualization

Seaborn: Enhanced statistical data visualization
