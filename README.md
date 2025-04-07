# EDA-prep-customer-data
This repository contains the initial exploratory data analysis (EDA) and data cleaning steps performed on the Customer Personality Analysis dataset fetched from Kaggle. The goal is to prepare the data for further insights and modeling by handling missing values, renaming columns, correcting data types, and standardizing the overall structure
# Dataset-
 "https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis/data"
The dataset contains customer-level data for a marketing campaign, including demographic info, purchase behavior, and campaign responses.
# Objective-
1. Handling of missing values
2. Column name standardization
3. Checking and fixing data types
4. Removal of duplicate rows
5. Basic formatting for clarity.
# Cleaning Summary-
1. Renamed inconsistent or unclear column names
2. Converted date column to datetime format
3. Casted monetary columns to appropriate float types
4. Ensured all values are non-negative
5. Dropped 24 null records from the income column.Since this is a personality-based analysis, income plays a key role in understanding customer behavior and preferences. And because only a small number of rows have missing income data (around 1%), it makes more sense to drop them instead of trying to fill them in.This way, the overall quality and reliability of the analysis stay intact.
6. No duplicate columns found
7. Categorical columns were already clean — no standardization needed
# Preliminary Observation-
1. Year of Birth includes unrealistic outliers (e.g., 1893))
2. Income, Purchase and Spend Columns like mnt_wines, mnt_meat_products show a wide spread, suggesting diverse customer behavior.
3. Campaign flags are binary and well-encoded
4. z_cost_contact and z_revenue are constant — may be dropped
# Next step-
1. Visualize trends in customer demographics and behavior
2. Identify segments for targeted marketing strategies
