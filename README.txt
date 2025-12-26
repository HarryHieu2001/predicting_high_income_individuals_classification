This dataset, sourced from the UCI Machine Learning Repository, is based on the 1994 U.S. Census.

Its goal is to classify adults into two income groups:

<=50K USD per year

>50K USD per year

By analyzing factors such as education, gender, race, and occupation, the study aims to understand how these variables influence income levels in the 1990s.These insights also help reveal social and economic patterns

- Data Dictionary
Features 	Description
Age		Age of the individual in years.
Workclass	Employment type or class of the worker.
fnlwgt		a sampling weight indicating the number of people the record represents in the population.
education	Highest level of education attained.
education-num	Numerical representation of education level
marital-status	Marital status of the individual.
occupation 	Type of job or occupation.
relationship	Relationship of the individual to others in the household.
race		Race of the individual.
sex		Gender of the individual.
capital-gain	Capital gains from investments
capital-loss	Capital losses from investments.
hours-per-week	Average number of working hours per week.
native-country	Country of origin of the individual.
salary		Income class of the individual.


Type of job or occupation.
This is my very first Data Analysis & Machine Learning project!

I’m so excited to share my final project — “Predicting High-Income Individuals”, where I built a classification model to predict whether a person earns more than $50K per year using the UCI Adult Income dataset.

Project Overview
The dataset comes from the 1994 U.S. Census and includes demographic and employment-related features such as age, education, occupation, working hours, and gender.
The goal is to classify individuals into two income groups:
≤50K USD
>50K USD
By analyzing these factors, I aimed to explore which attributes most influence income levels and how they reflect broader social and economic patterns.

Key Steps
Data cleaning & preprocessing (handling missing values, encoding, scaling)
Exploratory Data Analysis (EDA) using Python & visualization
Dealing with imbalanced data using SMOTE
Training and comparing 4 models:
Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting
Hyperparameter tuning to optimize model performance.

Result Highlights
  The Gradient Boosting model achieved the best overall performance:
    Accuracy: 0.81
    ROC-AUC: 0.887
    Balanced precision and recall
    Top income-related factors: education level, age, and working hours per week.

Key Insights
Individuals earning >50K tend to be older, more educated, work longer hours, and often hold professional or managerial positions.
Those earning ≤50K are younger, often work fewer hours, and mostly employed in private sectors or service jobs.

Tools & Skills Used
Python | Pandas | Matplotlib | Seaborn | Scikit-learn | SMOTE | Machine Learning | EDA | Model Evaluation


This project helped me gain hands-on experience in the full data analysis pipeline — from raw data to actionable insights and model evaluation.
