# Real Estate Price Prediction in King County

## Overview
This project, named "Fantastic Houses and Where to Find Them", is focused on understanding the real estate market in King County, which includes Seattle, by exploring a dataset of house sale prices between May 2014 and May 2015. Jacob Kawalski, an aspiring entrepreneur in the real estate domain, seeks to launch his business with a robust analysis of market trends and price determinants.

## Objective
The primary objective is to develop a predictive model that can accurately forecast house prices in King County based on various attributes provided in the dataset. This involves data cleansing, exploration, model selection, validation, and finally, price prediction for new houses using the best-performing model.

## Dataset Description
The dataset contains several attributes related to the housing features and sale details, including:
- id: Unique identifier for each sale
- price: Sale price (target variable)
- bedrooms, bathrooms: Number of bedrooms and bathrooms
- sqft_living, sqft_lot: Square footage of the living area and the lot
- floors: Number of floors
- waterfront: Whether the house has a waterfront view
- view: An index from 0 to 4 on how good the view of the property was
- condition, grade: Indexes rating the condition and overall grade of the house
- sqft_above, sqft_basement: Square footage of the house apart from the basement and the basement area
- yr_built, yr_renovated: Year the house was built and the year of the last renovation
- zipcode, lat, long: Location details of the house

## Methodology
Our analysis followed these steps:
- Data Preparation: Cleansing and preprocessing of the dataset to ensure quality and readiness for analysis.
- Exploratory Data Analysis (EDA): Examination of key variables and their relationships to understand the factors influencing house prices.
- Model Development: Construction of multiple predictive models to forecast house prices. The models considered include k-Nearest Neighbors (kNN) and others based on the dataset's characteristics.
- Model Evaluation and Selection: Evaluation of models based on accuracy, precision, and other relevant metrics to select the best-performing model.
- Price Prediction: Application of the selected model to predict prices for new houses in the test dataset.

## Tools and Libraries Used
- R Programming Language: For data processing and modeling.
- Libraries: caret, ggplot2, dplyr, tidyverse, rpart, forecast, car, ROSE, corrgram, lmtest, gvlma.

## Results and Discussion
The project concluded with the identification of a predictive model that offers a reasonable prediction of house prices in King County. Insights into significant predictors and their impact on house prices were discussed. The final model's performance metrics were detailed to evaluate its efficacy.

## Conclusion
The study provided Jacob Kawalski with a comprehensive analysis of the King County real estate market, assisting in the launch of his real estate business with data-driven strategies. Future work could explore additional modeling techniques and incorporate more recent data for improved accuracy.

