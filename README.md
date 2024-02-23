# Cardiovascular Diseases Risk Prediction

**Overview**

This project aims to explore and analyze the key factors that significantly impact the likelihood of developing heart diseases, such as age, height, weight, smoking history, alcohol consumption, and other lifestyle factors. The end goal is to build a predictive model to accurately predict the likelihood of developing heart disease based on a person's lifestyle.

**Data Source**

The dataset used in this project is obtained from Kaggle and contains approximately 300,000 samples with 19 features, including 12 categorical and 7 numerical variables. The target variable is the presence of heart disease.

**Data Preprocessing**

The dataset is first loaded and examined using the skim function to check for missing values and obtain a summary of numerical variables.
Categorical variables are converted to factors to facilitate analysis.
Duplicate entries are identified and removed to ensure data integrity.

**Exploratory Data Analysis (EDA)**

**Univariate Analysis**

Distribution of numerical variables such as height, weight, BMI, alcohol consumption, fruit consumption, green vegetable consumption, and fried potato consumption is visualized using histograms and density plots.
Categorical variables such as general health, checkup frequency, exercise habits, smoking history, and the presence of other diseases are examined using count plots.

**Bivariate Analysis**

Relationships between heart disease and various factors such as smoking history, age category, other cancers, sex, skin cancer, alcohol consumption, BMI, and fried potato consumption are explored using bar plots and box plots.

**Multivariate Analysis**

Scatter plots are used to visualize the relationships between multiple variables, such as weight vs. alcohol consumption and weight vs. BMI, colored by the presence of heart disease.
Hypothesis Testing
T-tests are conducted to test the significance of differences in mean values of variables such as fruit consumption, alcohol consumption, green vegetable consumption, and fried potato consumption between individuals with and without heart disease.

**Decision Tree Model**

A decision tree model is built using the rpart package to predict the presence of heart disease based on the features in the dataset.
The model's performance is evaluated using a confusion matrix, and the accuracy is reported.

**Conclusions**
The EDA and statistical tests reveal that lifestyle factors such as age, weight, smoking history, alcohol consumption, and dietary habits significantly impact the likelihood of developing heart disease.
The decision tree model provides a tool for predicting the risk of heart disease based on these factors.

**Future Steps**

Further refinement of the predictive model using additional machine learning techniques and feature engineering.
Validation of the model on an independent dataset to assess its generalizability.
