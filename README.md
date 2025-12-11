# Ad Campaign Performance Analysis using A/B Testing

# Project Overview
This project analyzes the performance of two online advertising platforms (Facebook Ads vs Google Adwords) to determine which platform delivers better conversions, click-throughs, and cost-effectiveness.  
Using **A/B Testing**, **statistical hypothesis testing**, **regression analysis**, and **time-series insights**, the project answers key marketing questions using real ad campaign data.

---

# Key Business Questions
1. **Which ad platform is more effective** in terms of conversions, clicks, and cost?
2. **How frequently** do high-conversion days occur?
3. **Do more clicks actually lead to more sales?**
4. **Does Facebook significantly outperform Adwords?**  
   (A/B hypothesis test)
5. **What days of the week or times of the month** show the highest conversions?
6. **Is there a long-term equilibrium relationship** between ad spend and conversions?
7. **Which campaign delivers the best ROI?**

---

# A/B Testing Summary
- **Null Hypothesis (H0):** Both platforms generate equal mean conversions.  
- **Alternate Hypothesis (H1):** Facebook generates more conversions than Adwords.

The statistical test results show **Facebook consistently outperforms Adwords**, allowing us to reject the null hypothesis.

---

# Insights from Analysis
# Distribution & Outliers  
- Conversions and clicks are symmetrically distributed with few extreme outliers.

# Platform Comparison  
- Facebook has **more frequent high-conversion days** than Adwords.
- Better engagement, stronger conversion funnel.

# Correlation  
- **Clicks → Conversions:**  
  Correlation coefficient = **0.87** (very strong relationship)  
  → More clicks generally lead to more conversions.

# Regression Analysis  
- Model shows good predictive power.  
- Facebook ad spend strongly predicts conversions.

# Time & Seasonal Trends  
- Conversions remain steady across weekdays.  
- A noticeable trend near mid-month peaks suggests behavioral or strategic triggers.

# Long-Term Relationship  
- Low p-value ⇒ Reject null ⇒  
  **Conversions depend significantly on ad spend.**

---

# Tech Stack
- **Python** – Pandas, NumPy, Matplotlib, Seaborn
- **Statistical Tests** – t-test, A/B test
- **Regression Modeling**
- **Jupyter Notebook**
- **Data Visualization**

---

# Project Structure
data/ ad_data.csv
notebook/ AB_Testing_analysis.ipynb
README.md
requirements.txt
