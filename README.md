# Electric-Vehicle-Count-Prediction

## Project Overview
This project focuses on predicting the number of electric vehicles (EVs) using regression models. The dataset includes vehicle details such as make, model, electric range, base MSRP, and registration county.

## Objective
The goal is to develop an accurate machine learning model that can forecast the EV count, helping policymakers and businesses make informed decisions about EV adoption and infrastructure planning.

## Data Processing & Feature Engineering
✔ Handled missing values using median/mode imputation.
✔ Feature Engineering: Derived vehicle age from model year.
✔ Categorical Encoding: Used Label Encoding for categorical features.
✔ Scaling: Applied StandardScaler to numerical features.
✔ Aggregated data at the county level for better predictions.

## Exploratory Data Analysis (EDA)
📊 Visualized distribution of model year, boxplot of electric range, and feature correlation heatmap to identify trends and relationships.

## Machine Learning Models & Evaluation
We experimented with multiple regression models, fine-tuning them using GridSearchCV & RandomizedSearchCV:

Random Forest Regressor 
Decision Tree Regressor
Support Vector Regressor (SVR)
Linear Regression, Ridge, and Lasso 
Boosting Algorithms: AdaBoost, Gradient Boosting, and XGBoost
## Results & Best Model
📌 Ridge Regression & AdaBoost Regressor achieved the best performance, with the lowest Mean Absolute Error (MAE) and RMSE.
📌 The project demonstrated the importance of feature selection, hyperparameter tuning, and model comparison in improving regression accuracy.

## Tech Stack 🛠️
🔹 Python (pandas, NumPy, scikit-learn, matplotlib, seaborn, XGBoost)
🔹 Machine Learning (Regression, Hyperparameter Tuning, Feature Engineering)
🔹 Data Processing & Visualization

