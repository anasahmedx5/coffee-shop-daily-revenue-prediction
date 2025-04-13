# Coffee Shop Daily Revenue Prediction

## Project Overview

This project focuses on building predictive models to estimate the daily revenue of a coffee shop using various operational metrics. It explores Simple Linear Regression, Multiple Linear Regression, and Polynomial Regression to understand the influence of features like customer count, average order value, and foot traffic.

## Design Overview

### Data Preprocessing
- **Feature Selection**: The independent variables were separated from the target variable `Daily_Revenue`.
- **Scaling**: Applied `StandardScaler` to normalize the input features.
- **Train-Test Split**: Dataset split into 80% training and 20% testing for fair evaluation.

### Models
- **Simple Linear Regression**: Trained on the most correlated feature (`Number_of_Customers_Per_Day`).
- **Multiple Linear Regression**: Used all features to predict revenue.
- **Polynomial Regression**: Applied to the best feature to capture non-linear relationships (degrees 2, 3, and 4).

### Evaluation
- **Metrics**:
  - Mean Squared Error (MSE)
  - R-squared (R²)
- **Visualization**:
  - Actual vs Predicted revenue plots
  - Polynomial regression performance comparison

## Key Components

### Libraries Used
- `Pandas`: Data manipulation
- `NumPy`: Numerical computations
- `Matplotlib`: Data visualization
- `Scikit-learn`: Preprocessing, modeling, and evaluation

### Process
1. Data loading and exploration
2. Correlation analysis to identify impactful features
3. Model training:
   - Simple Linear Regression
   - Multiple Linear Regression
   - Polynomial Regression (degrees 2 to 4)
4. Evaluation and visualization of model predictions

## Algorithms Used

- **Simple Linear Regression**: Predicts revenue using one strong feature.
- **Multiple Linear Regression**: Uses all features to improve prediction accuracy.
- **Polynomial Regression**: Captures non-linear patterns in revenue prediction.
- **MSE and R²**: Evaluate how well models perform on unseen data.

## Results

- Simple Linear Regression showed a strong relationship between revenue and the number of daily customers.
- Multiple Linear Regression improved prediction accuracy by including more business-related features.
- Polynomial Regression (especially degree 2) slightly improved performance for non-linear trends.
- Higher complexity offered better fit but required careful evaluation to avoid overfitting.

This project demonstrates how different regression models can be applied to real-world business forecasting problems.
