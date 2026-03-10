# house_price_prediction
California Housing Price Prediction

A Machine Learning project that predicts California housing prices using socio-economic and geographical data. This project demonstrates a complete end-to-end machine learning workflow, including data exploration, preprocessing, feature engineering, model training, and hyperparameter tuning.

Project Overview

The goal of this project is to build a machine learning model that can accurately predict the median house value in California districts based on various features such as population, income, housing age, and proximity to the ocean.

The project follows a full ML pipeline approach to ensure proper preprocessing and model reproducibility.

Dataset

The project uses the California Housing dataset, which includes features such as:

Longitude

Latitude

Housing Median Age

Total Rooms

Total Bedrooms

Population

Households

Median Income

Ocean Proximity

Median House Value (Target Variable)

Project Workflow

1️⃣ Data Collection

Loading the California housing dataset

Understanding dataset structure and attributes

2️⃣ Data Exploration

Statistical analysis of features

Visualizations to understand distributions and correlations

Geographical price analysis

3️⃣ Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling and normalization

4️⃣ Feature Engineering

New features were created to improve model performance:

rooms_per_household

population_per_household

bedrooms_per_room

5️⃣ Machine Learning Pipeline

A Scikit-Learn Pipeline is used to automate preprocessing and ensure consistent transformations during training and prediction.

6️⃣ Model Training

The following regression models were trained and evaluated:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

7️⃣ Hyperparameter Tuning

Model performance is improved using:

RandomizedSearchCV

Cross-validation

8️⃣ Model Evaluation

Performance is measured using:

Root Mean Squared Error (RMSE)

Cross-validation scores

Technologies Used : 

Python

NumPy

Pandas

Matplotlib

Scikit-Learn

Google Colab
