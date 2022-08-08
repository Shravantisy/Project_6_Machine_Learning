# Project_6_Machine_Learning
All about "Supervised Machine Learning" predicting housing prices

Main code files for this project are 
1. Project_6.1_housing_data_iteration_6_final.ipynb
2. Project_6.2_house-prices-advanced-regression-techniques_final.ipynb


You work for a consultancy specialising in real estate: your clients include developers, agencies, and investors. Pricing is a central aspect to the business. Traditionally, it’s the domain of home appraisers to determine the value of a property, which must be executed in an unbiased way, following an official criteria to ensure that there is no bias towards neither the buyer nor the seller.

For each house, it also contains around 80 different features, such as the area, the state of the property, whether it has a backyard or not, etc.

## The project will be divided into two major phases:

1. Create a model to predict whether a house is expensive or not (Classification).

2. Create a model to predict the exact price of a house (Regression).

### Summary of work done so far:

1. In the first phase, the model you build will have a categorical target: “Expensive” and “Not expensive”. Whenever a ML task involves a categorical target variable, it is called a classification task.

2. In the second phase of the project, the target variable will be numerical (the exact prices of the houses in dollars): you will be dealing with a regression task.


### Data Collection

Data from Kaggle Housing Data

### Data cleaning

1. Clean data set

2. Drop NaN values more then 90%

3. Predict Traget and split data into Train-test 

### working on Categorical and Numerical columns
(Encoding - "Automated" approach (Using Pipelines))

1. Selected the numerical columns and fill Nan values by Mean

2. Selected the categorical columns

3. Fitted a OneHotEncoder to them

4. Transformed the categorical columns with the encoder

### Data Scaling methods

1. MinMaxScalar

2. StandardSCalar

### Preprocessing

Using ColumnTransformer a pipeline with 2 branches

### Full_pipeline

1. Creating the the pipeline (preprocessor + model)

2. Predict the target


### There is one another small project for Mashroom competition 
Folder name is "Mashroom competition"



