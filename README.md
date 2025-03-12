# AI-Budget-Allocation

## Overview
This project implements a machine learning and Bayesian optimization framework for budget allocation. It uses **XGBoost** for predictive modeling and **Optuna** for optimizing resource distribution while maintaining statistical consistency. The goal is to assist decision-makers by providing quantitative insights into budget allocations, without replacing policymakers.

## Features
- **Predictive Modeling:** Uses XGBoost to forecast GDP growth, inflation, and the Gini index based on budget allocation.
- **Data Augmentation:** Generates synthetic data using Gaussian noise, bootstrapping, and Variational Autoencoders (VAE) to enhance model robustness.
- **Optimization:** Implements Bayesian optimization with Optuna to find the optimal allocation strategy.
- **Validation:** Uses K-Fold cross-validation and performance metrics (MSE, R², Adjusted R²) to assess model accuracy.
- **Visualization:** Generates comparison plots between actual and predicted values, learning curves, and optimized allocation distributions.

```

## Usage
### 1. Train the Model
Run the script to preprocess data, generate synthetic observations, and train the XGBoost model:
```sh
python train_model.py
```

### 2. Optimize Budget Allocation
Execute the optimization script to determine the best allocation strategy:
```sh
python optimize_allocation.py
```

### 3. View Results
- Predicted vs Actual Values
- Learning Curve Analysis
- Optimal Budget Allocation Recommendations


## Dependencies
- Python 3.8+
- XGBoost
- Optuna
- TensorFlow/Keras
- Scikit-learn
- Pandas
- Matplotlib
- NumPy

## Acknowledgments
This project was developed to explore AI-assisted budget allocation strategies. The implementation is inspired by research on machine learning applications in public finance and resource optimization.


