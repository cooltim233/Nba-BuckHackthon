# Nba-BuckHackthon

Obejective:
Optimizing game schedule:The Milwaukee Bucks are curious to learn more about how we can optimize our home game schedule for Business Operations. Is there a way to construct a realistic schedule that maximizes revenue? What are the optimal factors related to the schedule that we can leverage for each team

Data Description
![image](https://github.com/cooltim233/Nba-BuckHackthon/assets/120356932/ae61c1d9-d779-4fc6-be9f-bbcf004ca86a)

1.Data Exploration and Cleaning:
Initial dataset exploration for structure, missing values, and anomalies.
Applied relevant preprocessing, handling missing values and outliers.

2.Exploratory Data Analysis (EDA)
binary-continuous variables correlation with TotalRevenue
box plot for all components potentially affect TotalRevenue

3.Feature Engineering & Pre-processing:
Dropped redundant columns.
One-hot encoded categorical variables.
Scaled numerical features with standardization.
Chose a neural network for its ability to capture complex relationships.
Trained the model on the training data, monitored MAE during training.
Model Evaluation:
Evaluated model performance on training and validation datasets.
Visualized MAE over epochs for insights and overfitting assessment.

4.Insights & Recommendations:
Extracted feature importance using SHAP values and Random Forest.
Provided recommendations based on insights for schedule optimization.

5.Schedule Optimization(8 Games In Mouth):
Utilized linear programming (LP) with pulp library to maximize revenue.
Objective: Maximize total expected revenue while adhering to constraints.
Proposed an optimal game schedule based on expected revenues.
