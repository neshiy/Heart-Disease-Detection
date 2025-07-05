
### Table of Contents
- [Introduction](#introduction)
- [Exploratory Data Analysis (EDA)](#eda)
- [Data Preprocessing](#datapreprocessing)
- [Model Building](#modelbuilding)
- [Hyperparameter Tuning](#hyperparameter)
- [Evaluation Metrics](#metrics)
- [Web app Development](#webapp)
### Heart Disease Detection 

One of the leading causes of death worldwide is Heart disease. Early detection can help in timely treatment and saving lives. In this project, we build a machine learning model to predict the presence of heart disease based on patient medical data.





###  Exploratory Data Analysis (EDA)

- Checked all for null values.
- Analyzed class distribution (target variable).
- Visualized features with histograms, boxplots, violin plots, and correlation heatmaps.
- Identified relationships between features and heart disease presence.

### Data Preprocessing

- Feature selection: Used all features for initial model.

- Scaling: Standardized features using StandardScaler to improve model performance.

- Train-test split: Split data into 80% training and 20% testing sets for evaluation.
### Model Building

- Logistic Regression - Baseline model for binary classification.
- K-Nearest Neighbors - Classifies based on closest data points.
- Decision Tree - Tree-based model for decision making.
- Support Vector Machine - Finds optimal separating hyperplane.
### Hyperparameter Tuning

The GridSearchCV was used to tune hyperparameters of KNN, Decision Tree, and SVM for best performance.
### Evaluation Metrics

- Accuracy

- Confusion Matrix

- Classification Report (Precision, Recall, F1-Score)

The results of the models. 

- Logistic Regression: ~85%
- KNN: ~82%
- Decision Tree: ~79%
- SVM: ~87%

After checking with multiple models, it concluded that the best performance model is the Support Vector Machine Model (SVM).


### Web App Deployment

A web app was developed using Flask, where the users can input medical details and get real-time predictions. Here's a breakdown on what this app contain; 

- Loads the saved model.
- Accepts user inputs via HTML form.
- Predicts using the model.
- Displays result on the same page.
