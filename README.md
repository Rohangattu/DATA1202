Titanic Survival Prediction

This repository contains Python code for predicting survival on the Titanic dataset. The dataset is sourced from Kaggle and is available in the /kaggle/input/titanic/ directory.

Code Description
The main script, titanic_survival_prediction.py, performs the following tasks:

Data Loading and Exploration:
Loads the training data (train.csv) using Pandas.
Displays basic information about the dataset.
Explores the data using various visualizations and statistical analysis.

Data Preprocessing:
Handles missing values in the 'Age' and 'Embarked' columns.
Drops the 'Cabin' column due to a high percentage of missing values.
Performs feature engineering such as creating age groups and one-hot encoding categorical variables.

Data Analysis:
Provides insights based on exploratory data analysis, including survival rates based on gender, class, age group, etc.

Model Training:
Preprocesses the data using standard scaling and one-hot encoding.
Splits the dataset into training and testing sets.
Utilizes various ensemble classifiers including RandomForestClassifier, AdaBoostClassifier, GradientBoostingClassifier, and ExtraTreesClassifier for model training.

Running the Tests
Breakdown of Tests
The code includes exploratory data analysis, data preprocessing, model training, and evaluation. Each section is tested individually to ensure correctness and reliability.

Deployment
This code can be deployed on any machine with Python installed. Additionally, the trained model can be deployed in production environments for real-time prediction.

Instructions
To run the code:
Ensure you have Python 3 installed along with the necessary libraries specified in the requirements file.
Clone this repository to your local machine.
Navigate to the repository directory.
Execute the titanic_survival_prediction.py script.
Feel free to explore and modify the code to improve the model or experiment with different machine learning techniques.

Contributors

Rohan Sharma Gattu

If you have any questions or suggestions, feel free to contact rohan.gattu@dcmail.ca
Link to my kaggle notebook  - https://www.kaggle.com/code/rohangattu/titanic-survival-prediction
