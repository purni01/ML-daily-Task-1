# ML-daily-Task-1
Task1-ML
Task 1: Data Cleaning & Preprocessing – Titanic Dataset

In this task, I worked with the Titanic Dataset to clean and prepare the raw data for machine learning. The goal was to make the dataset usable by handling missing values, converting categorical data, and standardizing numeric columns.

Tools Used:
Python
Pandas, NumPy
Matplotlib,Seaborn
Scikit-learn

**Steps I Followed**

1.**Loaded the Dataset**
Used pandas to load the Titanic dataset (.csv file).
Explored it using .head(), .info(), and .isnull().sum() to check structure and missing values.

2.**Handled Missing Values**
Filled missing values in the Age column using the mean.
Checked that all missing values were handled (isnull().sum() showed 0).

3.**Encoded Categorical Variables**
Converted the Sex and Embarked columns into numeric values using one-hot encoding.
Used drop_first=True to avoid multicollinearity.

4.**Normalized Numerical Columns**

Standardized the Age and Fare columns using StandardScaler so they have a mean of 0 and standard deviation of 1.

5.**Visualized and Removed Outliers**
Used boxplots to detect outliers in Age and Fare.
Removed extreme values using a ±3 standard deviation rule.
Output

a. No missing values
b. All features are numeric
c. Numeric features are scaled
d. Outliers removed
