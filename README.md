# Analysis-of-Hydrocarbon-Emissions-from-Ships-at-a-Port-Insights-and-Predictive-Modeling

## Project Overview

This project aims to predict port emissions using various machine learning models. The prediction is based on several features such as the type of motor ship, type of load, year of construction, maximum speed, average speed, gross tonnage, dead weight, and engine power. The dataset used in this project contains real-world data on ship emissions at a port.

## Dataset

The dataset used in this project is a collection of emissions data from ships at a port. It includes features like the type of motor ship, type of load, year of construction, maximum speed, average speed, gross tonnage, dead weight, auxiliary engine fuel, engine speed, main engine power, auxiliary engine power, and total emissions.

## Methodology

The project follows these steps:

1. **Data Loading**: Load the emissions data from a CSV file.
2. **Data Preprocessing**: Handle missing values, encode categorical variables, and perform feature selection.
3. **Splitting Data**: Split the data into training and test sets.
4. **Model Training**: Train multiple regression models including Linear Regression, Random Forest, Gradient Boosting, XGBoost, and TPOT Regressor.
5. **Model Evaluation**: Evaluate the models using metrics like Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.
6. **Model Selection**: Select the best-performing model based on evaluation metrics.

## Results

The models were evaluated based on their performance in predicting port emissions. The evaluation metrics used were Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared. The TPOT Regressor, which is an AutoML tool, was used to automate the model selection process and find the best pipeline for the prediction task.

## Conclusion

The project demonstrates the use of various machine learning models to predict port emissions based on ship characteristics and operational data. The models were trained and evaluated, and the best-performing model was selected for making predictions. This project can be extended by incorporating more features, using more advanced models, and deploying the model for real-time emissions prediction at ports.

