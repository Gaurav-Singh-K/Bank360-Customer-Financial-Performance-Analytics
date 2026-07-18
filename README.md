# 🏦 Bank Customer Churn  Analysis

## 📌 Project Overview

Customer retention is one of the most important challenges in the banking industry. Acquiring a new customer is significantly more expensive than retaining an existing one. This project analyzes customer demographics, financial behavior, account activity, and banking products to identify the factors associated with customer churn and provide actionable business recommendations.

The project demonstrates an end-to-end data analytics workflow using Python, including data understanding, cleaning, feature engineering, exploratory data analysis (EDA), KPI creation, and business insights.

---

# 🎯 Business Objective

The objective of this project is to:

* Understand customer demographics and financial behavior.
* Identify factors influencing customer churn.
* Analyze customer activity and banking product usage.
* Discover high-risk customer segments.
* Generate actionable business recommendations to improve customer retention and business performance.

---

# 📂 Dataset

**Dataset:** Bank Customer Churn Dataset

The dataset contains customer-level banking information, including:

* Customer Demographics
* Credit Score
* Geography
* Gender
* Age
* Tenure
* Account Balance
* Number of Products
* Credit Card Ownership
* Active Membership Status
* Estimated Salary
* Customer Churn (Exited)

---

# 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 📊 Project Workflow

### 1. Business Understanding

* Defined the business objective.
* Identified analytical questions related to customer retention.

### 2. Data Understanding

* Dataset overview
* Metadata interpretation
* Data type validation
* Missing value analysis
* Duplicate record analysis

### 3. Data Cleaning

* Removed unnecessary columns.
* Validated dataset quality.
* Confirmed data consistency.

### 4. Feature Engineering

Created business-driven features including:

* Credit Score Group
* Age Group
* Tenure Group

These derived features simplify customer segmentation and improve business analysis.

### 5. KPI Development

Key performance indicators developed include:

* Total Customers
* Active Customers
* Male vs Female Customers
* Credit Card Holders
* Risk Profile Distribution
* Average Credit Score
* Average Balance
* Average Salary
* Average Customer Age
* Average Tenure
* Average Products per Customer

### 6. Exploratory Data Analysis

Customer Analysis

* Customer distribution by geography
* Gender distribution
* Age group distribution
* Customer tenure
* Active vs inactive customers

Financial Analysis

* Balance distribution by geography
* Balance distribution by age group
* Balance distribution by tenure
* Salary distribution
* Credit score distribution
* Balance vs salary relationship
* Credit score vs balance relationship
* Zero-balance customer analysis

Churn Analysis

* Overall churn rate
* Churn by geography
* Churn by gender
* Churn by age group
* Churn by tenure
* Churn by active membership

Product Analysis

* Product usage distribution
* Customer product adoption

Risk Analysis

* High-risk customer identification
* High-value inactive customer analysis

---

# 📈 Key Business Insights

* Germany represents the highest-risk regional market, exhibiting the highest churn rate despite leading in both average account balance and average credit score. Similarly, new customers represent a volatile, high-value segment with elevated churn rates alongside high average balances and strong credit profiles.
* The 51–60 age demographic represents a critical attrition point, showing the highest churn rate coupled with the highest average balance.
* ustomers utilizing only one product hold the majority of the total balance amount and exhibit high churn. Due to the massive size of this cohort, it poses the highest financial risk to the business.
* Customer segmentation based on age and tenure provides valuable insights into retention strategies.
* High-value inactive customers represent an opportunity for targeted engagement campaigns.
* Product adoption and customer activity play an important role in long-term customer loyalty.

---

# 💡 Business Recommendations

Prioritize the German Market:
Launch targeted retention campaigns in Germany. Because this market has the highest average balances and zero zero-balance accounts, mitigating churn here yields the highest immediate return on investment (ROI).

Optimize Onboarding for New High-Value Customers:
Introduce structured introductory benefits, personalized onboarding flows, or loyalty rewards for new customers to stabilize retention during their high-risk initial lifecycle phase.

Execute a Product Cross-Selling Strategy:
Develop targeted cross-selling initiatives (e.g., moving single-product users to two products) to deepen customer engagement, secure the large volume of capital held by this group, and lower their propensity to churn.

Investigate Mature Demographic Pain Points:
Conduct targeted qualitative research or customer care outreach for the 51–60 age bracket to identify and resolve specific service friction points causing high-balance attrition.

Address Capital Inactivity in France & Spain:
Design regional financial products or high-yield incentive structures specifically for France and Spain to encourage zero-balance customers to deposit capital.
---

# 🚀 Future Improvements

Future versions of this project will include:

* Interactive Power BI Dashboard
* SQL-based business analysis
* Customer churn prediction using Machine Learning
* Executive dashboard for business stakeholders

---

# 📁 Repository Structure

```text
Bank-Customer-Churn-Analysis/

│── data/
│── notebooks/
│── images/
│── README.md
│── requirements.txt
```

---

# 👨‍💻 Author

**Gaurav Singh**

Aspiring Data Analyst passionate about transforming data into actionable business insights using SQL, Python, Excel, and Power BI.

**Skills:** Python | SQL | Pandas | NumPy | Matplotlib | Seaborn | Power BI | Excel | Business Analytics
