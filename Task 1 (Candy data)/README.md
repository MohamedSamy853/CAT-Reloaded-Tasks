# Candy Dataset - Data Cleaning
This README file explains the Candy  dataset and the steps taken to clean and preprocess the data using pandas and the fuzzywuzzy library for string similarity matching.
## Dataset Description
The Candy Power Ranking dataset is a collection of data related to various types of candies. The dataset includes information such as candy names, rankings, and survey responses from individuals about their preferences for each candy.
## Data Cleaning Process
The following steps were performed to clean and preprocess the Candy Power Ranking dataset:
1. **Loading the Dataset**: The dataset was loaded into a pandas DataFrame for easy manipulation and analysis.
2. **Handling Missing Values**: Any missing values in the dataset were identified and appropriate actions were taken, such as imputation or removal of incomplete rows or columns.
3. **Data Type Conversion**: Columns with incorrect data types were converted to their appropriate types. For example, numerical columns were converted from strings to numeric values.
4. **Standardizing Text Data**: The text data in the dataset, such as candy names, was standardized to ensure consistency. This involved converting all text to a consistent case (e.g., lowercase) and removing leading or trailing spaces.
5. **Removing Duplicates**: Duplicate records or rows with identical or highly similar information were identified and removed to maintain data integrity.
6. **Handling Similar Strings**: The fuzzywuzzy library was used to identify and handle similar strings within the dataset. This involved matching similar strings across columns, identifying potential duplicates or variations of the same candy name, and resolving discrepancies.
7. **Data Validation and Sanity Checks**: The cleaned dataset was thoroughly validated to ensure that it met the expected data quality standards. Sanity checks were performed to verify the integrity of the data and to identify any remaining anomalies.
8. **Saving the Cleaned Dataset**: The cleaned dataset was saved in an appropriate format (e.g., CSV, Excel) for future analysis or sharing with other stakeholders.



