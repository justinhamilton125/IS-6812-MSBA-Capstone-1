
**[Click Here to view my Portfolio Repository with all Project Folders](https://github.com/justinhamilton125/Justin_Hamilton_Portfolio/tree/main)**

There is currently only 1 project, but this repo is intended to be updated with multiple projects.


# [Project 1: Home Credit Default Analysis]([https://github.com/justinhamilton125/Justin-Hamilton-Portfolio](https://github.com/justinhamilton125/Justin_Hamilton_Portfolio/tree/main/Project%201:%20Home%20Credit%20Default%20Model%20Files))

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

**Modeling:**
- Preparing the dataframes by merging selected dataframes to get the best information
- Built the Multiple Regression, Random Forrest Classifier, and Ensemble Model
- For each model I built, tuned the hyperparameters, evaluated the performance of the best model created, finding and discussing the top features towward a customer defaulting on a loan, ran the model against the test set
- Created a Model Performance Summary Table that allowed our group to easily compare which of our models is the best.
- Discussed the results from our models of the top features of a client that would be important when consdiering if they would default on their loan. 

**Presentation**
- Gave a professional presentation on solutions to Home Credit
- Made aesthetic slides that communicated the solution and reasoning to Home Credit

## Impact/Business Value:

Home Credit can lower costs by using this model to predict if a customer is going to default based on their history. Home Credit also benefits with this model by lowering risk of giving a loan to someone who is going to default. Using this model allows for Home Credit to see exactly which customer is predicted to default. Using that information, they can then only give the loan to these who are predicted to not default. This decision making process lowers risk of giving to someone that will default, lowers cost of never having a loan completed on payments, and increases revenue by lending to only those that are predicted to make payments on their loan which is the revenue for Home Credit. This combination of lowered risk, lowered cost, and increasing revenue will lead to an increase of profits.


## Difficulties Along the Way
Throughout this project, the main difficulties our group encountered were related to the capacity of our computers memory and processing units. We each were only using laptops with minimal storage, and to run the models at times took nearly 8 hours. Due to the time that it took for a model to run, it was difficult to time and train the exact results to what we wanted/needed.


## Key Take Aways
Throughout this project my main key takeaways were that 
- There is a power in people. Collaboration helps one another to find better solutions within the data and seeing new perspectives about how to solve problems.
- When it comes to doing a data analysis, it is more than finding the variables. A good analysis will find a solution, but a great analysis will show impact and connect to the business value.
- A sense of curiousity is important when it comes to data analysis. It may take a bit of curiousity to see how each of your solutions can be interepreted into a meaningful information to learn from. It is important to stay curious as you go through the analysis because the curiousity will motivate you to dig deep into the data and push you to find solutions you would not have thought of originally.
