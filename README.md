# Data Cleaning - Titanic Dataset

## Internship
Oasis Infobyte - Data Analytics

## Task
Level 1 - Task 3: Cleaning Data

## Objective
To systematically clean a dataset and transform it into an analysis-ready dataset while documenting the data-cleaning decisions.

## Dataset
Titanic passenger dataset containing passenger information such as age, gender, passenger class, fare, cabin, and embarkation details.

## Data Cleaning Steps
1. Inspected the dataset shape, columns, data types, and missing values.
2. Identified missing values in Age, Cabin, and Embarked.
3. Filled missing Age values using the median.
4. Filled missing Cabin values with "Unknown".
5. Filled missing Embarked values using the mode.
6. Checked and removed duplicate rows.
7. Verified numerical data types for Age and Fare.
8. Detected Fare outliers using the IQR method.
9. Retained legitimate Fare outliers.
10. Verified the cleaned dataset.
11. Saved the cleaned dataset as cleaned_titanic.csv.

## Files
- Data_Cleaning_Task3.ipynb - Jupyter Notebook containing the complete cleaning process.
- train.csv - Original dataset.
- cleaned_titanic.csv - Cleaned dataset.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook