# Prediction-using-Multiple-Linear-Regression

This project involves the implementation of Multiple Linear Regression (MLR) to analyze and predict the price of used toyota corolla cars based on multiple input features. The data used in this project is sourced from the book Data Mining for Business Analytics: Concepts, Techniques and Applications in Python by Galit Shmueli, Peter C. Bruce, Peter Gedeck, O. P. Wali and Nitin R. Patel.

## Project Structure

The project is structured as follows:

- toyotamlr.ipynb: Jupyter Notebook containing the full implementation of the Multiple Linear Regression model, including 
  data preprocessing, model training, and evaluation.
- toyota.xls: Dataset of the project

## Project Description

###  Objective

The primary objective of this project is to build and evaluate a Multiple Linear Regression model. The model is used to predict a target variable based on multiple predictors. Key steps include data preprocessing, model fitting, and performance evaluation.  

### Methodology

#### Data Preprocessing

- Handling Missing Values: The dataset is checked for missing values, and appropriate techniques are applied to handle them.

#### Model Training

- The MLR model is trained using the selected features to predict the target variable.
- The training process involves splitting the dataset into training and testing sets to evaluate model performance.


####  Model Evaluation

- R-Squared: The R-squared value is calculated to determine how well the independent variables explain the variance in the dependent variable.
- Residual Analysis: Residual plots are analyzed to check the assumptions of linearity, homoscedasticity, and normality of errors.

###  Results

The results section in the Jupyter Notebook includes:

- The coefficients of the regression equation.
- A detailed analysis of model performance based on various metrics such as Root Mean Square Error (RMSE).

## Prerequisites

To run the notebook, you need to have the following Python libraries installed:
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

These can be installed using pip:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## How to Use

1. Clone this repository to your local machine.
2. Dataset is present in toyota.xls .
3. Open the toyotamlr.ipynb notebook in Jupyter Notebook or VS Code.
4. Run the cells sequentially to reproduce the analysis and results.

## Acknowledgements

This project utilizes data from Data Mining for Business Analytics: Concepts, Techniques and Applications in Python by Galit Shmueli, Peter C. Bruce, Peter Gedeck, O. P. Wali and Nitin R. Patel. Special thanks to the authors for providing the dataset and accompanying content.


