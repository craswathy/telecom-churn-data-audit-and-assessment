# Telecom Customer Churn Data Audit & Assessment

## 📌 Project Overview
This project focuses on the raw data quality audit, hygiene assessment, and exploratory data analysis (EDA) of a telecom customer dataset. The primary goal is to identify schema inconsistencies, handle missing data, and profile key customer attributes associated with subscriber attrition.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## 🔍 Key Data Engineering & Audit Steps
- **Data Quality Audit:** Evaluated missing values, unexpected data types, duplicate records, and schema inconsistencies across customer records.
- **Data Hygiene & Preprocessing:**
  - Standardized missing value representations and applied appropriate imputations.
  - Converted data types (e.g., casting numerical strings to float/int metrics).
  - Encoded categorical variables for clean exploratory analysis.
- **Exploratory Data Analysis (EDA):** Profiling churn trends across contract types, payment methods, monthly charges, and tenure duration.

## 📊 Key Insights
- **Contract Type:** Subscribers on month-to-month contracts exhibit significantly higher attrition rates compared to 1-year or 2-year subscribers.
- **Tenure:** Customer churn risk decreases steadily as customer tenure increases beyond 12 months.
- **Billing:** Higher monthly charges strongly correlate with increased churn likelihood in unbundled plans.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/craswathy/telecom-churn-data-audit-and-assessment.git](https://github.com/craswathy/telecom-churn-data-audit-and-assessment.git)
