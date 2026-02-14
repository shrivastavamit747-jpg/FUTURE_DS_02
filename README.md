# Customer Retention & Churn Analysis (Task 2)

## 📌 Project Overview
As part of the **Applied AI and Data Science** internship, this project focuses on analyzing customer churn for a subscription-based business. By utilizing both Python for data preprocessing and Power BI for executive-level visualization, I identified key patterns that contribute to customer attrition and formulated data-driven retention strategies.

## 📊 Key Findings & Insights
* **Overall Churn Rate**: Identified a baseline churn rate of **26.58%**, which serves as the primary KPI for this analysis.
* **Customer Lifetime Trends**: Analysis of tenure groups shows that customers are at the highest risk of churning within their **first year** (0-12 months).
* **Retention Drivers**: **Tech Support** and **Online Security** were identified as critical drivers; customers using these services show significantly higher retention rates.
* **Contract Impact**: **Month-to-month** contracts account for over 55% of the total churn volume, suggesting a need for long-term contract incentives.

## 🛠️ Technical Workflow
1. **Data Cleaning (Python)**:
    - Handled missing values in `TotalCharges`.
    - Created a `Tenure_Group` feature to categorize customers into yearly cohorts.
    - Exported refined data for visualization.
2. **Dashboard Design (Power BI)**:
    - Built an interactive dashboard featuring **KPI cards**, **Cohort Analysis**, and **Life Cycle Timelines**.
    - Implemented a "Floating UI" design with a light grey background and white containers for a professional executive look.
    - Integrated **Slicers** (Gender, Senior Citizen, Payment Method) for granular data exploration.

## 📁 Repository Structure
* `Customer_Churn_Analysis.ipynb`: Python notebook containing data cleaning and EDA.
* `Churn_Analysis_Dashboard.pbix`: Final Power BI dashboard file.
* `Telco_Customer_Churn.csv`: The raw dataset used for the project.
