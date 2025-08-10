## Crime Data Classification Using Logistic Regression and Random Forest
Project Overview
This project involves building machine learning models to classify crime incidents based on a rich dataset containing multiple features related to crimes. The goal is to accurately predict the crime category or outcome while addressing the challenges posed by imbalanced classes in the dataset.

The dataset is preprocessed extensively, including handling missing values, removing outliers, encoding categorical variables, and engineering relevant features such as year extracted from date columns.

Key Features
Comprehensive exploratory data analysis (EDA) to understand trends, distributions, and relationships in the data.

Selection and preprocessing of relevant features, including numerical and categorical data transformations.

Implementation of two classification models:

Logistic Regression with class weight adjustment to handle class imbalance.

Random Forest Classifier for improved performance via ensemble learning.

Hyperparameter tuning of both models using GridSearchCV to optimize model parameters systematically.

Threshold tuning applied to classification outputs to balance precision and recall, especially important for imbalanced classes.

Detailed evaluation of model performance using accuracy, confusion matrix, and classification reports.

Dataset Description
The dataset consists of crime records with attributes such as:

Crime type (Primary Type)

Location details

Arrest status

Domestic crime indicator

FBI and IUCR codes

Date and time fields

Preprocessing steps involved:

Dropping irrelevant columns (e.g., IDs)

Outlier detection and removal using Interquartile Range (IQR) method

Encoding categorical variables and date-time feature extraction

Handling class imbalance with model parameters and threshold tuning

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

Adjust classification thresholds to improve prediction balance on imbalanced data.

Evaluate models using appropriate metrics and select the best performing one.

Results
Both Logistic Regression and Random Forest models demonstrated good classification performance after tuning.

Threshold adjustment improved recall for minority classes without severely compromising precision.

Random Forest generally outperformed Logistic Regression due to its ability to capture complex patterns.

Future Work
Experiment with other ensemble methods such as Gradient Boosting or XGBoost.

Explore advanced sampling techniques like SMOTE to better address class imbalance.

Incorporate temporal analysis to capture trends over time.

Deploy the model via a web app or API for real-time crime prediction.
