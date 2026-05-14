# Employee Attrition Analysis

## Project Overview
Objective: Identify which employee characteristics are most associated with attrition (voluntary resignation), using exploratory data analysis and statistical correlation. Dataset: IBM-style HR dataset (test.csv) with features including Business Travel, Department, Years at Company, and Percent Salary Hike. This project was developed as part of academic coursework for MSc Data Analytics and demonstrates data cleaning, exploratory data analysis, visualization, and predictive analysis.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scipi
- Google Colab

## Key Insights
Findings
#Business Travel
Frequent travellers had the highest attrition rate (~25%)
Non-travellers had the lowest (~8%), confirming travel burden as a significant attrition driver

#Department
Sales had the highest attrition rate (~21%), followed by HR (~19%)
R&D was the most stable (~14%)

#Tenure (Years at Company)
Infant attrition" (very early leavers) had extremely high rates (~36%) — onboarding/fit issues
Employees in the 1–5 year range also showed elevated attrition (~20%)
Long-tenured employees (20+ years) were the most stable (~8%)

#Salary Hike
Attrition rates were broadly similar across hike bands (11–25%), suggesting salary hike alone is not a strong predictor
Cramér's V Correlation Analysis

Used chi-squared-based Cramér's V to measure association between categorical variables
Business Travel and Department showed the strongest associations with Attrition
Salary Hike had the weakest association — echoes the bar chart findings


## Project Type

Academic Class Project – MSc Data Analytics

## Author

Shivangi Sinha
