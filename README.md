# Wazobia-Real-Estate-Limited-House-Price-Prediction

## Introduction
Real estate is a constantly changing market that is affected by a variety of factors leading to fluctuating prices. The aim of this project is to develop a predictive model that can assist Wazobia Real Estate Limited in Nigeria to determine the ideal pricing for properties based on certain features including location, title, number of bedrooms, bathrooms and parking spaces.

### Objectives
- Data Analysis: Delve into the dataset through comprehensive exploratory data analysis. Identify outliers, tackle missing values, and gain a deep understanding of the data's underlying characteristics.

- Model Building: Advanced machine learning algorithms are utilized to create accurate predictive models for house prices.

- Model Evaluation: Rigorously evaluate model performance using appropriate metrics to select the most precise predictive model.

- Interpretability: Gain valuable insights into real estate market dynamics.

- Business Impact: Transform and translate model insight with actionable strategies Wazobia Real Estate's pricing tactics with actionable strategies.

## Data Description and E.D.A

This dataset contains information on various features related to houses, including the number of bedrooms, bathrooms, parking spaces, property types, Locations and their corresponding prices. The goal of this project is to develop accurate predictive models that estimate house prices in Nigeria, providing valuable insights to Wazobia Real Estate Limited for informed decision-making and improved market competitiveness.

### Data Information

- Number of Entries: 14,000
- Features: Bathroom, Bedroom, Parking Space, Property Location (loc), Property Type (title)
- Target Variable: Price

### Data Analysis Highlights

In our exploratory data analysis (EDA), we delved into various aspects of the dataset to understand its relationships and generated some insights 

- The distribution of bathrooms, bedrooms, and parking spaces is explored
- Correlation analysis shows the relationships between features and the target variable (price)
- The distribution of property prices is analyzed, highlighting skewness and the presence of outliers.
- Location-based and property type-based pricing trends are uncovered, offering insights for pricing strategies.
- Missing values are identified in the "loc" and "title" columns, and recommendations are provided for handling them appropriately.

---

You can access the complete dataset [HERE](https://zindi.africa/competitions/free-ai-classes-in-every-city-hackathon-2023/data).

---


## Data Preprocessing

### Data Cleaning

- Removed rows with missing values in 'loc' and 'title' columns.

- Filled missing values in 'bedroom', 'bathroom', and 'parking_space' columns with their respective medians.

### Features Engineering

- Encoded 'loc' column using TargetEncoder, enhancing model's understanding of location-price relationship.
  
- Created new features 'comfort_ind', 'size', and 'comfort_by_size' to capture property comfort and size insights.


## Machine Learning WorkLoad
### Model Building

- Utilized CatBoostRegressor with RMSE as the loss function for predicting house prices.

- Employed 5-fold cross-validation with shuffling using KFold to prevent overfitting.

### Model Evaluation

- Achieved a cross-validation RMSE score of 415,808.6 indicating prediction variance.



### Features Importance

- Top three important features: "title_rank," "loc_encoded," and "bedroom"

- Significant contributions from "size" and "comfort_by_size".

- "comfort_ind," "parking_space," and "bathroom" have relatively lower importance scores.


### Conclusion

This project predicts house prices based on location, title, and amenities using the top-performing Cross-validated Catboost regressor model for a real estate company.  

## Media Links

[linkedin](https://www.linkedin.com/in/alajede-mustapha-6071211a9/)

