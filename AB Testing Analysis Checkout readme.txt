# 🧪 A/B Testing Analysis: Checkout Optimization

## 📌 Project Overview

This project analyzes an A/B test conducted by an e-commerce company to evaluate a redesigned checkout experience.

The goal is to determine whether **Variant B (new checkout)** improves:
- Conversion Rate
- Revenue per User

and to provide a **data-driven recommendation** for product deployment.

---

## 🎯 Business Problem

The company is experiencing **low checkout conversion rates** despite high user traffic, leading to potential revenue loss.

To address this, a redesigned checkout flow (Variant B) was introduced to reduce friction and improve user experience.

---

## 🧠 Objective

- Compare performance of Variant A (Control) vs Variant B (New)
- Measure:
  - Conversion Rate
  - Revenue per User
- Perform statistical testing
- Estimate business impact
- Recommend whether to deploy the new version

---

## 🗂️ Dataset

- ~20,000 users
- Features include:
  - user_id
  - group (A/B)
  - user_type (New/Repeat)
  - timestamp
  - conversion (0/1)
  - revenue
  - add_to_cart

---

## ⚙️ Tools & Technologies

- Python (Pandas, NumPy)
- Matplotlib
- Statsmodels (Z-test)
- Jupyter Notebook

---

## 📊 Key Analysis Steps

### 1. Conversion Analysis
- Calculated conversion rate for both groups
- Compared total conversions and user counts

### 2. Statistical Testing
- Used **two-proportion Z-test**
- Validated significance of conversion improvement

### 3. Revenue Analysis
- Computed revenue per user
- Calculated total revenue per group
- Estimated revenue uplift

### 4. Segmentation Analysis
- Compared performance across:
  - New vs Repeat users

### 5. Trend Analysis
- Analyzed daily conversion trends
- Verified stability and consistency of results

---

## 📈 Key Results

- Conversion Rate:
  - Variant A: ~9.9%
  - Variant B: ~12.3% (**+24% uplift**)

- Statistical Significance:
  - p-value < 0.05 ✅

- Revenue Impact:
  - ~₹32K additional revenue during experiment

---

## 💰 Business Impact

- Improved conversion directly increased revenue
- Repeat users contributed strongly to uplift
- Results are consistent over time → reliable improvement

---

## 🚀 Final Recommendation

✅ **Deploy Variant B**

Expected outcomes:
- Higher conversion rate
- Increased revenue per user
- Improved overall business performance

---

## 📊 Visualizations

- Conversion Rate Comparison
- Revenue Comparison
- Daily Conversion Trend
- Segment Analysis (New vs Repeat users)

---

## 🧠 Key Learnings

- Importance of statistical significance in decision making
- Translating data insights into business impact
- Evaluating experiment consistency over time
- Segment-level insights can uncover deeper opportunities

---

## 📌 Conclusion

This project demonstrates how A/B testing can be used to drive **data-driven product decisions** by combining:

- Statistical validation  
- Business impact analysis  
- Behavioral insights  

---

## 👤 Author

**Abhishek K**  
Aspiring Data Analyst | Python | SQL | Power BI

---