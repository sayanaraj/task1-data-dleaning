# task1-data-dleaning
Internship Task 1- Data Cleaning and Processing using Titanic Dataset

This repository contains my solution for the first task that was given to us for our AI and ML Internship at ELEVATE LABS

#Dataset
The Titanic Dataset was used as suggested by the document from Kaggle: [Download link](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

#Librabries 
All the required libraries like: 
pandas – for data handling
numpy – for numerical calculations
matplotlib – for basic visualizations
seaborn – for advanced graphs
scikit-learn – for preprocessing, scaling, encoding
were installed with the help of Command Prompt on Windows and then imported.

#Actions Performed to the dataset
1. Loaded the data from the given dataset using pandas.read_csv()
2. Explored the nulls/types. (.isnull().sum())
3. Handled missing values using .median(),.mode().
4. Encoded categorical figures. (Sex)
5. Standardized numerical figures. (Age and Fare using StandardScaler), This helps certain ML models (like KNN, SVM, Logistic Regression) perform better and converge faster.
6. Outlier detection and removal using the Interquartile Range (IQR) method.
7. Visualised the dataset.

#File list 
- 'task1.py': main file
- 'Titanic-Dataset.csv': provided dataset
- 'titanic_cleaned.csv': the cleaned dataset
