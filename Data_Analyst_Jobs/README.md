Objective
To analyze global data analyst job listings and predict salaries based on company characteristics, job ratings, and industry type. The project aims to identify the most in-demand skills, top-paying industries, and factors influencing analyst compensation.

## Tools & Technologies
- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Machine Learning:** Random Forest Regressor
- **Data Sources:** Public job listing datasets
- **Other Tools:** Excel, SQL for data preprocessing

##  Process Overview
1. Collected and cleaned job listing data (handled missing values and irregular salary formats).
2. Standardized features like `Rating`, `Company Name`, `Industry`, and `Location`.
3. Extracted numeric salary data using regex and feature engineering.
4. Built regression models to predict salary based on job attributes.
5. Visualized trends by company type, industry, and experience level.

##  Challenges Faced
- Missing and inconsistent salary fields.
- Non-uniform data types and outliers.
- Feature encoding and handling categorical attributes efficiently.

## Results & Insights
- Strong correlation observed between **company rating and salary**.
- **Top-paying sectors:** Finance, IT, and Analytics Consulting.
- Random Forest model provided the most reliable salary predictions.

## Key Learnings
- Data preprocessing for text and numeric features.
- Regression modeling and hyperparameter tuning.
- Visualizing relationships between job roles and compensation.
