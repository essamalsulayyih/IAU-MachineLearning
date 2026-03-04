Overview
This project demonstrates essential data cleaning and preprocessing steps required before building machine learning models. Real-world data is often incomplete, noisy, or inconsistent; therefore, preparing it properly is crucial for model performance.

Dataset
File: IntegratedData.csv.

Content: COVID-19 statistics (cases, deaths) and mobility metrics (retail, transit, etc.).

Preprocessing Steps
Data Quality Assessment: Identify and fix incorrect data types, such as converting the date column from a string to a datetime object.

Handling Missing Values: Apply Median Imputation for missing mobility data because the median is more robust to outliers than the mean.

Handling Outliers: Use the Interquartile Range (IQR) method to detect and remove extreme values that could distort the model.

Normalization: Apply Min-Max Scaling (to range 0-1) and Z-score Standardization (to mean 0 and standard deviation 1) to ensure features are on a similar scale.

Principal Component Analysis (PCA): Reduce dimensionality by creating principal components that capture the maximum variance in the data.

Results
The preprocessing success is measured by the Explained Variance Ratio in PCA, which indicates how much original information is retained in the reduced components.