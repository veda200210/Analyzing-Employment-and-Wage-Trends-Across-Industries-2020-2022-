**Overview**

This project explores employment and wage trends in the U.S. from 2020 to 2022 using data from the Quarterly Census of Employment and Wages (QCEW). The goal is to uncover patterns in industry growth, wage distributions, and job market changes during and after the COVID-19 pandemic.

Using Python and a combination of statistical analysis and machine learning, the project seeks to identify key drivers of employment growth and provide actionable insights for businesses, policy makers, and analysts.

**Key Questions Explored**

1. Which industries have shown the most significant growth or decline in employment?

2. How have average wages changed across sectors from 2020 to 2022?

3. What are the predictors of wage levels across different job sectors?

4. Can we model and forecast employment or wage trends using regression techniques?


**Tools and Technologies Used**


- Python – for data manipulation and analysis

- Pandas – to clean and explore the dataset

- Seaborn & Matplotlib – for data visualization

- Scikit-learn – for implementing machine learning models

- Statsmodels – for statistical analysis and hypothesis testing

- Jupyter Notebook – to document and present the analysis

- QCEW Data – publicly available labor statistics dataset (qcew-2020-2022.csv)

**Data Preparation**

- The notebook begins with:

- Importing relevant Python libraries

- Loading the QCEW dataset

- Performing exploratory data analysis to understand data distributions, missing values, and variable types

- Cleaning the dataset to remove inconsistencies

**Analysis Highlights**

**Descriptive Analysis**

- Employment and wage distributions across years and sectors

- Outlier detection and removal

- Correlation heatmaps to identify relationships among numeric variables

**Statistical Testing**

- ANOVA and hypothesis tests to determine wage differences across industries

- Regression modeling (OLS) for wage prediction

**Machine Learning Models**

- Linear Regression, Ridge, and Lasso for salary prediction

- Random Forest and Gradient Boosting for advanced regression modeling

- Model evaluation using R² and RMSE

**Results & Insights**

- **Wage disparities** exist across industries, with certain tech and finance roles seeing the highest growth.

- **Statistical models** indicate significant predictors of wage, such as industry, year, and employment levels.

- **ML models** enhance prediction accuracy, with Gradient Boosting performing particularly well in terms of R² score.

**Conclusion**

This project demonstrates how combining statistical reasoning with machine learning techniques can offer deep insights into employment trends. Understanding these patterns is crucial for strategic workforce planning and economic forecasting.
