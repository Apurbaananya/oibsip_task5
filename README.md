# Sales Prediction using Python

Oasis Infobyte Internship Project


![image](https://github.com/Apurbaananya/oibsip_task5/assets/142817867/d3ae3a86-8c04-4a23-8b26-febcf0bfd4d5)

Image courtesy : https://crmech.com/sales-forecasting/

## Problem Statement

The task at hand is to predict future sales for product and service-based businesses. Given the dynamic nature of the market, businesses must anticipate sales figures based on factors such as advertising expenses, audience targeting, and advertising platform choices.

**Challenges**

1. **Variable Impact of Advertising**: Understanding how varying levels of advertising expenditure affect sales.
2. **Audience Segmentation**: Identifying and analyzing diverse audience segments to predict their impact on sales.
3. **Platform Optimization**: Determining the best advertising platforms to maximize sales outcomes.

**Objective**

Develop a machine learning model using Python to predict future sales. The model will offer actionable insights into the relationships between advertising investments, audience segments, and advertising platforms with sales figures.

## Project Summary
**Objective**

The goal of this data science project is to predict future sales for product and service-based businesses. The prediction factors include advertising expenditures, audience segmentation, and advertising platforms.

**Scope**

Sales prediction is essential for businesses, helping them make informed decisions about advertising costs and strategies. The project will use Python for machine learning to forecast future sales.

**Key Components**

1. **Advertising Expenditure Analysis**: Examine the impact of advertising costs on sales predictions.
2. **Audience Segmentation**: Understand how different audience segments affect sales variations.
3. **Platform Influence**: Investigate the role of advertising platforms in determining sales outcomes.

**Implementation**

Python will be used to implement machine learning models, employing techniques such as regression analysis and predictive modeling.

**Outcome**

The project aims to develop a robust sales prediction model that will enable businesses to make data-driven decisions, optimize advertising strategies, and enhance operational efficiency.

## Results
| Sl. no.| Regression Model         | Train R2(%) | Test R2(%) |
| ------ | ------------------------ | ----------- | ---------- |
|    1   | Linear Regression        | 0.894975    | 0.885177   |
|    2   | Linear Regression Tuned  | 0.894975    | 0.885177   |
|    3   | Lasso Regression         | 0.820983    | 0.827435   |
|    4   | Lasso Regression Tuned   | 0.894967    | 0.885461   |
|    5   | Ridge Regression         | 0.894931	  | 0.884211   |
|    6   | Ridge Regression Tuned   | 0.894975    | 0.885168   |
|    7   | Decision Tree            | 1.000000    | 0.954889   |
|    8   | Decision Tree Tuned      | 0.775947    | 0.829328   |
|    9   | Random Forest            | 0.996283    | 0.983694   |   
|   10   | Random Forest Tuned      | 0.817937    | 0.847796   |
|   11   | XGB                      | 1.000000    | 0.984017   |
|   12   | XGB Tuned                | 1.000000    | 0.984017   |

## Conclusion
In the ever-evolving world of product and service-based businesses, forecasting sales is crucial. This project, conducted during a data science internship at Oasis Infobyte, focused on predicting sales using machine learning with Python. Here are the essential insights and conclusions from our work.

**Key Insights**

1. **Advertising Impact**:
   - Sales show a significant positive correlation with TV and radio advertising expenses, underlining the effectiveness of these marketing channels.
   - TV advertising, in particular, has a strong impact on driving sales.

2. **Model Accuracy**:
   - The R2 score was used as the evaluation metric, demonstrating the model's accuracy in predicting sales.
   - The Gradient Boosting model proved to be the best performer, with a training accuracy of 99% and a testing accuracy of 98%.

**Takeaways**

1. **Strategic Insights**:
   - The correlation between advertising expenses and sales provides valuable insights for strategic decision-making.
   - These insights help in effectively allocating resources and optimizing advertising strategies.

2. **Robust Predictions**:
   - The chosen model shows strong predictive capabilities, providing a solid foundation for sales planning.
   - The high R2 score confirms the model's reliability in forecasting sales trends.

**Conclusion**

This project highlights the critical role of data science in optimizing business strategies and predicting sales. The insights gained from this analysis aid in informed decision-making, improving resource allocation and marketing strategies. By leveraging data-driven approaches, businesses can enhance their outcomes and drive growth effectively.
