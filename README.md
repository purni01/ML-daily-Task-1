# ML-daily-Task-1
Task1-ML
Task 1: Data Cleaning & Preprocessing – Titanic Dataset

In this task, I worked with the Titanic Dataset to clean and prepare the raw data for machine learning. The goal was to make the dataset usable by handling missing values, converting categorical data, and standardizing numeric columns.

Tools Used

Python
Pandas, NumPy
Matplotlib,Seaborn
Scikit-learn
Steps I Followed

Loaded the Dataset

Used pandas to load the Titanic dataset (.csv file).
Explored it using .head(), .info(), and .isnull().sum() to check structure and missing values.
Handled Missing Values

Filled missing values in the Age column using the mean.
Checked that all missing values were handled (isnull().sum() showed 0).
Encoded Categorical Variables

Converted the Sex and Embarked columns into numeric values using one-hot encoding.
Used drop_first=True to avoid multicollinearity.
Normalized Numerical Columns

Standardized the Age and Fare columns using StandardScaler so they have a mean of 0 and standard deviation of 1.
Visualized and Removed Outliers

Used boxplots to detect outliers in Age and Fare.
Removed extreme values using a ±3 standard deviation rule.
Output

-- No missing values
-- All features are numeric
-- Numeric features are scaled
-- Outliers removed
