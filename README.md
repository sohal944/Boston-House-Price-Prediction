# Boston House Price Prediction

This project predicts house prices in Boston using machine learning, specifically the XGBoost Regressor. The dataset was preprocessed to clean null values and ensure high-quality predictions.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Data Preprocessing](#data-preprocessing)
5. [Modeling](#modeling)
6. [Results](#results)
7. [How to Run](#how-to-run)
8. [Acknowledgments](#acknowledgments)

---

## Introduction
The Boston housing dataset contains information about houses in Boston, including features like crime rate, number of rooms, and property tax. The goal is to predict the price of houses based on these features.

---

## Dataset
The dataset is a well-known machine learning dataset provided by the `sklearn.datasets` module. Key attributes include:
- **CRIM**: Per capita crime rate.
- **RM**: Average number of rooms per dwelling.
- **TAX**: Property tax rate per $10,000.
- **MEDV**: Median value of owner-occupied homes (target variable).

---

## Technologies Used
The project was implemented using:
- **Python**: Core programming language.
- **Pandas**: Data manipulation and cleaning.
- **NumPy**: Numerical computations.
- **Matplotlib**: Data visualization.
- **scikit-learn**: Dataset access and machine learning utilities.
- **XGBoost Regressor**: Model for predicting house prices.

---

## Data Preprocessing
- **Loading Data**: The dataset was loaded using `sklearn.datasets`.
- **Cleaning**: Null values were identified and removed.
- **Feature Engineering**: Additional checks ensured relevant features were scaled and normalized where needed.

---

## Modeling
The XGBoost Regressor was used for predictions:
- **Training**: The data was split into training and test sets.
- **Hyperparameter Tuning**: Parameters were adjusted for optimal performance.
- **Evaluation**: Metrics like Mean Squared Error (MSE) and R² were used to assess model accuracy.

---

## Results
The model achieved strong performance, accurately predicting house prices based on the dataset features. Key highlights include:
- High R² score indicating a good fit.
- Insights into feature importance, e.g., **RM** and **TAX** were critical predictors.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Boston-House-Price-Prediction.git
