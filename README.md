# HR-ATTRITION-ANALYSIS-

**Project Overview**
-----------------
This project analyzes employee attrition using a dataset from a fictional HR system. The goal is to identify key factors that influence employee turnover and develop a predictive model to forecast attrition risk. Additionally, the project provides actionable recommendations and a visual summary through a Power BI dashboard.

**Objectives**
-----------------
-Understand patterns and drivers behind employee attrition.

-Build a machine learning model to predict attrition.

-Visualize HR insights using Power BI.

-Provide prevention suggestions to reduce future attrition rates.

**Deliverables**
-----------------
1.Power BI Dashboard:
A comprehensive dashboard showing:
Attrition by Department.
Attrition by Gender.
Attrition by Years of Working.
Attrition based on Overtime.

📎 Output: [HR Attrition Analysis.pdf]

2.Model Accuracy Report + Confusion Matrix:
Trained classification model using Logistic Regression.
Accuracy score and confusion matrix for performance evaluation.
Data preprocessing and feature engineering steps included.

3.Attrition Prevention Suggestions

A PDF summarizing actionable steps HR teams can take based on data insights and model outcomes.

**Tools & Technologies**
-------------------------------
Python (Pandas, Scikit-learn, Seaborn, Matplotlib)

Jupyter Notebook

Power BI Desktop

CSV Dataset: Cleaned HR data file (cleaned_hr_data.csv)

** Data Analysis & Modeling Steps**
-------------------------------------------
1. Data Cleaning
Loaded the HR dataset and removed irrelevant columns.
Handled categorical variables through encoding.
Checked for missing values and ensured data consistency.

2. Exploratory Data Analysis (EDA)
Identified major factors correlating with attrition:
Department,
Gender,
Overtime,
Years at company.
Used visual plots for clearer interpretation of attrition patterns.

3. Model Building
Chose classification algorithm (Logistic Regression ).
Split data into training and test sets.
Trained the model and calculated:
Accuracy and
Confusion Matrix.

5. Power BI Visualization
Imported dataset into Power BI,
Created clean, HR-friendly visuals for actionable insight,
exported dashboard to PDF format.

** Key Insights**
----------------------------
Employees working overtime have significantly higher attrition rates.
The Research & Development department sees the most attrition.
Early-career employees (0–5 years) are at higher risk.
Gender distribution also shows variance in attrition patterns.
