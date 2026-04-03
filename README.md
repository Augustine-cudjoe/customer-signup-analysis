# Customer Sign-Up Behaviour & Data Quality Analysis

## 📌 Project Overview
This project analyses customer sign-up behaviour for a SaaS company (Rapid Scale) and performs a data quality audit on the dataset. The goal is to generate insights that support business decisions in marketing and onboarding.

---

## 📊 Dataset
- Customer dataset: 300 records
- Fields include:
  - customer_id, signup_date, source, region
  - plan_selected, marketing_opt_in, age, gender

---

## 🧹 Data Cleaning
- Handled missing values (email, region, age, etc.)
- Standardised inconsistent categories (e.g., PRO → Pro)
- Converted data types (dates to datetime)
- Removed duplicates and invalid records

---

## 📈 Key Insights
- Weekly sign-ups remained stable (avg. 6–7 users)
- Peak sign-up reached 13 users, minimum dropped to 1
- Google was the top acquisition source in the most recent period
- Premium plan was the most selected overall
- Pro users generated the highest support requests

---

## 📉 Data Quality Issues
- Missing values in key fields (email: 11.3%, region: 10%)
- Presence of unknown acquisition sources (NaN values)
- Inconsistent categorical data

---

## 💡 Recommendations
- Focus marketing efforts on high-performing channels (Google, Instagram)
- Improve tracking using UTM parameters
- Enhance onboarding for Pro and Basic users

---

## 🛠 Tools Used
- Python (Pandas, NumPy)
- Jupyter Notebook
- Data Cleaning & Analysis Techniques

---

## 📎 Project Files
- `customer_signup_project.ipynb` – Analysis notebook
- `report.pdf` – Final report

---

## 🚀 Author
Augustine Cudjoe

