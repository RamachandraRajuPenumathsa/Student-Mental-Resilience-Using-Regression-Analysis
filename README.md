# Student Mental Resilience Using Regression Analysis
This project aims to analyze the mental health status of students based on various factors such as gender, age, course, year of study, CGPA, marital status, and whether they have sought specialist treatment. The dataset used in this project contains 101 instances and 11 features.
Dataset Description

## The dataset includes the following columns:
- Timestamp: The date and time when the data was recorded.
- Gender: The gender of the student (Male/Female).
- Age: The age of the student.
- Course: The course the student is enrolled in.
- Year: The current year of study of the student.
- CGPA: The cumulative grade point average of the student.
- Marital Status: The marital status of the student (Yes/No).
- Depression: Whether the student has depression (Yes/No).
- Anxiety: Whether the student has anxiety (Yes/No).
- Panic Attack: Whether the student has panic attacks (Yes/No).
- Seek Any Specialist for Treatment: Whether the student has sought specialist treatment (Yes/No).
## Data Preprocessing
Steps Taken:
- Loading the Dataset: The dataset is loaded into a pandas DataFrame.
- Renaming Columns: Columns are renamed for consistency and ease of use.
- Checking Data Types: The data types of each column are checked and corrected if necessary.
- Handling Missing Values: Missing values are identified and handled using imputation techniques. For example, the missing value in the 'Age' column is filled with the mean age.
- Standardizing Data: Categorical variables are encoded, and numerical features are standardized or normalized.
- Removing Inconsistencies: Trailing spaces in categorical data are removed, and data is updated for consistency.
