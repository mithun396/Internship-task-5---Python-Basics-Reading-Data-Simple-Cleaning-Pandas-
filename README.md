# Internship-task-5---Python-Basics-Reading-Data-Simple-Cleaning-Pandas-

# Overview
This task demonstrates basic data cleaning and preprocessing using Python and Pandas.
The objective is to replace manual Excel-based cleaning with a reproducible, programmatic workflow.

Dataset Used: Titanic Dataset
Tools: Google Colab / Jupyter Notebook
Libraries: pandas, numpy

# Steps Performed

# 1. Data Loading
- Loaded the Titanic dataset using pd.read_csv()
- Previewed data using head() and inspected structure using info()

# 2. Missing Value Analysis
- Identified missing values using isnull().sum()

# 3. Data Cleaning
- Dropped Cabin column due to excessive missing values
- Filled missing Age values using median
- Filled missing Embarked values using mode
- Removed duplicate records to ensure data consistency

# 4. Data Type Conversion
- Encoded Sex column:
- male → 0
- female → 1
  
# 5. Feature Engineering
- Created Age_Group column:
- Child (<18)
- Adult (18–59)
- Senior (60+)
- Created Fare_Band using quartile-based binning

# 6. Data Export
- Saved the cleaned dataset as cleaned_data.csv

# Final Outcome
- Gained hands-on experience with Pandas data cleaning
- Learned how Python replaces manual Excel-based workflows
- Produced a clean, analysis-ready dataset suitable for EDA or machine learning

# Tools & Libraries
- Python 3
- pandas
- numpy
- Google Colab / Jupyter Notebook
