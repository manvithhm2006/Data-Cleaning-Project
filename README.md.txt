# Data Cleaning & Preprocessing Project

## Objective
This project demonstrates the essential steps of preparing raw data for Machine Learning. Using the famous Titanic Dataset, we clean the data by handling missing values, removing outliers, encoding categorical variables, and normalizing numerical features.

## Dataset
- Source: Kaggle Titanic Dataset
- Features: Age, Sex, Fare, Embarked, Pclass, etc.

## Tools Used
- **Python**: Programming Language
- **Pandas**: Data Manipulation
- **NumPy**: Numerical Operations
- **Matplotlib/Seaborn**: Visualization
- **Scikit-Learn**: Feature Scaling (StandardScaler)

## Steps Performed
1. **Data Exploration**: Loaded data and checked for missing values and data types.
2. **Handling Missing Values**: 
   - Age: Filled with Mean
   - Cabin: Filled with "Unknown"
   - Embarked: Filled with Mode (Most Frequent)
3. **Outlier Detection**: Used Boxplots to visualize outliers in Age.
4. **Categorical Encoding**: Applied One-Hot Encoding to Sex and Embarked columns.
5. **Normalization**: Applied StandardScaler to Age and Fare columns.

## Results
- Raw data was successfully cleaned.
- Output saved as 'cleaned_data.csv'.
- Boxplot visualization saved as 'outliers_age.png'.

## How to Run
1. Ensure Python is installed.
2. Run command: `python main.py`
3. Check generated CSV and PNG files.