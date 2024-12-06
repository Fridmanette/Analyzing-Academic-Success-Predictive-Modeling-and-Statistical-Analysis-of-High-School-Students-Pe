# Students-Performance
Academic Students Performance

Data taken from: https://www.kaggle.com/datasets/rabieelkharoua/students-performance-dataset/data

Author: Rabie El Kharoua

DOI: 10.34740/kaggle/ds/5195702

This repository contains a comprehensive data analysis project investigating factors influencing high school students' academic performance, measured by Grade Point Average (GPA). 

Statistical and Machine Learning Methods
1. Analysis of Variance (ANOVA):
- Tested categorical variables for significant differences in mean GPA.
- Identified factors like tutoring, parental support, and extracurricular participation as impactful.

2. Ordinary Least Squares (OLS) Regression:
- Validated assumptions (linearity, independence, homoscedasticity, normality).
- Achieved R² = 0.985, indicating excellent model fit.

3. Causal Inference:
- Applied generalized propensity scores to estimate the causal effect of absences on GPA.

4. Bayesian Regression:
- Provided a probabilistic framework to understand uncertainty in predictions.

5. Logistic Regression (Grade Class):
- Predicted students’ grade categories based on independent variables.
- Achieved 68% overall accuracy with strong precision and recall for certain classes.

Tools and Technologies
Data Processing: Pandas, NumPy
Statistical Analysis: Scikit-learn, Statsmodels
Machine Learning: Logistic regression, Bayesian regression
Visualization: Matplotlib, Seaborn
