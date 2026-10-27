# Ridge-Regression-House-Price-Prediction

# House Price Prediction using Linear and Ridge Regression

## Overview
This project implements Linear Regression and Ridge Regression models to predict house prices using Python and Scikit-learn.

## Objectives
- Build a house price prediction model.
- Train Linear and Ridge Regression models.
- Evaluate model performance using regression metrics.
- Compare both models on the same test dataset.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Dataset
The dataset contains 506 samples and 13 input features. The target column is `price`.

**Note:** The target column must be excluded from the input features to avoid data leakage.

## Models
1. Linear Regression
2. Ridge Regression with GridSearchCV and 5-fold cross-validation

## Model Performance

| Metric | Linear Regression | Ridge Regression |
|---|---:|---:|
| R² Score | 0.6688 | 0.6685 |
| MAE | 3.1891 | 3.1857 |
| MSE | 24.2911 | 24.3129 |
| RMSE | 4.9286 | 4.9308 |

**Best Ridge Alpha:** 1

## Results
Both models achieved similar performance. Linear Regression had a slightly higher R² score, while Ridge Regression had a slightly lower MAE. Ridge regularization did not substantially improve performance on this test split.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   `pip install -r requirements.txt`

3. Launch Jupyter Notebook:

   `jupyter notebook`

4. Open the notebook and run the cells sequentially.

## Requirements

Create a `requirements.txt` file containing:

    numpy
    pandas
    matplotlib
    scikit-learn
    jupyter

## Project Structure

    House-Price-Prediction/
    ├── Linear_Regression.ipynb
    ├── Ridge_Regression.ipynb
    ├── README.md
    └── requirements.txt

## Future Improvements
- Compare additional regression models.
- Perform residual analysis.
- Improve feature engineering.
- Evaluate models with additional cross-validation experiments.

## Author
Utkrisht Patel , CEO & Founder , Invantra Labs

## Disclaimer
This project is for educational purposes. Model performance depends on the dataset and evaluation setup.
