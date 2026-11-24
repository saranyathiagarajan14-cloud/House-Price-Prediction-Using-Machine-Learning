
# House Price Prediction Using machine learning

A machine learning project that uses Linear Regression to predict house prices based on property features.

## Project Overview

This project explores a housing dataset and predicts house prices using features such as area, number of bedrooms and bathrooms, stories, parking, and other property details. It demonstrates data exploration, visualization, model training, and evaluation using Python.

## Dataset

The dataset contains 545 house records with these columns:

- Price
- Area
- Bedrooms
- Bathrooms
- Stories
- Main road access
- Guest room
- Basement
- Hot water heating
- Air conditioning
- Parking
- Preferred area
- Furnishing status

## Machine Learning

- **Problem type:** Regression
- **Algorithm:** Linear Regression
- **Features:** Property details, including area, bedrooms, bathrooms, stories, parking, and amenities
- **Target:** House price
- **Categorical data:** Converted into numeric features using one-hot encoding
- **Train-test split:** 80% training and 20% testing

## Project Workflow

1. Loaded the dataset using pandas.
2. Checked the dataset structure, summary statistics, missing values, and duplicates.
3. Encoded categorical features using one-hot encoding.
4. Visualized the price distribution and correlations between numeric columns.
5. Split the features and target into training and test sets.
6. Trained a Linear Regression model.
7. Evaluated predictions using MAE and R².
8. Compared actual and predicted prices with a graph.
9. Predicted the price of a sample house.

## Results

- **Mean Absolute Error (MAE):** 970,043.40
- **R² Score:** 0.653
- **Sample house predicted price:** 4,898,897.16

The model explains approximately 65.3% of the price variation in the test data. MAE represents the average prediction error in the dataset's price units.

## Technologies

- Python
- Jupyter Notebook
- NumPy
- pandas
- scikit-learn
- Matplotlib
- Seaborn
- Joblib

## Important Notes

- The dataset contains 545 house records.
- Categorical features were converted into numerical values using one-hot encoding.
- The notebook uses a saved model named `house_price_model.pkl`. Include this file if you want to run the model-loading section.
- The dataset's currency is not specified in the notebook.
- This project demonstrates a basic regression workflow; predicted prices may differ from actual market prices.



