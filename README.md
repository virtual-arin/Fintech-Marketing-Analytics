# Fintech-Marketing-Analytics 📢

## 💰 Industry Domain

Fintech — Digital Banking & Financial Services

## 🏢 About the Company

NovaPay is a fintech company providing digital banking, savings, and financial products to retail customers. Its marketing team runs targeted campaigns to increase customer adoption of financial products. Management wants analysts to understand customer behavior, campaign performance, and the characteristics associated with successful marketing conversions.

## 🤔 Problem Statement

NovaPay’s marketing campaigns generate large numbers of customer interactions, but conversion rates vary significantly across customer segments and campaign conditions. The company lacks clear evidence about which customer characteristics, contact methods, and campaign factors contribute to successful product subscriptions.


## 🎯 Objective

Analyze NovaPay’s marketing campaign data using exploratory data analysis to identify customer segments, campaign patterns, conversion drivers, and underperforming areas. Develop actionable recommendations for improving targeting, communication strategies, campaign efficiency, and customer conversion rates using data-driven visualizations and statistical insights.

## 📈 Data Source

[Bank Marketing Campaign Dataset](https://www.kaggle.com/datasets/yaminh/bank-marketing-campaign-dataset)

## 🤔 Business Questions

1. **What is the overall conversion rate?**

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/1.conversion_status_distribution.png" width="100%">

2. **Categorical feature univariate distribution**

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/2.categorical_feature_univariate_distributions.png" width="100%">

3. **Numerical feature univariate distribution**

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/3.numerical_feature_univariate_distributions.png" width="100%">

4. **Categorical feature bivariate distribution**

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/4.categorical_feature_distributions_by_conversion_status.png" width="100%">

5. **Numerical feature bivariate analysis**

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/5.numerical_feature_distributions_by_conversion_status.png" width="100%">

6. **Which customer segments have the highest and lowest marketing conversion rates?**

* *students (around 30%) and retired workers (around 23%) have the highest conversion rates while manual worker (around 7%), domestic workers (around 9%) and business owners (around 9%) have lowest marketing conversion rates.*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/6.occupation_vs_conversion_status.png" width="100%">

7. **How does customer age influence the likelihood of subscribing to NovaPay’s financial product?**

* *customers whose age is between 33 to 53 are more likely to be converted*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/7.age_vs_conversion_status.png" width="100%">

8. **Which marital status segments generate the highest conversion rates?**

* *customers who are married are more likely to convert (approx 6.1%) and customers who are single are yet still likely to convert (4.2%).*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/8.marital_status_vs_conversion_status.png" width="100%">

9. **Does education level have a meaningful relationship with customer conversion?**

* *college has the highest conversion rate (approx 15%).elementary school has the lowest conversion performance (approx 8%). Across every single education_level, over 80% of the customer remains unconverted.*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/9.education_level_vs_conversion_status.png" width="100%">

10. **Which marketing contact method produces the highest conversion rate?**

* *mobile has the highest conversion rate meanwhile across all three channels (landline, mobile, unidentified), the majority of customers remain not_converted.*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/10.communication_channel_vs_conversion_status.png" width="100%">

11. **Which months or campaign periods generate the strongest and weakest conversion performance?**

* *customers who were called in the month of may generates the highest conversion rate followed by june, july and august. customers who were called in the month of december and january generates the least conversion. Meanwhile a majority of customers remains not_converted.*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/11.call_month_vs_conversion_status.png" width="100%">

12. **Does the number of times a customer is contacted affect the probability of conversion?**

* *No, high contact frequency does not increases conversion. Both groups share a similarly low median call frequency (1–3 calls). excess calling is literally worthless with extreme outliers (30+ calls) in not_converted customers.*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/12.call_frequency_vs_conversion_status.png" width="100%">

13. **How does a customer’s previous campaign outcome influence their likelihood of converting in the current campaign?**

* *The unidentified and unsuccessful campaign outcome has the highest customer count but a poor converted rate, while successful strongly predicts converted, as it is the only category where converted beats not-converted.*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/13.previous_campaign_outcome_vs_conversion_status.png" width="100%">

14. **Which customer characteristics are most strongly associated with successful conversions?**

* *students and retired workers shows top converting occupations.*

* *age groups of 65+ and <25 shows high conversion rates.*

* *college individuals show the highest academic conversion rates.*

* *single marital status shows better conversion rates than divorce and married.*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/14.successfull_conversion_rates.png" width="100%">

15. **Based on the analysis, which customer segments and marketing strategies should NovaPay prioritize to improve overall conversion rates?**

* **Customer Segments:** *target students and the 65+ age group, as they shows the highest conversion rates and also focus on individuals with a college education and those who are single.*

* **Marketing Strategies:** *prioritize mobile communication channels over landlines. schedule campaigns heavily during march, december, and september, while keeping call durations short for optimal efficiency.*

<img src="https://raw.githubusercontent.com/virtual-arin/Fintech-Marketing-Analytics/main/images/15.Important_Feature_Analysis.png" width="100%">
