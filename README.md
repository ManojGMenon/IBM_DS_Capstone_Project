# IBM_DS_Assignment
Model creation and evaluation for predicting loan default/payment

## Project:
We will complete a notebook where we will build a classifier to predict whether a loan case will be paid off or not.<br>

## Tasks:
We will load a historical dataset from previous loan applications, clean the data, and apply different classification algorithm on the data. <br>
We will use the following algorithms to build the models:<br>
<ul><li> k-Nearest Neighbour
<li> Decision Tree
<li> Support Vector Machine
<li> Logistic Regression </ul>

## Components of the required Outputs (report items)
The results will be reported as the accuracy of each classifier, using the following metrics when these are applicable:<br>
<ul><li> Jaccard index
<li> F1-score
<li> LogLoss<br></ul>

## Dataset: 
This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted.<br>
https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-ML0101EN-SkillsNetwork/labs/FinalModule_Coursera/data/loan_train.csv

## Jupyter Notebook :
### Approach to solving this problem
<ul><li>1. Problem definition
<li>2. Setting up the environment (importing required libraries)
<li>3. Loading the raw dataset
<li>4. Cleaning the data
<ul> <li>Adjusting data formats <li>
        Data visualization for exploration <li>
        Feature selection/extraction <li>
        Converting categorical to numeric data <li>
        One-hot encoding <li>
        Dropping unnecessary data </li></ul>
<li>5. Data Modelling & Evaluation with KNN
<ul> <li> Feature selection (X,y) <li>
          Create training & test sets <li>
          Normalize the data <li>
          Train the model using the Training set <li>
          Make prediction using the Test set <li>
          Find model accuracy using Jaccard index, for different values of ‘k’  (best model) <li>
        Output : Chart of K vs Accuracy - showing highest K value. </ul></ul>

