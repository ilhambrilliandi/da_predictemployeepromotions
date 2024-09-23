# Data Analysis: Epmloyee Promotion

This is a project of end-to-end analysis, including data preprocessing, visualization and predicting using several methods. Providing insights about what takes the biggest role on promotions, and find the best department based on promotion rates in a year.

Conclusion:
- Overfitting occured on LogR and SVM models because of imbalanced data.
- Tested on 6 models, lightgbm is the fittest.
- 429 people (3.3%) of all employees predicted will get promoted in 2024.
- Education level and department have important role in determining promotion.
- Based on promotion, the most accomplished departments are Sales & Marketing, Operations, and Procurement.
- Bachelors got the most promoted employees by number, and Masters & Above by percentage. Note that no Below Secondary employees got promoted.
- Recruitment Channel has important role in determining promotion. Other is the most by number, and Referred by percentage (4.55%).
- Promotion distribution by gender relatively even.

Recommendation:
- Use hyperparameter tuning or other resampling method.
- Employees' performance can be improved by conducting training, Below Secondary employees need to be the focus.
