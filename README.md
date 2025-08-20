# Data-Quality-Anomaly-Detection-Tool

Automatically detects, reports, and cleans anomalies in datasets with a detailed Excel report and cleaned dataset export.
Designed for real-world messy data — handles missing values, outliers, redundant features, and more.

✨ Features

Generates multi-sheet Excel data quality report:

✅ Data profile (columns, missing %, unique values)

✅ Numeric summary (mean, std, skew, kurtosis)

✅ Invalid entries (e.g., negative values)

✅ Outlier summary (aggregated by column & method)

✅ Duplicate rows

✅ Correlation analysis (flags redundant features >0.9 corr)

✅ Low-variance columns (constant/near-constant)

✅ Skewness analysis (flags highly skewed features)

✅ Before vs After cleaning comparison

Optionally outputs a cleaned dataset (CSV):

Handles missing values (drop/fill intelligently)

Caps numeric outliers (IQR method)

Drops high-missing columns

🛠️ Tech Stack

Python 3.9+

Pandas

NumPy

SciPy

OpenPyXL
