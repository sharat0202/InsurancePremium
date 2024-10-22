This project is part of a master's program assignment, focused on predicting insurance premiums using linear regression.

# Insurance Premium Prediction

This project aims to predict insurance premiums based on customer information using a Linear Regression model. The dataset contains customer details such as age, gender, BMI, number of children, smoking habits, and region. The target variable is charges, representing the insurance premium amount.

### Project Overview

Insurance companies use various customer features to determine their premiums. This project uses Linear Regression to build a predictive model based on a given dataset of customer profiles. The goal is to predict the insurance charges using features such as:

    Age
    Sex
    BMI
    Number of Children
    Smoking Status
    Region

### Modeling Approach

The project follows these steps:

#### Data Preprocessing:
    Handle missing values (if any).
    Encode categorical variables (Sex, Smoker, Region) using one-hot encoding.
    Scale the numerical features (Age, BMI, Children) using standardization.

#### Exploratory Data Analysis (EDA):
    Visualize relationships between features and the target variable using plots (correlation heatmaps, scatter plots, etc.).

#### Model Training:
    Split the dataset into training and test sets.
    Create two splits - with 10% test data and 20% test data
    Train a Linear Regression model to predict charges on both the sets.

#### Model Evaluation:
    Evaluate the model using metrics like Mean Squared Error (MSE) for both the sets.

