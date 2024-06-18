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
  <img width="1023" alt="Screenshot 2024-06-17 at 1 36 20 PM" src="https://github.com/VinithaReddyKondakalla90/My-ML-Projects/assets/41354589/e48f54ac-5674-4fb3-9452-2cd935a590f2">
## Data Visualization
To better understand the data we work with we use data visualization techniques. This includes using types of graphs and charts, like scatter plots to show relationships between variables histograms to display event frequencies heatmaps to illustrate correlations between variables line charts to track changes over time and bar charts, for comparing variables across groups.
<img width="978" alt="Screenshot 2024-06-17 at 1 43 14 PM" src="https://github.com/VinithaReddyKondakalla90/My-ML-Projects/assets/41354589/cb8d967f-e78f-4735-a035-c9ae28b5eb70">
<img width="732" alt="Screenshot 2024-06-17 at 1 44 01 PM" src="https://github.com/VinithaReddyKondakalla90/My-ML-Projects/assets/41354589/c1268cc2-8802-4f4d-bf4d-db9ef217b864">


## Model selection and training
This project employs a suite of machine learning techniques tailored to address the classification task inherent in predicting mental health outcomes
Here we have taken 4 Training Models :
- Logistic Regression: A statistical method used for binary classification tasks, where the outcome variable is categorical (e.g., presence/absence of a mental health disorder). It estimates the probability of a binary outcome based on one or more predictor variables.
- Decision Tree: A non-linear predictive model is used that splits the data into subsets based on the most significant attributes. It is a tree-like structure where internal nodes represent feature splits and leaf nodes represent class labels.
- Random Forest: An ensemble learning technique that combines multiple decision trees to improve prediction accuracy and reduce overfitting. It constructs a multitude of decision trees during training and outputs the mode of the classes or mean prediction of individual trees.
- Gradient Boosting: This technique builds models sequentially, with each new model correcting errors made by the previous ones. It optimizes a differentiable loss function by adding weak learners (typically decision trees) in a stage-wise manner.
<img width="342" alt="Screenshot 2024-06-17 at 1 44 29 PM" src="https://github.com/VinithaReddyKondakalla90/My-ML-Projects/assets/41354589/2782babb-ab39-4884-8367-71337353aa1e">

## Performance evaluation:
The performance of regression models is assessed by applying a range of metrics designed to measure distinct dimensions of predicted accuracy. These include Mean Squared Error (MSE), which provides a measure of the average squared difference between predicted and actual values; Root Mean Squared Error (RMSE), which represents the square root of the MSE to interpret errors in the original units of the response variable; and R-squared (R2) score, which indicates the percentage of variance in the dependent variable explained by the independent variables. Mean Absolute Error (MAE) measures the average magnitude of errors between predicted and actual values. In addition, further metrics like accuracy, precision, recall, and F1-score are used for classification tasks, including determining if mental health issues are present or absent, to evaluate how well the model performs in accurately classifying cases across various categories. Cross-validation techniques, which divide the dataset into multiple subsets for training and validation, are used to perform performance evaluation to ensure the robustness and reliability of the models.
<img width="493" alt="Screenshot 2024-06-17 at 1 44 47 PM" src="https://github.com/VinithaReddyKondakalla90/My-ML-Projects/assets/41354589/7f377f2f-dc3e-4796-9ed6-c050cbc1f0ea">

## Conclusion
This project highlights the importance of understanding the mental health status of students and the various factors that can influence it. By analyzing this dataset, we can gain valuable insights that can help improve student well-being.
## Requirements
To run the analysis, ensure you have the following software and libraries installed:
- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- statsmodels
- jupyter (optional, for running the notebook interactively)

## How to Run
- Clone the repository.
- Install the required packages using pip install -r requirements.txt.
- Import the Student Mental health.csv.
- Run the Jupyter notebook Student_Mental_Project.ipynb to see the analysis.
  
