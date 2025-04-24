# Task-1-Data-Cleaning-Preprocessing
This project involves cleaning and preprocessing the Titanic dataset for machine learning. Steps include:

### cleaning and Preprocessing Steps
- Loaded and explored the dataset
- Filled missing values (median for Age, mode for Embarked)
- Dropped the Cabin column due to too many nulls
- Encoded categorical columns (Sex and Embarked)
- Normalized Age and Fare using StandardScaler
- Removed outliers using the IQR method

  ### Files
- Task - 1 Data Cleaning & Preprocessing: The main preprocessing code
- Titanic-Dataset.csv: The dataset used

### Using Libraries for cleaning and Preprocessing Steps
```bash
pandas
numpy
scikit-learn
seaborn
matplotlib
