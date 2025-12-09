# 📊 Marketing Funnel Analysis — Customer Journey & Conversion Optimization

This project analyzes the marketing funnel performance of a retail brand by understanding how customers move from **awareness → engagement → campaign interaction → final conversion**.  
The goal of the analysis is to identify drop-offs, segment customer behavior, and generate actionable insights that help improve marketing effectiveness and overall ROI.

This project was executed end-to-end with a complete data analytics pipeline including **data cleaning, EDA, KPI calculation, segmentation, funnel mapping, and insight generation.**

---

## 🚀 Project Objectives

- Understand customer behavior across the marketing funnel  
- Identify **bottlenecks** where customers drop off  
- Analyze spending patterns and engagement behavior  
- Study campaign performance using past campaign acceptance  
- Provide **business recommendations** to improve conversions  
- Present insights that support **data-driven marketing decisions**

---

## 🧠 Dataset Overview

The dataset contains detailed customer information with 29 columns including:

| Feature Category      | Description |
|-----------------------|-------------|
| **Demographics**      | Year of birth, education, marital status, income |
| **Household Info**    | Number of kids/teens in home |
| **Customer Activity** | Web visits, store purchases, catalog purchases |
| **Spending Behavior** | Wines, meat, fish, sweets, gold products |
| **Campaign Data**     | AcceptedCmp1–5, Response (latest campaign) |
| **Churn Indicators**  | Complaint history, recency |

✔ Total Rows: **2240**  
✔ Funnel-related columns: **WebVisits, Purchases, Campaign Acceptance, Response**

---

## 🔽 Funnel Definition (Based on Dataset)

### 🟦 Stage 1: Awareness  
- `NumWebVisitsMonth` → Measures visibility and website interest  

### 🟦 Stage 2: Engagement  
- `NumWebPurchases`  
- `NumCatalogPurchases`  
- `NumStorePurchases`  
- `NumDealsPurchases`  
- Spending columns (`MntWines`, `MntMeatProducts`, etc.)

### 🟦 Stage 3: Campaign Interaction  
- `AcceptedCmp1` to `AcceptedCmp5` → Past campaign acceptance  

### 🟦 Stage 4: Conversion (Final Response)  
- `Response` → Whether the customer accepted the latest campaign  

This funnel structure helps analyze the complete customer journey from awareness to conversion.

---

## 📈 Key Insights

- High website visits did **not always** lead to purchases → awareness does not guarantee engagement.  
- High-spending customers (especially in Wines, Meat, Gold products) showed **higher campaign conversion rates**.  
- Deal-driven purchases increased engagement but **did not guarantee** campaign conversion.  
- Past campaign acceptance was a **strong predictor** of the latest campaign response.

---

## 🎯 Business Recommendations

- Target high-value customers with personalized premium campaigns.  
- Improve website and catalog purchasing experience to reduce early drop-offs.  
- Use historical campaign acceptance to personalize offers.  
- Retarget high-visit, low-purchase users with optimized messaging.

---

## 🛠️ Tools & Technologies Used

- **Python** → Pandas, NumPy, Seaborn, Matplotlib  
- **MySQL** → Data extraction and SQL-based insights  
- **Jupyter Notebook** → Data cleaning & EDA  
- **PowerPoint** → Insights presentation for stakeholders  

---

## 📂 Project Deliverables

| File                         | Description |
|------------------------------|-------------|
| `Marketing_jupyterr.ipynb`   | Full EDA, funnel mapping, KPI analysis |
| `presentation.pptx`          | Stakeholder presentation |
| `README.md`                  | Documentation |

---

## 🏆 Project Impact

- Identified the main drop-off stage in the marketing funnel  
- Improved understanding of customer segments & behavior  
- Delivered actionable insights to improve **marketing ROI**  
- Enabled better campaign targeting using behavioral patterns  

---
