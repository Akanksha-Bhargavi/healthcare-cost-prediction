# **Predicting Healthcare Expenditures: A Regression Analysis Approach**

## **Project Description**

- This project investigates factors influencing healthcare expenditures using regression analysis. By leveraging statistical modeling techniques, we aim to identify key determinants of medical costs, evaluate their impact, and develop predictive models for estimating insurance charges.

## **Objectives**

- Analyze the relationship between demographic, behavioral, and health-related factors with medical insurance costs.

- Apply various regression techniques, including Linear Regression and Generalized Linear Models (GLMs), to predict insurance expenditures.

- Evaluate model performance using diagnostic tests and predictive accuracy metrics.

- Provide insights to insurance companies, policymakers, and individuals for better decision-making regarding healthcare expenses.

## **Scope of Project**

- Conduct Exploratory Data Analysis (EDA) to understand data distributions and trends.

- Perform variable selection and multicollinearity diagnostics.

- Implement Simple and Multiple Linear Regression models to assess relationships between variables.

- Address model assumptions using diagnostics and transformations.

- Utilize Generalized Linear Models (GLMs) for improved predictive performance.

- Validate models through error metrics such as RMSE and MAE.

## **Dataset Information**

- The dataset consists of demographic, behavioral, and health-related attributes impacting insurance charges
- Source: Kaggle Insurance Dataset

## **Environment Setup & Dependencies**
- To replicate this project, install the required dependencies
```bash
install.packages("tidyverse")
install.packages("ggplot2")
install.packages("car")
install.packages("MASS")
install.packages("glmnet")
```
## **Reproducibility Guide**
- Clone the repository
```bash
git clone https://github.com/yourusername/healthcare-cost-prediction.git
cd healthcare-cost-prediction
```

## **Results & Findings**

- Exploratory Analysis: Insurance charges are positively skewed, and smokers have significantly higher costs.

- Simple Regression Analysis:Age, BMI, and smoker status have a significant impact on insurance charges.Smoking is the most influential factor, leading to higher costs.

- Multiple Regression:Adjusted R-squared = 0.7494, indicating a strong model fit.Interaction between sex and BMI was examined but had a limited effect.

- Model Diagnostics:Normality and homoscedasticity violations were detected, leading to transformations.

- Generalized Linear Models (GLMs):The inverse Gaussian model provided better predictive accuracy.

- Prediction Accuracy:The GLM model outperformed linear regression in capturing complex relationships.

## **Conclusion**

- This study highlights key drivers of healthcare expenditures, with smoking status, BMI, and age playing significant roles. The transition from Linear Regression to Generalized Linear Models (GLMs) improved prediction accuracy, accounting for data skewness and assumption violations. Future improvements could involve advanced machine learning models to enhance predictive capabilities.

## **References**

- Dataset Source: Kaggle (https://www.kaggle.com/datasets/mirichoi0218/insurance)
- Generalized Linear Models: McCullagh & Nelder (1989) "Generalized Linear Models"
