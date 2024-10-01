# Weather Data Analysis Project

## Overview
This project analyzes weather data from Australia, focusing on temperature patterns in Canberra. It uses various data analysis and machine learning techniques to process, visualize, and model the temperature trends.

## Data Source
The project uses the "weatherAUS.csv" dataset, which contains weather information for various locations in Australia.

## Features
1. Data Loading and Preprocessing
2. Exploratory Data Visualization
3. Polynomial Regression Analysis
4. Stochastic Gradient Descent (SGD) Optimization
5. Model Comparison and Evaluation

## Technical Stack
- Python
- Libraries: TensorFlow, NumPy, Pandas, Matplotlib

## Key Components

### Data Preparation
- Loads weather data from CSV
- Filters data for Canberra
- Calculates average daily temperature

### Visualization
- Plots average temperature over time
- Visualizes temperature trends for specific time periods

### Modeling
1. Polynomial Regression using Matrix Multiplication
   - Implements a basic polynomial regression model
   
2. Polynomial Regression with SGD and Regularization
   - Uses TensorFlow for model implementation
   - Applies Stochastic Gradient Descent for optimization
   - Incorporates regularization to prevent overfitting

### Analysis
- Compares different modeling approaches
- Evaluates model performance using R-squared values
- Analyzes residuals to assess model fit

## Results
The project demonstrates the application of different regression techniques to model temperature trends. It highlights the impact of regularization on model performance and provides insights into the temperature patterns in Canberra.

## Usage
To run this analysis:
1. Ensure you have Python and the required libraries installed
2. Place the "weatherAUS.csv" file in the project directory
3. Run the Jupyter notebook "data_analysis.ipynb"
