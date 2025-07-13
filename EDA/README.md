# 💳 Credit Card Exploratory Data Analysis (EDA) Project

## 📝 Project Overview
This project undertakes a comprehensive Exploratory Data Analysis (EDA) of a credit card dataset, focusing on both customer demographics and transaction behavior.  
The **core objective** is to reveal crucial **patterns, relationships, and trends** in card usage and financial metrics — ultimately delivering actionable insights for:
- Strategic product development  
- Targeted marketing campaigns  
- Enhanced customer retention  

### 📁 Notebook Structure
- `Credit_CardEDA.ipynb`: Transaction-level data including usage patterns, expense types, credit limits, annual fees, and monthly trends.
- `Customer_Dataset_EDA.ipynb`: Customer demographics such as age, income, education level, job, and their relationship with customer satisfaction.

---

## 🔍 Key Insights

### 📂 From Transaction Data (`Credit_CardEDA.ipynb`)
- **Transaction Methods**  
  “Swipe” is the dominant transaction method, far more frequent than “Chip” or “Online” transactions.

- **Expense Patterns**  
  “Bills” are the most frequent expense type, followed by “Entertainment” and “Fuel”. “Travel” is the least common.

- **Card Categories**  
  The “Blue” card category dominates the dataset. Premium cards like “Platinum” and “Gold” are rare.

- **Financial Metrics Trends**  
  Metrics like *Customer Acquisition Cost*, *Annual Fees*, *Credit Limit*, *Total Transaction Amount*, *Volume*, and *Interest Earned* show monthly fluctuations, often peaking around **July-August**.

- **Credit Limit & Fees**  
  These are assigned in discrete tiers. There is **no strong linear correlation** between them or with total transaction amounts.

- **Transaction Amount vs Volume**  
  A **strong positive linear relationship** exists — higher spending corresponds to more transactions.

- **Outlier Retention**  
  Outliers in metrics like *Credit Limit*, *Total Transaction Amount*, *Volume*, *Annual Fees*, *Customer Acquisition Cost*, and *Interest Earned* were **intentionally retained**. These represent **high-value customers** or **unique card characteristics**.

---

### 👥 From Customer Demographics (`Customer_Dataset_EDA.ipynb`)
- **Data Quality**  
  The dataset is **clean** with **no missing values**, ensuring reliable analysis.

- **Age Distribution**  
  Varies by gender — reveals **demographic segmentation**.

- **Job & Satisfaction**  
  Different job categories exhibit **distinct average customer satisfaction scores**.

- **Education & Income**  
  Income levels vary significantly with education — highlighting **economic disparities**.

- **Education & Satisfaction**  
  Satisfaction scores **vary across education levels** as well.

---

## 🧰 Technologies Used
- **Python**: Programming Language  
- **Pandas**: Data manipulation and analysis  
- **NumPy**: Numerical operations  
- **Matplotlib**: Data visualization  
- **Seaborn**: Enhanced statistical data visualization  

---
