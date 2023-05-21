# Sales-Analysis-Impact-of-TV-and-Radio-Promotions-on-Sales
Analyzing the relationship between TV and radio promotions and their impact on sales using linear regression.

This repository contains the code and findings from a comprehensive analysis of the relationship between promotional budgets and sales. The project employs exploratory data analysis techniques and develops linear regression models to understand the impact of different promotional channels on sales. The key takeaways and results from the analysis are summarized below.

**Key Takeaways:**
- Data visualizations and exploratory data analysis were utilized to assess the suitability of linear regression for modeling the relationship between promotional budgets and sales.
- The results of the linear regression models provide insights into the relationship between promotional budgets and sales, allowing for interpretations and predictions.

**Results:**
- In the simple linear regression model, the y-intercept was determined to be 41.5326, and the slope was estimated as 8.1733. This suggests that, on average, a 1 million dollar increase in the radio promotion budget could lead to an 8.1733 million dollar increase in sales.
- The results of the regression analysis indicated statistical significance with a p-value of 0.000, implying a significant relationship between radio promotion budget and sales.
- The 95% confidence interval for the slope of the regression model was found to be [7.791, 8.555], providing a range within which the true value of the slope is likely to fall with 95% confidence.

Findings for External Stakeholders: Based on the dataset and regression analysis, we observed a substantial relationship between radio promotion budget and sales for companies represented in the data. Increasing the radio promotion budget by 1 million dollars is estimated to result in an average sales increase of 8.1733 million dollars. These findings suggest that continued investment in radio promotion is beneficial. Further exploration of the relationship in different contexts, such as industry or product-specific analyses, is recommended to gain a deeper understanding.

**Considerations and Key Findings:**
- Exploratory data analysis techniques were employed to identify a suitable variable for the simple linear regression model.
- The validity of the model assumptions was checked before interpreting the results.
- Measures of uncertainty, including p-values and confidence intervals, were provided to enhance the understanding of coefficient estimates.

Findings to Share with Others:
- Sales were distributed relatively evenly between $25 and $350 million across all promotions.
- TV demonstrated the strongest linear relationship with sales, followed by radio and social media.
- The R-squared value for the simple linear regression model with TV as the independent variable was 0.999, indicating that nearly all the variation in sales can be explained by the TV promotion budget alone.
- The estimated coefficients for the intercept and TV promotion budget had statistically significant p-values (0.000) and confidence intervals ([3.558, 3.565]), supporting the relationship between TV promotion budget and sales.

**Considerations and Key Takeaways:**
- Box-plots were used to visualize the distribution of sales across different promotions.
- One-way ANOVA was applied to assess significant differences among the means of three or more groups.
- ANOVA post hoc tests revealed detailed pairwise differences between promotions.

**Summary for Stakeholders:**
High TV promotion budgets significantly increase sales compared to medium and low TV promotion budgets. Switching from a high to medium TV promotion could reduce sales by approximately $75 million, and switching from a high to low TV promotion could decrease sales by about $154 million. Additionally, a $1 million increase in the radio promotion budget is predicted to result in a $2.97 million increase in sales. Therefore, it is recommended to prioritize a high promotional budget for TV and invest in radio promotions to maximize sales.
