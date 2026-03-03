## Lab 4 Overview

This notebook contains the solution for Lab 4, focusing on practically assessing and preprocessing a dataset (`amazon.csv` was chosen) for machine learning models.

### Tasks & Methodology

1. **Identify Data Quality Issues:** Converted strings disguised as text (e.g., containing `₹`, `,`, `%`) into proper numerical values for ML compatibility.
2. **Missing Value Strategy:** Applied **Median Imputation** on `rating` and `rating_count`, as the median is robust against skewed data and extreme outliers common in engagement metrics.
3. **Detect & Handle Outliers (IQR):** Capped extreme values in `actual_price` to their IQR bounds instead of deleting them, preserving valid high-priced data points.
4. **Normalize Features:** Applied both **Min-Max** and **Z-score (Standard)** scaling ensuring features with drastically different ranges contribute equally to models.
5. **PCA & Explained Variance:** Used PCA to reduce dimensionality, demonstrating how to retain the majority of predictive information while eliminating redundancy.
