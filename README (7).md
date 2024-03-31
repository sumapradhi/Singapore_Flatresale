# Singapore_flat_prices_resale_prediction
# Resale Price Prediction Web Application

## Overview

This project aims to address the challenge of estimating resale prices for flats in Singapore's competitive real estate market. We have developed a user-friendly web application that utilizes a machine learning model to predict the resale price of flats based on various input factors. The model is built upon historical data of resale flat transactions, allowing potential buyers and sellers to make informed decisions.

## Motivation

The Singapore resale flat market is influenced by numerous variables, including location, flat type, storey range, floor area, and lease duration. Accurately estimating resale values is crucial, and this project was motivated by the need to provide a reliable and accessible solution. By harnessing machine learning, we can leverage historical data to predict resale prices with greater accuracy.

## Solution Approach

To tackle the problem statement, we followed a series of well-defined steps:

1. **Data Collection and Preprocessing:**
   - Gathered a comprehensive dataset of resale flat transactions from the Singapore Housing and Development Board (HDB) spanning from 1990 to the present.
   - Preprocessed the data, cleaning and structuring it to prepare for machine learning.

2. **Feature Engineering:**
   - Extracted key features from the dataset, including town, flat type, storey range, floor area, flat model, and lease commence date.
   - Created additional features where necessary to enhance prediction accuracy.

3. **Model Selection and Training:**
   - Chose an appropriate machine learning model for regression, such as linear regression, decision trees, or random forests.
   - Trained the model on the historical data, using a portion of the dataset for training.

4. **Model Evaluation:**
   - Evaluated the model's predictive performance using regression metrics, including Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R2 Score.

5. **Streamlit Web Application:**
   - Developed a user-friendly web application using Streamlit.
   - Enabled users to input details of a flat (town, flat type, storey range, etc.).
   - Utilized the trained machine learning model to predict the resale price based on user inputs.

6. **Deployment on Render:**
   - Deployed the Streamlit application on the Render platform to make it accessible to users over the internet.

7. **Testing and Validation:**
   - Conducted thorough testing of the deployed application to ensure it functions correctly and provides accurate predictions.

## How to Use the Application

1. Visit the deployed web application.
2. Input the details of the flat you want to estimate the resale price for, including the town, flat type, storey range, and other relevant information.
3. Click the "Predict" button.
4. The application will use the machine learning model to provide you with an estimated resale price based on the input factors.

## Disclaimer

Please note that the predicted resale prices provided by the application are based on historical data and a machine learning model. They should be used as estimates and not as absolute values for real estate transactions. It's advisable to consult with real estate professionals for accurate and up-to-date pricing information.

Thank you for using our Resale Price Prediction Web Application!
