
# [Project 1: Home Credit Default Analysis](https://github.com/justinhamilton125/Justin-Hamilton-Portfolio)

## Project Overview:

**Project Objective:** 
Home Credit (Loan Brokerage/Bank) will be able to identify if a customer is a safe candidate to lend to based on attributes about a person who is most likely to default on a loan, resulting in an increase in revenue, improved customer experience, and lower default rates.

**Business Problem:**
Home Credit desires to know safe borrowers in a customer base that is unfamiliar with banking. Lending to those who are more likely to default on loans decreases the profits of Home Credit and results in negative customer experiences.

**Analytic Problem:**

The target variable is specificially customers that do have a negative history of repayment to lend to, and postive repayment. Represented in the application_train/test.csv sets of binary where 1 = Not trust worthy borrower (Client with payment difficulties), 0 = Trustworthy borrower (client with good repayment history).

Develop a model that will predict which customers will be good borrowers, using a classification method based on customer financial behavior data.

## Solution to Business Problem
My groups solution to the problem was a Gradient Boosting Model. This model gave us a Kaggle score of .656 and AUC of .669. 

Based on our model, we found that important factors to consider that the person will default are

1. Many enquiries to Credit Bureau 1 day before application
2. Client provided work phone
3. Low rated Regions of city where the client was from based on address
4. High price of goods that the loan was used for
5. Many enqiries to the Credit Bureau 1 hour before application
6. Permanent Address does not match the Contact Address of the Client


## Individual Contribution
Throughout the phases of this project, I contriduted by, 

**Exploratory Data Analysis:**

- Developing the Project Objective, Business Problem, and Analytic Problem
- Listing clear definitions for each of the variables of the data sets that were provided
- Exploring through each of the datasets by creating the dataframes,
- Finding common columns among the dataframes
- Exploring the summary stats for all of the numeric columns within the dataframes
- Exploring summary information of the categorical variables in the datasets
- Getting the unique values for the categorical columns in the dataframe

**Modeling:***
- Preparing the dataframes by merging selected dataframes to get the best information
- Built the Multiple Regression, Random Forrest Classifier, and Ensemble Model
- For each model I built, tuned the hyperparameters, evaluated the performance of the best model created, finding and discussing the top features towward a customer defaulting on a loan, ran the model against the test set
- Created a Model Performance Summary Table that allowed our group to easily compare which of our models is the best.
- Discussed the results from our models of the top features of a client that would be important when consdiering if they would default on their loan. 

**Presentation***
- Gave a professional presentation on solutions to Home Credit
- Made aesthetic slides that communicated the solution and reasoning to Home Credit

## Impact/Business Value:

Home Credit can lower costs by using this model to predict if a customer is going to default based on their history. Home Credit can also have


## Difficulties Along the Way
README: Difficulties that your group encountered along the way.

## Key Take Aways
README: What you learned in the project.
