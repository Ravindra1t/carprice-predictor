# carprice-predictor
just a practice of my linear regression skills
This project aims to predict car prices based on various features such as curb weight, engine size, horsepower, car body type, and others. The model uses a linear regression approach to forecast car prices from a given dataset.

Project Overview
The goal of this project is to develop a machine learning model that can predict the price of a car based on its attributes. The dataset includes both numerical and categorical features, such as car dimensions, engine specifications, and car body types. After performing exploratory data analysis (EDA), significant features were selected for model training.

Features
Numerical Features:
Curbweight

Car Length

Car Width

Engine Size

Boreratio

Horse Power

Wheel Base

City mpg

Highway mpg

Categorical Features:
Engine Type

Fuel Type

Car Body

Aspiration

Cylinder Number

Drivewheel

Brand Category

Project Workflow
Data Preprocessing:

Handling missing values, outliers, and data transformation (such as sqrt/log transformation).

One-hot encoding for categorical features to make them suitable for machine learning models.

Feature Engineering:

Selection of significant features based on exploratory data analysis (EDA).

Modeling:

Linear regression was used to build a prediction model.

Evaluation:

Model performance is evaluated using metrics such as RMSE (Root Mean Squared Error) and R² score.
