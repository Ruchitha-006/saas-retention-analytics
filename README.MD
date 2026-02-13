# 📊 SaaS Retention Analytics – Churn Event Analysis

## 🔎 Project Overview

Customer churn is one of the most critical metrics in subscription-based (SaaS) businesses.  
This project analyzes churn event data to understand why customers leave, identify churn patterns, and suggest data-driven retention strategies.

The analysis simulates real-world work done by product, growth, and retention teams.

## 🎯 Business Objectives

- Analyze churn event trends over time
- Identify top churn reasons
- Examine upgrade/downgrade behavior before churn
- Measure refund impact on revenue
- Provide actionable retention recommendations


## 📁 Dataset Description

The dataset contains **600 churn events** with the following key columns:

- `churn_event_id` – Unique churn record ID  
- `account_id` – Customer account identifier  
- `churn_date` – Date of churn  
- `reason_code` – Reason for churn  
- `refund_amount_usd` – Refund issued after churn  
- `preceding_upgrade_flag` – Whether customer upgraded before churn  
- `preceding_downgrade_flag` – Whether customer downgraded before churn  
- `is_reactivation` – Whether the account was previously reactivated  
- `feedback_text` – Customer feedback  


## 🛠️ Tools & Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Jupyter Notebook  


## 📊 Analysis Performed

### 1️⃣ Data Cleaning
- Converted date columns to datetime
- Verified data types
- Created time-based features

### 2️⃣ KPI Analysis
- Total churn events
- Reactivation rate
- Upgrade/downgrade before churn %
- Average refund amount

### 3️⃣ Churn Reason Analysis
- Top churn reasons
- Refund amount by reason

### 4️⃣ Trend Analysis
- Monthly churn trend visualization


## 🔍 Key Insights

- A small number of reason codes drive majority of churn.
- Customers who downgrade before churn show higher exit probability.
- Reactivation rate indicates some customers return after churn.
- Refunds represent direct revenue impact.
- Monthly churn patterns suggest periodic spikes.


## 🚀 Business Recommendations

- Monitor downgrade behavior as an early churn signal.
- Improve customer support in top churn reason categories.
- Introduce targeted retention campaigns before churn.
- Create reactivation campaigns for past churned users.
- Track refund trends to minimize revenue loss.


## 📈 Project Outcome

This project demonstrates the ability to:

- Perform structured churn analysis
- Extract business insights from event-level data
- Translate analysis into actionable recommendations
- Build a portfolio-ready SaaS analytics case study.