# FUTURE_DS_02 – Facebook Ads Performance Dashboard

A Power BI dashboard created during Data Science Internship Task 2, analyzing Facebook ad campaigns to uncover insights on spend, engagement, conversion rates, and ROI.

---

# Project Overview
- **Objective**: Build a data-driven dashboard to evaluate ad performance, optimize spending, and guide campaign decisions.
- **Tools**: Power BI Desktop (2024+), DAX, Microsoft Excel (for initial data prep).

---

# Included Files
- `FUTURE_DS_02.pbix` – Power BI dashboard file
- `dataset_facebook_ads.csv` – Raw CSV dataset (sourced from Kaggle)
- `README.md` – This file

---

## Key Metrics & Calculations:

| Metric              | Calculation |
|---------------------|-------------|
| CTR (%)             | (Clicks / Impressions) × 100 |
| CPC (₹)             | Spent / Clicks |
| Conversion Rate (%) | (Total Conversions / Clicks) × 100 |
| ROI (%)             | ((Total Conversions × ₹500) – Total Spent) / Total Spent |

> ₹500 assumed revenue per conversion (adjustable as needed).

---

## How to Use This Dashboard

### 1. Open the Dashboard
- Ensure you have Power BI Desktop installed.
- Download `FUTURE_DS_02.pbix` from this repo.
- Open the file using Power BI Desktop.

### 2. Review Data Model
- Navigate to the Model View to confirm table `data` includes the imported CSV.
- You can adjust the conversion value by updating the ROI measure in Modeling → New Measure.

### 3. Refresh Data (Optional)
- To test with your own dataset:
  - Replace `dataset_facebook_ads.csv` in Power Query.
  - Click Home → Transform Data → Refresh Preview.
  - Click Close & Apply to update visuals.

### 4. Explore Visuals
- Top Row: KPI cards – Spend, Impressions, Clicks, CTR.
- Middle Section: Charts – ROI by campaign; CTR trends by age & gender; Spend vs Clicks.
- Bottom Section: Table – Ad-level details with CTR, CPC, demographics.

### 5. Interact with Dashboard
- If slicers are configured (or added), use them to filter by:
  - Age group  
  - Gender  
  - Campaign ID

---

## Insights & Takeaways
- Audience engagement: Females aged 23–29 show highest CTR and best cost-efficiency.
- Top performers:  
  - Ad ID 1121683 (CTR = 25%)  
  - Campaign 107 (highest ROI)
- Optimization focus:  
  - Ads with high impressions but low engagement should be refreshed.

---

## Written Insights & Recommendations

A detailed analysis has been documented in:

📄 [`final_recommendations.txt`](insights/final_recommendations.txt)

It includes:
- Audience performance breakdowns  
- Ad-level insights  
- ROI analysis  
- Strategic recommendations to optimize future ad campaigns

---

## Dataset sourced from Kaggle: Facebook Ads Performance.

---

### Feedback & Suggestions
I’d love to hear your thoughts! Feel free to open an Issue if you find bugs, or want to collaborate.

---

## Connect with Me

- 💼 [LinkedIn](https://www.linkedin.com/in/somya-das-30715b262/)  
- 🐱 [GitHub](https://github.com/Somyaaaaaaaaa)  
