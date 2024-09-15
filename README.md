# House Price Prediction Project 🏡📊

This project aims to predict house prices based on various features such as area, number of bedrooms, bathrooms, stories, and more. Using machine learning techniques, we have built models to predict house prices based on a dataset of housing attributes.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Model Evaluation](#model-evaluation)
- [How to Run](#how-to-run)
- [Results](#results)
- [Future Work](#future-work)

## Overview
In this project, multiple machine learning models were trained and evaluated to predict house prices based on a dataset containing 545 records. Each record contains 13 features describing the house characteristics such as the area, number of rooms, and additional amenities like parking or air conditioning.

## Dataset
The dataset used in this project contains the following columns:
- `price`: The selling price of the house.
- `area`: Size of the house in square feet.
- `bedrooms`: Number of bedrooms.
- `bathrooms`: Number of bathrooms.
- `stories`: Number of stories.
- `mainroad`: Whether the house is located on the main road (yes/no).
- `guestroom`: Whether the house has a guestroom (yes/no).
- `basement`: Whether the house has a basement (yes/no).
- `hotwaterheating`: Whether hot water heating is available (yes/no).
- `airconditioning`: Whether air conditioning is available (yes/no).
- `parking`: Number of parking spaces.
- `prefarea`: Whether the house is in a preferred area (yes/no).
- `furnishingstatus`: Whether the house is furnished, semi-furnished, or unfurnished.

## Features
The key features that influence house prices are:
1. Area
2. Number of bedrooms and bathrooms
3. Stories
4. Air conditioning
5. Parking spaces

## Technologies Used
- **Python** 🐍
- **Pandas** for data manipulation.
- **NumPy** for numerical computations.
- **Matplotlib** and **Seaborn** for data visualization.
- **scikit-learn** for machine learning algorithms.
- **Google Colab** for running the notebooks in a cloud environment.

## Model Evaluation
The following machine learning models were used:
- **Linear Regression**
- **Ridge and Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Extra Trees Regressor**
- **K-Nearest Neighbors (KNN)**
- **Support Vector Regressor (SVR)**

### Best Performing Model: Linear Regression
- **R² Score**: 64.2%
- **Mean Squared Error (MSE)**: 1,809,581,673,897.11

Other models such as Ridge, Lasso, and Decision Trees were also evaluated, but Linear Regression performed the best in this dataset.

