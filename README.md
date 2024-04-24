# ACDA1 Team 2 Repository

![Screenshot 2024-04-24 at 6 28 59 PM](https://github.com/NaqDoo/sc1015_miniproj/assets/162019204/c8629182-402a-4360-ab54-df4aa23fdb20)

## **About** 

We will be exploring the Heart Failure Prediction Dataset from kaggle (https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data).

Structure: 
1. Exploratory Data Analysis
2. Logistic Regression Model
3. Random Forest Regression Model

## Aim
Predicting whether a patient is susceptible to heart failure based on the attributes provided. The problem is a binary classification problem (having a heart disease (1) and not having one (0)).

## Models Used 

- Logistic Regression
    - In this project, we implemented logistic regression using Python and the scikit-learn library to predict the presence or absence of heart disease based on various attributes
    - Applied one-hot encoding to categorical features
    - Split the data into training and testing sets
    - Made predictions on the test set using the trained logistic regression model
    - Used confusion matrix and ROC curve to evaluate and visualise the model's performance
- Random Forest Regression
    - Categorical data was converted to integer for this model to be applied.
    - Split the data into train and test sets
    - Carried out random forest regression and evaluated model performance using explained variance and mean squared error
    - Regression Model did not perform well with heart attack dataset as the R^2 decresed with test set and MSE increased instead.
    - Extracted the top 10 values from 4 features to draw relations with risk of heart disease
 
## Conclusion
- Carried out Logistic Regression and Random Forest Regression
- Logistic Regression Model has better performance with this dataset
- RestingECG and RestingBP have lowest correlation with HeartDisease
- ST_Slope and Exercise Angina tend to have highest correlation
- Aging population is at higher risk of Heart Disease


## Knowledged gained from project
- Data visualisation skills
- Presentation skills
- Data cleaning
- Performing logistic regression
- Performing random forest regression
- Extracting count of top 10 values of a feature
- Collaboration on Github

## Contributors

- @AvanishAvale - Exploratory Data Analysis
- @richardxdxd - Logistic Regression
- @NaqDoo - Random Forest Regression

## References
