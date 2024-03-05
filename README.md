# Poisson Regression Modeling with Date Transformation

This repository demonstrates the application of Poisson regression modeling with date transformation using Python. Poisson regression is particularly useful for modeling count data, and in this project, we explore its application in predicting ice cream sales based on various factors including date, temperature, and advertising expenditure.

## Overview

This project involves the following key steps:

- **Data Loading and Examination**: We begin by loading the dataset and examining the first few rows to understand its structure and content.
  
- **Adding Derived Regression Variables**: Several derived regression variables such as month, day of the week, and day are added to the dataset to enhance the predictive power of the model.
  
- **Data Splitting for Training and Testing**: The dataset is split into training and testing sets to train the model on one subset and evaluate its performance on the other.
  
- **Regression Formula Specification**: We specify the regression formula that defines the relationship between the dependent variable (ice cream sales) and the independent variables (day, month, temperature, advertising expenditure, and day of the week).
  
- **Poisson Regression Modeling**: Poisson regression models are fitted to the training data using the statsmodels library.
  
- **Model Evaluation and Validation**: Predictions are made on the test dataset, and the performance of the model is evaluated using various metrics. Visualizations are created to compare predicted and actual ice cream sales counts.

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels

## Usage

1. Clone the repository to your local machine.
2. Install the required dependencies listed in the `requirements.txt` file.
3. Run the provided Python script to execute the Poisson regression modeling process.
4. Explore the model summary, predictions, and visualizations to gain insights into ice cream sales prediction.

## Acknowledgments

The dataset used in this project is sourced from [KenDaupsey's GitHub repository](https://github.com/KenDaupsey/Basic-Poisson-Regression-Using-Python).

Feel free to customize the README further according to your preferences and additional details about the project!

- Special thanks to the contributors and maintainers of the Python libraries used in this project.
