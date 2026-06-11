# Medical_Insurance_Pricing_Analysis
Exploratory Data Analysis and LM and Gamma GLM modeling of medical insurance prices using R.

## Project Overview

This project investigates the factors that influence medical insurance charges using exploratory data analysis and statistical modelling in R.
The goal was to identify which customer characteristics contribute most strongly to insurance pricing and to build an appropriate predictive model for insurance charges.

## Dataset

Variables for the medical insurance cost include:

- Age
- Sex
- BMI
- Number of Children
- Smoking Status
- Region
- Insurance Charges

## Methods

- Exploratory Data Analysis (EDA)
- Linear Regression
- Log-Linear Regression
- Interaction Modelling
- Gamma Generalised Linear Models (GLMs)

## Key Findings

- Smoking status was the strongest predictor of insurance charges.
- BMI and smoking status interacted strongly.
- Age showed a consistent positive relationship with insurance costs.
- The Gamma GLM with a log link and Smoker × BMI interaction provided the best model fit.

## Tools Used

- R
- Tidyverse
- ggplot2
- Jupyter Notebook

## Future Improvements

Future models could incorporate:

- Previous claims history
- Occupation risk category
- Medical history
- Lifestyle factors
- Policy type
- Income

These variables could help predictive performance.
Machine learning techniques such as Random Forests, Gradient Boosting, or XGBoost could also be investigated and compared against the statistical models used in this project. This would allow evaluation of predictive performance on unseen data and provide insight into how well the model generalises to new customers.
