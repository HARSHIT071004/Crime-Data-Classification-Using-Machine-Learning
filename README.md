Crime Data Classification Using Logistic Regression and Random Forest
Project Overview

This project focuses on building machine learning models to classify crime incidents based on a rich dataset with multiple crime-related features. The goal is to accurately predict crime categories or outcomes while effectively handling challenges posed by imbalanced classes.

Extensive preprocessing was applied, including handling missing values, removing outliers, encoding categorical variables, and engineering features such as extracting the year from date columns.

Key Features

Comprehensive Exploratory Data Analysis (EDA) to identify trends, distributions, and relationships.

Preprocessing of numerical and categorical features, outlier removal, and feature engineering.

Implementation of two classification models:

Logistic Regression with class weight adjustment for imbalanced classes.

Random Forest Classifier for improved predictive performance through ensemble learning.

Hyperparameter Tuning using GridSearchCV for optimal model parameters.

Threshold Adjustment to balance precision and recall, particularly for minority classes.

Model evaluation using accuracy, confusion matrix, and classification reports.

Dataset Description

The dataset contains crime records with attributes including:

Crime type (Primary Type)

Location details

Arrest status

Domestic crime indicator

FBI and IUCR codes

Date and time fields

Preprocessing Steps:

Dropping irrelevant columns (IDs, etc.)

Outlier detection and removal using IQR method

Encoding categorical variables and extracting date-time features

Handling class imbalance via model parameters and threshold tuning

Environment and Dependencies

Python 3.x

pandas

numpy

matplotlib

seaborn

scikit-learn

How to Use

Load the dataset and perform data cleaning and preprocessing.

Conduct exploratory data analysis to visualize crime patterns.

Split the data into training and testing sets.

Train Logistic Regression and Random Forest models with hyperparameter tuning using GridSearchCV.

Adjust classification thresholds to improve predictions on imbalanced data.

Evaluate models and select the best performing one.

Results

Both Logistic Regression and Random Forest demonstrated strong classification performance.

Threshold adjustment improved recall for minority classes without significantly reducing precision.

Random Forest outperformed Logistic Regression due to its ability to capture complex patterns.

Future Work

Experiment with other ensemble methods such as Gradient Boosting or XGBoost.

Apply advanced sampling techniques like SMOTE to handle class imbalance.

Incorporate temporal analysis to capture trends over time.

Deploy the model as a web application or API for real-time crime prediction.

Author

Harshit Sharma – Data Science / Machine Learning Enthusiast
