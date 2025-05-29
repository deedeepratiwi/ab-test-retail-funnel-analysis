# A/B Test Analysis – Online Retail Conversion Funnel

This project evaluates the impact of a product change on conversion rates using A/B testing techniques. The analysis was performed using the Online Retail dataset and basic statistical testing in Python.

## 🔍 Objective

To determine whether the variant group (Group B) led to a statistically significant improvement in user conversion rate compared to the control group (Group A).

## 📊 Dataset

Synthetic dataset based on the Online Retail dataset, structured with:
- Group assignment (A or B)
- User sessions and conversions
- Funnel steps (Product Viewed → Added to Cart → Purchased)

## 🧪 Methodology

- Funnel conversion rate calculated for both groups
- Statistical hypothesis testing using Z-test for proportions
- Significance level set at 0.05

## ✅ Result

- Z-statistic: 0.77
- P-value: 0.4416
- Conclusion: No statistically significant difference between Group A and B conversion rates

## 📈 Tools & Libraries

- Python (pandas, scipy, matplotlib)
- Jupyter Notebook
- SQL (for initial data exploration if needed)

## 📂 Files

- `ab_test_analysis.ipynb`: Jupyter Notebook with full analysis
- `data/online_retail_ab_test.csv`: Sample dataset
- `images/funnel_chart.png`: Optional funnel visualization

## 📌 Takeaway

The tested product feature did not result in a statistically significant uplift in conversions. Suggest further investigation or test with a larger sample size.
