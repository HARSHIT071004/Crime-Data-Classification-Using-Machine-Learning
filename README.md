📊Crime Data Classification 

Overview

     This project builds machine learning models to classify crime incidents using a structured crime dataset. It addresses imbalanced classes and applies Logistic Regression and Random Forest to predict crime categories with high accuracy.

Dataset

  Attributes include:

    Primary crime type

    Location details

    Arrest and domestic indicators

    FBI/IUCR codes

    Date and time information

 Preprocessing steps:

    Dropped irrelevant columns (e.g., IDs)

    Handled missing values and outliers (IQR method)

    Encoded categorical variables

    Extracted temporal features (year, month)

    Addressed class imbalance with class weights and threshold tuning

Objectives:

    Perform EDA to explore crime patterns and distributions

    Preprocess and engineer features for modeling

Train and tune:

    Logistic Regression (class-weight adjustments)

    Random Forest Classifier (ensemble learning)

    Evaluate models using accuracy, confusion matrix, and classification reports

    Optimize hyperparameters using GridSearchCV

Tech Stack:

    Language: Python 3.x

    Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Usage:

    Clone the repository:

    git clone https://github.com/HARSHIT071004/Crime_data_model.git
    cd Crime_data_model


Install dependencies:

    pip install -r requirements.txt


Run preprocessing and model training:

    python crime_classification.py

Results

    Random Forest delivered higher accuracy than Logistic Regression.

    Threshold tuning improved recall for minority classes without reducing precision.

Future Enhancements

    Explore Gradient Boosting or XGBoost.

    Use SMOTE or other sampling techniques for class imbalance.

Deploy as a web application or API for real-time predictions.

Author

Harshit Sharma

GitHub: HARSHIT071004Enthusiast
