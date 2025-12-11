#  Ad Campaign Performance Analysis using A/B Testing

#  Project Overview

This project compares Facebook Ads and Google Adwords to determine which platform performs better in terms of conversions, clicks, and cost efficiency. The project uses A/B testing, statistical analysis, regression, and time-based trends to generate insights.

# Business Objectives

1. **Identify which ad platform performs better.**
2. **Analyze the relationship between clicks and conversions.**
3. **Measure the frequency of high-conversion days.**
4. **Conduct A/B hypothesis testing.**
5. **Study day-based and time-based trends.**
6. **Evaluate how ad spend impacts conversions.**
7. **Determine which campaign provides better ROI.**

##  A/B Testing Summary

**H0:** Both platforms have equal average conversions.
**H1:** Facebook has higher average conversions than Adwords.
Statistical results show Facebook performs better, so the null hypothesis is rejected.

## Key Insights

### Distribution and Outliers

Conversions and clicks show near-normal distribution with few outliers.

### Platform Comparison

Facebook has more high-conversion days and stronger engagement.

### Correlation

Clicks and conversions have a strong positive correlation (0.87).

### Regression Analysis

Ad spend, especially on Facebook, strongly predicts conversions.

### Time and Trend Analysis

Conversions remain consistent across weekdays, with a small rise mid-month.

### Long-Term Relationship

Statistical results confirm conversions depend significantly on ad spend.

## Steps Performed

1. **Loaded and reviewed the dataset.**
2. **Cleaned and prepared the data.**
3. **Performed descriptive statistics.**
4. **Conducted exploratory data analysis.**
5. **Compared platform performance.**
6. **Performed A/B and hypothesis testing.**
7. **Built a regression model.**
8. **Checked variable correlations.**
9. **Analyzed time-based patterns.**
10. **Summarized insights and conclusions.**

## Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn), SciPy, Statsmodels, Jupyter Notebook

## Project Structure

project/
data/
ad_data.csv
notebook/
AB_Testing_analysis.ipynb
README.md
requirements.txt

