# **Model Development (UCI Imports-85 & Laptop Pricing)**

This repository provides a complete Model Development workflow for two datasets — the Automobile (Imports-85) dataset from the UCI Machine Learning Repository and a Laptop Pricing dataset.

The project focuses on understanding feature patterns, relationships, and statistical insights through EDA, followed by the development of regression models to predict target variables such as price.

# 📌 Dataset Overview

1️⃣ Automobile Dataset

Source: UCI Machine Learning Repository – Automobile Dataset

Rows: 205

Attributes: 26 (mix of categorical, continuous, and integer values)

Common Target Variable: price

2️⃣ Laptop Pricing Dataset

A dataset containing specifications and prices of various laptop models. Used for exploring relationships between configuration features and price prediction.


# 🧮 Model Development Workflow

Following the Exploratory Data Analysis (EDA), this phase focuses on developing and evaluating regression models for predicting target variables such as price.

1️⃣ Single Linear Regression

Develop a Simple Linear Regression model using one predictor variable (e.g., horsepower → price).

Fit the model and visualize the regression line.

Assess the relationship strength and interpret coefficients.

2️⃣ Multiple Linear Regression

Build a Multiple Linear Regression model using multiple independent variables (e.g., engine-size, curb-weight, horsepower, highway-mpg).

Evaluate the significance of each feature and interpret regression coefficients.

Analyze model fit and performance metrics.

3️⃣ Model Evaluation Using Visualization

Use graphical methods to assess model accuracy and residual behavior:

Regression Plot: Compare predicted vs. actual values.

Residual Plot: Check for randomness and constant variance.

Distribution Plot: Evaluate how well predictions match the actual data distribution.

4️⃣ Polynomial Regression with Pipelines

Implement Polynomial Regression to capture non-linear relationships.

Use PolynomialFeatures and integrate with Pipeline to automate feature transformation and model fitting.

Compare linear and polynomial model performances.

5️⃣ Polynomial Features

Generate higher-degree and interaction terms to model non-linear behavior.

Examine improvements in model fit while monitoring for overfitting.

6️⃣ Pipeline

Construct an ML pipeline to streamline preprocessing, feature transformation, and model training.

Automate scaling, polynomial generation, and regression fitting within a single workflow.

Ensure consistency and reproducibility in model building.

7️⃣ Measures for In-Sample Evaluation

Evaluate model performance for:

Model 1: Simple Linear Regression

Model 2: Multiple Linear Regression

Model 3: Polynomial Fit

Use key metrics for comparison:

R² Score – goodness of fit

Mean Squared Error (MSE) – average squared difference between actual and predicted values

Mean Absolute Error (MAE) – average absolute difference

Prediction and Decision Making:
Use model insights to guide feature importance analysis, price prediction, and data-driven decision-making.

# 📊 Outcome

✅ Developed and compared multiple regression models (Simple Linear, Multiple Linear, and Polynomial) for predictive analysis.
✅ Visualized model performance through regression, residual, and distribution plots to evaluate fit quality and detect bias or variance issues.
✅ Implemented Polynomial Regression with pipelines to efficiently handle non-linear feature relationships and automate the modeling process.
✅ Assessed model accuracy using key statistical metrics — R², MSE, and MAE — for in-sample evaluation.
✅ Derived insights into feature importance, helping guide decisions related to pricing and performance factors.
✅ Built a reusable modeling pipeline applicable to other structured datasets for continuous model experimentation and optimization.

# 🧰 Tools & Libraries

- Python – core language for data analysis and modeling

- Pandas, NumPy – data preprocessing, manipulation, and numerical operations

- Matplotlib, Seaborn – model visualization (regression, residual, and distribution plots)

- Scikit-learn – linear regression, polynomial features, pipelines, and evaluation metrics

- SciPy – statistical testing and correlation analysis
