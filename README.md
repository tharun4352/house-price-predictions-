# Housing Price Predictor

## Overview

This project aims to predict house sale prices based on various property features such as location, area, quality, number of rooms, garage capacity, and other housing characteristics. The model was developed using Machine Learning techniques and trained on historical housing sales data.

## Problem Statement

Real estate agencies require accurate property price estimation to assist buyers, sellers, and agents in making informed decisions. The objective of this project is to build a predictive model that estimates house sale prices using available property features.

## Dataset

The dataset contains detailed information about residential properties, including:

* Property size and area
* Number of bedrooms and bathrooms
* Quality and condition ratings
* Garage information
* Neighborhood details
* Additional amenities and features

Files provided:

* train.csv
* test.csv
* data_description.txt
* sample_submission.csv

## Approach

1. Data Loading and Exploration
2. Handling Missing Values
3. Encoding Categorical Features
4. Feature Preprocessing
5. Model Training using Random Forest Regressor
6. Prediction Generation for Train and Test Datasets

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Google Colab
* GitHub

## Model

Algorithm Used:

* Random Forest Regressor

Reasons for Selection:

* Handles mixed data types effectively
* Captures non-linear relationships
* Provides strong baseline performance for regression tasks

## Output Files

* train_predictions.csv
* test_predictions.csv
* model.pkl

## Project Structure

Housing-Price-Predictor/
│
├── Housing_Price_Predictor.ipynb
├── train_predictions.csv
├── test_predictions.csv
├── model.pkl
├── data_description.txt
└── README.md

## Future Improvements

* Hyperparameter Tuning
* Feature Engineering
* XGBoost Implementation
* Cross Validation
* Model Deployment using Flask or Streamlit

## Author

Tharun injothi
B.Tech CSE (AI & ML)

