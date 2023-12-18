# AutoML

In this assignment, we explore the predictive modeling of flight delays using two distinct approaches: H2O.ai and Statsmodels. Our analysis begins with data exploration, preprocessing, and splitting into training, validation, and test sets. In the H2O.ai framework, we employ AutoML with hyperparameter tuning and evaluation metrics to assess model performance, ultimately selecting a Gradient Boosting Machine model with specific hyperparameters. Simultaneously, the Statsmodels approach involves linear regression analysis to understand the significance of predictor variables, revealing the importance of airline, flight, and time-related factors. Our findings provide a comparative analysis of these modeling techniques, highlighting the selected H2O.ai model's predictive accuracy and insights from the Statsmodels linear regression, shedding light on their respective strengths and weaknesses in predicting flight delays. These results have implications for airline operations and passenger satisfaction, enabling data-driven decision-making in the aviation industry.

I have tried to answer the following questions:

- Is the relationship significant?
- Are any model assumptions violated?
- Is there any multicollinearity in the model?
- In the multivariate models are predictor variables independent of all the other predictor variables?
- In in multivariate models rank the most significant predictor variables and exclude insignificant ones from the model.
- Does the model make sense?
- Does regularization help?
- Which independent variables are significant?
- Which hyperparameters are important?
