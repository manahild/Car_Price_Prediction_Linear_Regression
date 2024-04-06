# Car Price Prediction Website
 This repository contains the code and resources for building a machine learning model that predicts the price of used cars based on various features such as year, kilometers driven, company, fuel type, and more.

## Dataset Information
The dataset used for training the model contains information about used cars, including:


Name: Name of the car.

Company: Manufacturer/company of the car.

Year: Year of manufacture.

Price: Price of the car.

Kilometers Driven: Distance traveled by the car in kilometers.

Fuel Type: Type of fuel used by the car.

The dataset consists of 892 entries with 6 columns. Initially, data cleaning and preprocessing steps were performed to ensure data quality and consistency.

## Data Preprocessing
Data preprocessing steps included:

Removing non-numeric values from the 'year' and 'price' columns.

Converting data types to appropriate formats.

Handling missing values.

Removing outliers.

Feature engineering and transformation.

After preprocessing, the dataset was reduced to 816 entries with 6 columns.

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis was conducted to understand the relationships between different features and the target variable (price). Visualizations such as scatter plots and heatmaps were used to analyze correlations and distributions.

## Model Building
A machine learning model was developed using the cleaned dataset. The model utilizes a Linear Regression algorithm to predict car prices based on the input features. One-hot encoding was applied to categorical variables, and a pipeline was used for data preprocessing and model training.

## Model Evaluation
The model was evaluated using the R-squared (R2) metric, which measures the proportion of the variance in the target variable that is predictable from the input features. The model achieved an R2 score of approximately 0.74, indicating a good fit to the data.

## Deployment
The trained model was saved using the pickle library and deployed as a web application using Flask. Users can input the features of a car through a web interface, and the model will predict the price of the car based on the provided information.

## Interface

![image](https://github.com/manahild/Car_Price_Prediction_Linear_Regression/assets/120354756/70d4ede9-b08a-4c41-ac1a-3f53c388720d)
