# Coffee Shop Daily Revenue Prediction

## Project Overview

The primary objective of this project is to build a **predictive model** for daily revenue prediction of a coffee shop using **linear regression**. The model is trained on a dataset containing various operational metrics and is used to predict the daily revenue based on factors such as the number of customers, operating hours, marketing spend, and foot traffic. The project involves data preprocessing, model training, evaluation, and visualization of results.

## Design Overview

### Data Preprocessing
- **Feature Scaling**: The features are scaled using **StandardScaler** to normalize the data, ensuring that all features contribute equally to the model's performance.
- **Data Splitting**: The data is split into training and testing sets (80% for training, 20% for testing) to ensure that the model is evaluated on unseen data.

### Model
- **Linear Regression**: The model is trained using **Linear Regression** with the preprocessed data.
- **Evaluation**: The model's performance is evaluated using **Mean Squared Error (MSE)** and **R-squared**, which provide insights into the accuracy and explanatory power of the model.

## Key Components

### Libraries Used:
- **Pandas**: For data handling and manipulation.
- **NumPy**: For numerical operations.
- **Matplotlib**: For data visualization, including model evaluation metrics.
- **Scikit-learn**: For model training, evaluation, and data preprocessing.

### Process:
1. **Data Loading**: The dataset is loaded using Pandas.
2. **Feature Scaling**: The features are scaled to ensure the model's efficiency.
3. **Model Training**: A linear regression model is trained on the data.
4. **Model Evaluation**: The model’s accuracy is evaluated using **MSE** and **R-squared**.
5. **Visualization**: Model performance is visualized with metrics such as **MSE** and **R-squared**.

## Algorithms Used
1. **Linear Regression**: A machine learning algorithm used for predicting continuous values. In this project, it predicts the daily revenue based on various operational features.
2. **Mean Squared Error (MSE)**: A metric used to evaluate the model's performance by measuring the average squared difference between predicted and actual values.
3. **R-squared**: A statistical measure of how well the independent variables explain the variation in the dependent variable.

## Results:
- The **Mean Squared Error (MSE)** provides an indication of the average error in the model's predictions.
- The **R-squared** value demonstrates how well the model explains the variance in daily revenue.

