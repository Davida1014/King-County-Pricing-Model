# King County Housing Price Prediction

# Overview
This project seeks to create a model that predicts house prices in King County, WA using multiple linear regression and feature modeling and training. This represents the final project in Phase 2 of Flatiron School's Data Science immersive program.

# Business Problem
A King County real estate company is trying to determine what types of houses to focus on selling. Possible features that may impact prices include location, square-footage, number of stories, and more. This model seeks to determine which features to focus on to maximize selling price.

# Methods
The following steps were taken to create price predictions:
1. Exploratory data analysis and visualizations to identify most promising predictors
2. Data cleaning of identified features
3. Feature engineering: creation of new features to further inform predictions
4. Statistical tests to confirm significance of identified and engineered features
5. Creation of several multiple linear regression models and evaluation of each to identify most successful model

# Results
The most successful multiple linear regression model was generated using polynomial features, KBest feature selection, and Lasso. Recursive feature elimination was also explored but did not prove as successful as the aforementioned model.

The most significant indicators of price in this model were high house square footage, proximity to houses with high square footage, high grade in the King County grading system, and location.

# Summary
Analysis of existing and engineered features in the King County housing data set revealed square footage, neighbor square footage, grade, and distance and high predictors of house price. Other features that were expected to be strong predictors, such as waterfront views or season sold, did not impact prices as much as expected. 

The most successful model with the lowest testing error was achieved through a combination of polynomial feature creation, KBest feature selection, and Lasso.

# Further Research
Areas for further research include:
1. Neighborhoods outside of Seattle proper
2. School districts
3. Distance to water
4. Distance to colleges and universities

# Repository Structure
├── data                                # data folder
├── reference                           # project reference files
├── models                              # final regression model and scaler
├── results                             # final prediction notebook, model implementation, predicted prices
├── King County Project Notebook.ipynb  # project notebook with EDA and model creation
├── king_county_prediciton.ipynb        # final prediciton notebook, model implementation
└── README.md
