# Lung_Capacity_Prediction

This repository contains code for building a regression model to predict lung capacity based on various factors such as age, height, smoking status, gender, and whether the individual was delivered via Caesarean section.

## Dataset

The dataset used for this regression model contains the following variables:

1. LungCap: Lung capacity (target variable)
2.Age: Age of the individual
3.Height : Height of the individual
4.Smoke : Smoking status (0 for non-smoker, 1 for smoker)
5.Gender: Gender of the individual (0 for male, 1 for female)
6.Caesarean: Whether the individual was delivered via Caesarean section (0 for no, 1 for yes)

## Regression Model

We built a regression model using the lung capacity data with the following steps:

1. Data preprocessing: Handling missing values, encoding categorical variables, etc.
2. Splitting the data into training and testing sets.
3. Building the regression model using techniques such as linear regression, random forest regression, etc.
4. Evaluating the model's performance using metrics like Mean Squared Error, R-squared, etc.
