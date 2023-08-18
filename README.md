# random-forest---decision-tree-models
Comparing Random Forest and Decision Tree Models Using an Income Dataset
## Income Prediction Model using Random Forest

This repository contains a machine learning model built using the Random Forest algorithm to predict income levels based on various features. The dataset used for this project is the Income Dataset, which includes attributes such as age, workclass, education, marital status, occupation, and more.

### Project Overview

The goal of this project is to predict whether an individual's income is above or below $50,000 based on a set of features. The dataset initially contained missing values and categorical features, which required preprocessing to ensure accurate model performance.

### Data Preprocessing

- Conducted Exploratory Data Analysis (EDA) to understand the data distribution and identify missing values.
- Handled missing values by dropping rows with missing values and encoding categorical features using Label Encoding.
- Balanced the imbalanced dataset using the Synthetic Minority Over-sampling Technique (SMOTE).

### Model Building

- Implemented Random Forest and Decision Tree models to predict income levels.
- Utilized K-Fold Cross Validation to assess model performance and compared accuracy scores.
- Tuned hyperparameters of the Random Forest model using GridSearchCV to optimize performance.

### Model Evaluation

- Evaluated the final Random Forest model on a test dataset.
- Calculated accuracy, confusion matrix, and classification report to measure model performance.
- Visualized feature importance to understand the impact of individual features on predictions.
- Plotted the Precision-Recall curve and calculated Precision-Recall AUC and Average Precision scores.

### Results

- Achieved an accuracy of approximately 88.7% on the test dataset.
- The Precision-Recall AUC was 0.89, indicating good precision and recall trade-off.
- Identified key features that contribute the most to the prediction, as shown in the feature importance plot.

### Dataset Columns

| Column          | Description                           |
|-----------------|---------------------------------------|
| age             | Age of the individual                |
| workclass       | Type of employment                    |
| fnlwgt          | Final weight                          |
| education       | Highest education level achieved      |
| education-num   | Numeric representation of education   |
| marital-status  | Marital status                        |
| occupation      | Occupation                            |
| relationship    | Relationship status                   |
| race            | Race                                  |
| sex             | Gender                                |
| capital-gain    | Capital gain                          |
| capital-loss    | Capital loss                          |
| hours-per-week  | Hours worked per week                 |
| native-country  | Native country                        |
| income          | Income level (target variable)        |


