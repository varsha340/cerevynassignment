# cerevynassignment
Problem Understanding
Predicting future values from real-world data is an important task in many domains such as energy management, sales forecasting, agriculture, and healthcare. In this project, the objective is to build a machine learning model that predicts future energy consumption using historical household energy usage data.
Real-world datasets are often noisy, incomplete, and contain non-linear relationships between variables. Traditional rule-based approaches are not effective in such scenarios. Therefore, machine learning techniques are used to learn patterns from historical data and make accurate predictions.
The goal of this project is not only to achieve good prediction accuracy but also to demonstrate proper data handling, model reasoning, evaluation, and explainability, which are essential skills for an AI/ML engineer.
Model Pipeline Description
The machine learning pipeline follows a structured and systematic approach:
Data Collection
A publicly available household energy consumption dataset was used. The dataset contains electrical measurements such as voltage, current, and sub-meter readings recorded over time.
Data Preprocessing
Removed missing and incomplete records
Separated input features and target variable
Applied feature scaling to normalize data
Split the dataset into training (80%) and testing (20%) sets
This step ensures clean and model-ready data.
Feature Selection
Relevant numerical features that directly influence energy consumption were selected, while redundant features were removed to reduce noise and improve model efficiency.
Model Selection and Training
Linear Regression was used as a baseline model
Random Forest Regressor was selected as the final model


Random Forest was chosen because it can capture non-linear relationships, handle feature interactions, and reduce overfitting through ensemble learning.
Evaluation and Inference
The trained model was evaluated on unseen test data, and predictions were generated for new inputs using the same preprocessing pipeline.
Results and Metrics
The performance of the model was evaluated using the following metrics:
Root Mean Squared Error (RMSE)
RMSE measures the average magnitude of prediction error.
A lower RMSE value indicates that the model’s predictions are close to the actual energy consumption values.
R² Score (Coefficient of Determination)
R² measures how well the model explains the variance in the target variable.
A higher R² score indicates better predictive capability.
Model Performance Summary
Random Forest achieved lower RMSE compared to Linear Regression
Random Forest achieved higher R² score, indicating better model fit
