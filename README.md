# House Price Prediction with Machine Learning

## Project Overview

The goal of this project is to develop a machine learning model capable of predicting house prices in California using demographic and geographical features.

The project uses the California Housing dataset available through the scikit-learn library. Starting from the available data, a regression model is trained to estimate house values in different districts of California.

In addition to prediction, the project demonstrates the main stages of a machine learning workflow, including data exploration, preprocessing, model training, evaluation, and interpretation of results.

## Dataset

The California Housing dataset contains information about different districts in California, including:

* Median income
* House age
* Average number of rooms
* Average number of bedrooms
* Population
* Average occupancy
* Latitude
* Longitude

The target variable is the median house value.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn

## Project Structure

```text
house-price-prediction-ml/
│
├── README.md
├── notebook/
│   └── house_price_prediction.ipynb
└── src/
```

## Models

The following machine learning models were implemented and compared:

1. Linear Regression
2. Random Forest Regressor

## Results

| Model                   | MAE   | R²    |
| ----------------------- | ----- | ----- |
| Linear Regression       | 0.533 | 0.576 |
| Random Forest Regressor | 0.328 | 0.805 |

The Random Forest model significantly outperformed Linear Regression, achieving a lower prediction error and a substantially higher R² score.

## Conclusions

The results show that house prices are influenced by complex and non-linear relationships between features. While Linear Regression provides a simple baseline, Random Forest is better suited to capture these relationships and therefore achieves superior predictive performance.

This project was developed for educational purposes to explore machine learning techniques for regression problems using Python and Scikit-Learn.
