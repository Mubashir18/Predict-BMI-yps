# Predict-BMI-yps
Python project analyzing how lifestyle and behavioral habits predict BMI in young people using OLS and Ridge regression.
# What Lifestyle and Behavioral Habits Predict BMI in Young People?

This repository contains a regression analysis project exploring whether it is possible to predict the Body Mass Index (BMI) of young people based on their self-reported lifestyle and behavioral habits. The analysis uses the "Young People Survey" dataset.

## Author
**Khanzada Mubashir Hassan**
HSE University

## Project Structure

* analysis.ipynb: The main Jupyter Notebook containing the data preprocessing, exploratory data analysis (EDA), and regression modeling (OLS and Ridge Regression) in Python.
* YPS.csv: The Young People Survey dataset used for the analysis.
* report: The comprehensive final report, detailing the research question, methodology, findings, and conclusion.

## Overview

The goal of this project was to establish the correlation between behavioral habits (like time spent on active/passive sports, healthy eating, spending on gadgets, smoking, and alcohol consumption) and BMI. 

Two regression models were compared:
1. **Ordinary Least Squares (OLS) Linear Regression**: For establishing individual statistical significance and effects of predictive variables.
2. **Ridge Regression**: For modeling and shrinking multicollinear features.

### Key Findings
* Demographic factors (Age and Gender) were the most significant predictors of BMI.
* Being male and getting older show strong positive correlations with a higher BMI in this youth dataset.
* Most of the purely behavioral metrics (like healthy eating and active sport) demonstrated very weak predicting power when gender and age were controlled, mainly because self-reported behavioral answers on simple 1-5 scales hold high attenuation bias.
* The Ridge model yielded slightly more stable predictions across folds, validating OLS insights.

## Requirements

To run the analysis.ipynb notebook, the following Python libraries are generally needed:
* pandas
* numpy
* statsmodels
* scikit-learn
* matplotlib
* seaborn

You can install the necessary dependencies using pip:
pip install pandas numpy statsmodels scikit-learn matplotlib seaborn
