# Heart Disease Prediction Using Machine Learning Approach

## Project Overview

**Project Title**: Heart Disease Prediction  

This project builds a machine learning classification model to predict the likelihood of heart disease based on clinical attributes. It includes data cleaning, exploratory analysis, feature engineering, model development, ensemble learning, and performance evaluation.
The final solution provides a reliable end-to-end ML workflow suitable for healthcare analytics and early disease-risk detection.

## Objectives

1. **Set up a retail sales database**: Create, format, and populate a complete SQL database to store and manage retail sales data.
2. **Data cleaning & preparation**: Fix data-type issues, remove duplicates, and handle missing values to ensure accuracy and consistency.
3. **Exploratory Data Analysis (EDA)**: Analyze key dimensions, time attributes, and numerical measures to understand data patterns and distributions.
4. **Business Analysis**: Use SQL (window functions, CTEs, aggregations) to uncover insights on revenue, profitability, customer behavior, category trends, and time-series patterns.
5. **Build interactive visual dashboards:**: Develop optimized Power BI dashboards to visualize KPIs, trends, and segment-level performance for informed decision-making.

## Project Structure
### Database Setup

- **Database Creation**: The project starts by importing data from local CSV file and creating a database named `sql_project_p1`.
- **Table Creation**: A table named `retail_sales` is created to store the sales data. The table structure includes columns for transaction ID, sale date, sale time, customer ID, gender, age, product category, quantity sold, price per unit, cost of goods sold (COGS), and total sale amount.
- **Data Quality**: Some columns are in the wrong format (e.g., sale_date as text, sale_time as text), and the dataset contains duplicates and NULL values.


### 1. Data Quality & Preparation
- Imported heart disease dataset and performed full data validation
- Removed duplicate entries and inconsistent records
- Verified and corrected datatypes to ensure model readiness
- Prepared a clean, structured dataset for downstream tasks


### 2. Exploratory Data Analysis

- Analyzed key feature distributions and patient characteristics
- Generated correlation heatmaps to identify strong medical predictors
- Examined categorical variables (e.g., chest pain type) to understand their relationship with disease risk
- Visualized data patterns using Matplotlib and Seaborn

### 3. Feature Engineering & Scaling

- Separated predictors (X) and target variable (y)
- Applied StandardScaler to normalize continuous clinical measurements
- Ensured uniform feature contribution across ML algorithms

### 4. Ensemble Model Development

- Built a Voting Classifier combining:
    - 1) Logistic Regression
    - 2) Random Forest
    - 3) Gradient Boosting
- Used soft voting to aggregate predictions and improve accuracy
- Leveraged strengths of both linear and tree-based models

### 5. Model Training

- Split data into 80% training and 20% testing
- Trained individual models and the ensemble classifier
- Utilized scaled features to improve convergence and model stability

### 6. Performance Evaluation

- Evaluated model using:
    - 1) Accuracy
    - 2) Precision
    - 3) Recall
    - 4) F1-score
    - 5) Confusion Matrix
- Visualized model performance using heatmaps
- Compared individual models vs. ensemble model to validate improvements

## Conclusion

This project demonstrates a complete machine learning pipeline for predicting heart disease using ensemble learning techniques. Through robust preprocessing, exploratory analysis, feature scaling, and model evaluation, the project highlights the value of ML in medical risk prediction and assists in supporting clinical decision-making.

