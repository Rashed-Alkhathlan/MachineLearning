# Lab 5 Overview

This lab focused on feature engineering for predicting `Order_Status` using the `talabat_enhanced_orders.csv` dataset. The following tasks were successfully implemented in `Lab5.ipynb`:

- **Task 1:** Created a new feature called `route_efficiency`, which compares the actual delivery route distance against the straight-line (Haversine) distance between the restaurant and the customer.
- **Task 2:** Implemented a new continuous `is_peak_hour` rule (13:00-16:00 and 18:00-22:00) to see how shifting the busy windows affects model performance.
- **Task 3:** Evaluated different frequency thresholds (`top_k` = 10, 30, and 50) for categorical reduction on the `Item_Name` column, comparing accuracy and feature importance rankings.
- **Task 4:** Used scikit-learn's `SelectFromModel` with a median threshold to perform automated feature selection, effectively halving the dataset's features while maintaining baseline predictive accuracy.
