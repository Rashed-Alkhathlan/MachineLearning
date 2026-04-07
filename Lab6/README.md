# Lab 6 Overview

This lab focused on applying linear regression on an ecommerce dataset to predict the `Yearly Amount Spent` by a customer. The following tasks were successfully implemented in `Lab6.ipynb`:

- **Task 1:** Loaded the `Ecommerce_Customers.csv` dataset into a pandas DataFrame.
- **Task 2:** Explored the data using standard pandas methods (`head`, `info`, `describe`) to understand feature distributions.
- **Task 3:** Cleaned the data by checking for missing values and filtering to keep only the relevant numerical features.
- **Task 4:** Performed feature engineering by separating predictors (`Avg. Session Length`, `Time on App`, `Time on Website`, `Length of Membership`) from the target variable (`Yearly Amount Spent`).
- **Task 5:** Prepared the data for modeling by splitting it into training and testing sets using `train_test_split`.
- **Task 6:** Trained a `LinearRegression` model from `scikit-learn` on the training data.
- **Task 7:** Evaluated the model performance by calculating error metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE), and analyzed the model coefficients to interpret feature significance.
