### Interpretable ML I
### Introduction

This notebook uses a [Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/code) database and attempts to compare predicting the likelihood of customer churn using linear regression, logistic regression and a logistic general additive model

For all models, the assumptions required for each model were tested and discussed thoroughly before fitting. This includes for:

1. Linear Regression:
    - Linearity
    - Independence of Observations
    - Homoscedasticity
    - Normality
    - No multicollinearity
    - No autocorrelation
2. Logistic Regression:
    - Linearity
    - Independence of Observations
    - No multicollinearity
    - Large sample size
3. Logistic GAM:
    - Independence of Observations
    - No multicollinearity
    - Homoscedasticity
    - Large sample size
  
### Citations:

1. https://www.kaggle.com/datasets/blastchar/telco-customer-churn/code

2. https://www.geeksforgeeks.org/detecting-multicollinearity-with-vif-python/

3. https://godatadrive.com/blog/basic-guide-to-test-assumptions-of-linear-regression-in-r

4. https://en.wikipedia.org/wiki/Homoscedasticity_and_heteroscedasticity#Testing

5. https://bookdown.org/rwnahhas/RMPH/mlr-linearity.html
