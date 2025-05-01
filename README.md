# 🧪 A/B Testing: E-Commerce Landing Page Redesign

This project analyzes whether a new e-commerce landing page design leads to higher user conversion rates. The goal is to apply A/B testing methodology to real-world data and make a data-driven business recommendation.

## 📌 Project Objective

Determine if the new landing page version significantly increases the conversion rate compared to the existing one.

## 📁 Dataset

- Source: [Kaggle - A/B Testing Dataset](https://www.kaggle.com/datasets/zhangluyuan/ab-testing)
- Fields: `user_id`, `timestamp`, `group`, `landing_page`, `converted`

## 🧰 Tools Used

- R
- tidyverse (dplyr, ggplot2)
- Base R statistical testing (prop.test)
- R Markdown

## 📊 Key Steps

1. Data cleaning (remove mismatched rows and duplicates)
2. Calculate conversion rates by group
3. Visualize group performance
4. Run two-proportion z-test (prop.test) for statistical inference
5. Make a business recommendation

## ✅ Results

- **Conversion Rates**  
  - Control (old page): 12.03%  
  - Treatment (new page): 11.88%

- **p-value:** 0.1918  
- **Conclusion:** No statistically significant improvement from the new design.

## 💼 Business Recommendation

Stick with the current landing page, as there is no clear evidence that the new version improves conversion.

## 📎 Report

View the full R Markdown analysis 👉 [Report HTML](https://github.com/cytkmk/ecommerce-ab-test/blob/main/ecommerce_ab_test.html) 

---

## 🙋‍♀️ Author

Chanya Trakulmaykee  

