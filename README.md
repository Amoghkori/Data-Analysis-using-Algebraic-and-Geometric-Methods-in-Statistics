This repository contains the code and report for the data analysis project conducted as part of the MATH 561 course at the Illinois Institute of Technology. The project aims to explore and analyze real-life data using algebraic and geometric methods in the statistical programming language R. The goal is to gain insights into the relationships between variables and make predictions based on observed data.

## Introduction
The project focuses on applying various statistical techniques to analyze the given dataset and make informed decisions. The analysis includes conducting statistical tests, creating Bayesian network graphs, performing linear regression, and evaluating model fit using goodness of fit tests.

## Data Description
The dataset used for analysis is the "Lung Cancer Prediction" dataset. Unlike the initial TikTok song popularity dataset, this dataset primarily consists of numerical and binary columns, such as age, smokes or not, air pollution, etc. The dataset contains several variables related to lung cancer, including age, gender, air pollution level, alcohol use, genetic risk, and various symptoms.

## Problem Statement
The project aims to analyze the given dataset in a real-world setting and experiment with different models, including graphical, linear, and Gaussian models. The goal is to explore relationships between variables, perform feature selection, and make predictions related to lung cancer.

## Report Contents
1. Correlation Plot: Visualizing and analyzing the correlation between numerical variables.
2. ANOVA Analysis: Conducting a two-way ANOVA to determine significant differences between variable means.
3. Pearson's Chi-Squared Test: Performing a chi-squared test to assess the association between categorical variables.
4. Fisher's Exact Test: Utilizing Fisher's exact test to calculate the exact probability of obtaining observed frequencies in a contingency table.
5. HC Function: Implementing the hill climbing algorithm for optimizing model parameters.
6. BIC - Bayesian Information Criterion: Using BIC to compare different statistical models based on their fit to the data.
7. RMSE - Root Mean Squared Error: Evaluating the accuracy of prediction models using RMSE.
8. Model 1: Graphical Model
    - A. Graphical Model for Entire Dataset: Summarizing the Bayesian network structure and parameters.
    - B. Graphical Model for Marginalized Data: Describing the Bayesian network with selected features based on correlation.
    - C. Graphical Model for Selected Features from ANOVA Analysis: Presenting the Bayesian network with features selected from ANOVA.
9. Model 2: Linear Model
    - A. Linear Model for Entire Dataset: Providing the RMSE score for the linear model using the entire dataset.
    - B. Linear Model for Marginalized Data: Presenting the RMSE score for the linear model using marginalized data.
    - C. Linear Model for ANOVA: Displaying the RMSE score for the linear model using features selected from ANOVA.
    - D. Linear Model with HC-1: Evaluating the performance of the linear model with the HC-1 dataset.
    - E. Linear Model with HC-1 for Marginalized Data: Assessing the performance of the linear model with HC-1 for marginalized data.

## Conclusion
The data analysis project utilized algebraic and geometric methods to explore relationships between variables in the lung cancer prediction dataset. Various statistical tests, Bayesian network modeling, linear regression, and goodness of fit tests were performed. The results and findings are detailed in the report, providing insights into the dataset and facilitating informed decision-making based on the analysis.

For detailed code and analysis, please refer to the R markdown provided in this repository.
