## **Analysis of Insurance Data**
# **Overview**
> This project delves into an extensive analysis of medical insurance data. The primary objective is to understand the factors affecting insurance charges and to
develop predictive models to estimate these charges based on various features like age, BMI, smoking status, and more.

# **Dataset**
The analysis utilizes the medical_charge.csv file, which includes several key attributes:

1. age: Age of the primary beneficiary
2. sex: Insurance contractor gender
3. bmi: Body mass index
4. children: Number of children covered by health insurance
5. smoker: Smoking status
6. region: Beneficiary's residential area in the US
7. charges: Individual medical costs billed by health insurance
# **Key Insights and Visualizations**
**Exploratory Data Analysis (EDA):** Conducted a comprehensive EDA to explore age, BMI, smoking status, and their relationships with insurance charges.
Data Visualization: Created various plots to visualize correlations and distributions of key variables.

# **Predictive Modeling**
> Linear Regression

1. Single Feature Analysis: Explored the relationship between age and insurance charges.
2. Multiple Features: Extended the model to include multiple predictors.

> Advanced Regression Techniques
1. Ridge and Lasso Regression: Implemented with hyperparameter tuning for model optimization.

# **Model Improvement and Results**
1. Standard scaling was applied to the features for better model performance.
2. The models were evaluated based on their Root Mean Square Error (RMSE) and coefficients.
3. Optimal hyperparameters were identified for both Ridge and Lasso regression models.

# **Conclusion**
This project highlights the significance of different factors in predicting insurance charges. Advanced regression techniques like Ridge and Lasso were effective in improving the model's performance, showcasing their utility in handling complex datasets.

# **How to Run the Notebook**
1. Clone the repository.
2. Ensure Jupyter Notebook is installed.
3. Navigate to the notebook and open it via Jupyter Notebook.

# **Requirements**
Python 3.x
**Libraries:** pandas, numpy, matplotlib, seaborn, sklearn
