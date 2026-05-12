# 🏥 Hospital Readmission Analysis

## Project Overview
This project analyzes U.S. healthcare data to identify geographic and clinical trends in 30-day hospital readmissions. The goal is to pinpoint high-risk regions and specific medical conditions that drive readmission rates, providing actionable strategic recommendations for hospital resource allocation.

## 🔍 Methodology
1. **Data Cleaning:** Conducted a thorough data audit, filtering for specific readmission measures while removing mortality rates and redundant hospital-wide averages to ensure a focused clinical analysis.
2. **Analysis:** Segmented healthcare data into two primary categories:
    * **Geographic Analysis:** Identifying regional clusters with higher-than-average readmission risks.
    * **Clinical Analysis:** Comparing readmission rates across specific medical conditions to find outliers.
3. **Visualization:** Built insight-driven horizontal bar charts and pivot tables to highlight regional disparities and critical condition risks.

## 📊 Interactive Analysis
[**👉 View the Live Analysis (Google Sheets)**]([\https://docs.google.com/spreadsheets/d/1t6EhAcCa6kLhx1Xu5zV3DEctJA5GOBEdhle7QmE_ZLk/edit?usp=sharing]

## Key Findings & Strategic Recommendations
* **Regional High-Risk Areas:** Analysis identified that **60% of the top 10 states** with the highest readmission rates are located in the **South** (MS, AR, KY, WV, TN, and AL).
    * *Strategic Recommendation:* Investigate regional healthcare infrastructure in the Southeast to identify specific barriers like rural access or outpatient clinic shortages contributing to these higher rates.
* **Clinical Outliers:** Patients treated for **Heart Failure** face the most significant risk, with readmission rates near **22% which is nearly 5 times higher** than surgical recovery for Hip/Knee replacements.
    * *Strategic Recommendation:* Prioritize **more intensive transition programs** for Heart Failure and respiratory patients, such as enhanced discharge education and mandatory 48-hour follow-up calls.

## Data Source
* **Dataset:** [US Healthcare Readmissions and Mortality (Kaggle)](https://kaggle.com)
* **Key Metrics:** State, Measure Name (Condition), and Average Score (Readmission Rate %).
