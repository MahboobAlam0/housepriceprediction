# House Price Prediction using Scikit-learn Linear Regression, Gradient Descent, Normal Equation

## Project Overview
This project implements **Linear Regression** to predict house prices using **Gradient Descent** and **Normal Equation**. The model is evaluated using the **R² score** on both the training and test sets.

## Dataset
The dataset contains various features related to house properties, including:
- **OverallQual** (Overall material and finish quality)
- **GrLivArea** (Above grade living area in square feet)
- **GarageCars** (Number of garage cars)
- **GarageArea** (Size of garage in square feet)
- **TotRmsAbvGrd** (Total rooms above grade)

## Model Performance
| Method                  | Train R² Score | Test R² Score |
|-------------------------|---------------|--------------|
| Gradient Descent       | 0.7465        | 0.7864       |
| Normal Equation        | 0.7465        | 0.7864       |
| Scikit - Learn        | 0.7465        | 0.7864       |

## Key Insights
- **OverallQual** has the highest correlation with house prices (**0.79**), making it the most important feature.
- The test R² score (0.7864) is slightly higher than the train R² score (0.7465), indicating good generalization.
- Both **Gradient Descent** and **Normal Equation** yield the same performance.

## Installation
```sh
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage
1. Load the dataset.
2. Train the model using Gradient Descent or Normal Equation.
3. Evaluate the model using R² score.
