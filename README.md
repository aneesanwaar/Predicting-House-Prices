# Predicting House Prices Using the Boston Housing Dataset

## Description
This project involves building a linear regression model,  Random Forest, and XGBoost from scratch to predict house prices using the Boston Housing Dataset. The goal is to implement regression algorithms without relying on built-in libraries such as `sklearn.linear_model`, enabling a deeper understanding of regression techniques.

## Steps
### 1. Data Preprocessing
- Loading the Boston Housing Dataset.
- Normalizing numerical features.
- Preprocessing categorical variables (if any) to ensure model compatibility.

### 2. Model Implementation
- Implemented **Linear Regression**, **Random Forest**, and **XGBoost** from scratch.
- Ensured models can handle training and predictions efficiently.

### 3. Performance Comparison
- Evaluated models using **Root Mean Square Error (RMSE)** and **R² score**.
- Compared different models to determine the best approach for this dataset.

### 4. Feature Importance
- Extract and visualize feature importance for **Random Forest** and **XGBoost**.
- Analyzed how different features impact house prices.



## Installation & Setup
# Prerequisites: 

Clone the repository and install all required dependencies using:
```
git clone https://github.com/aneesanwaar/Predicting-House-Prices.git
pip install -r requirements.txt
```


## Usage
1. Run the script in a Jupyter Notebook or a Python environment.
2. Follow the preprocessing steps to clean and normalize data.
3. Train the models and compare their performance.
4. Visualize the feature importance of tree-based models.

## Notes
- The dataset is sourced from **OpenML**.
- The project focuses on **manual implementation** of algorithms to understand the inner workings of regression models.
- Performance metrics help determine which model is most suitable for house price prediction.



