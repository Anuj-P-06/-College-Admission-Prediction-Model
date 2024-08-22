# College-Admission-Prediction-Model
## Table of Contents
- [Project Overview.](#project-overview)
- [Reasons for making this project.](#reasons-for-making-this-project)
- [Tools Used.](#tools-used)
- [Tasks Performed.](#task-performed)
- [Results and Findings.](#results-and-findings)

## Project Overview:
This project involves developing a predictive model to assess college admission outcomes using logistic regression. The dataset includes SAT scores, gender, and admission status. Through data analysis and modeling, the project examines the influence of SAT scores and gender on admission decisions. The logistic regression model indicates that both factors are statistically significant predictors of admission.

## Reasons for making this project
Predict Admission Likelihood: To help students assess their chances of being admitted based on key factors like SAT scores.
Data-Driven Decision Making: To assist college admissions committees in making informed, data-backed decisions.
Identify Biases: To explore the impact of variables like gender on admission outcomes, potentially identifying biases.
Improve Application Strategies: To guide applicants in improving their profiles for better admission chances.
Educational Insight: To provide a practical example of logistic regression in predicting categorical outcomes.

## Tools Used:
Jupyter Notebook-->Data Analysis, Data Preprocessing, Exploratory Data Analysis (EDA), Model Building and EvaluationDocumentation, Clustering.

## Task Performed:
### 1) Data Preparation:
- Data Loading: Loaded the dataset containing SAT scores, gender, and admission status.
- Data Exploration: Performed initial exploration to understand the structure and content of the dataset.
- Data Scaling: Scaled the data to prepare it for clustering.
### 2) Logistic Regression:
- Feature Selection: Selected SAT scores and gender as features for predicting college admission.
- Model Building: Built a logistic regression model to predict admission based on the selected features.
- Model Fitting: Fit the logistic regression model to the data.
- Model Evaluation: Evaluated the model using statistical metrics like coefficients, p-values, and summary outputs to interpret the significance of the predictors.
- Model Interpretation: Interpreted the results, focusing on the influence of SAT scores and gender on admission decisions.
### 3 )K-Means Clustering:
- Model Initialization: Initialized the k-means clustering model with a specified number of clusters.
- Model Fitting: Fit the k-means model to the scaled data to identify clusters.
- Cluster Assignment: Assigned each data point to a cluster based on the k-means model.

## Results and Findings:
- The model made had a accuracy of 94.64% for predicting the addmission chance of students.
- The model effectively predicts college admission outcomes using SAT scores and gender, with both factors being significant predictors.
- The model found that higher SAT scores significantly increase the likelihood of being admitted to college.
- K-means clustering provides an additional layer of analysis by segmenting the data into distinct groups, which could be useful for understanding different applicant profiles.
- The model could reveal differences in how SAT scores impact admission chances for different genders, indicating whether one gender benefits more from higher scores.
- By analyzing the characteristics of each cluster, we identify that specific profiles, such as students with low SAT have but high admission rates, suggesting that other factors (not included in the model) are influencing their success.
