## module 0. "Guess the Number!"

The computer guesses an integer from 1 to 100, and you have to guess it.
By "guess", of course, we mean "write a programme that guesses the number".
In my algorithm, I use selecting the middle value of the range. After each attempt, I reduce the range if the guessed value is larger/lower than the average.


## module 1. "Who wants to be a film distribution millionaire?":

### Project Objectives:

    Try on the role of an analyst at a film distribution company.
    to conduct your first data analysis using pandas.

## module 2. Exploratory data analysis for a project from UNICEF:

UNICEF, an international arm of the United Nations whose mission is to improve the well-being of children around the world.

The point of the project is to track the impact of the living conditions of students aged 15 to 22 on their performance in maths, in order to identify at-risk students early on. And this can be done with the help of a model that would predict the results of the state maths exam for each student in the school. To decide on the parameters of the future model, conduct an exploratory data analysis and report on the results.

### Main Project Goals and Objectives (EDA):

    Formulate assumptions and hypotheses to further build the model.
    Check the quality of the data and cleanse it if necessary.
    Decide on the parameters of the model.

#### Project Work Stages:

    Conduct initial data processing.
    Look at the distribution of signs for numeric variables, eliminate outliers.
    Estimate the number of unique values for nominal variables.
    Transform the data as necessary.
    Conduct correlation analyses for quantitative variables.
    Select variables that are not correlated.
    Analyse nominative variables and eliminate those that do not affect the predicted value.
    Formulate conclusions regarding the quality of the data and the variables that we will use in the further construction of the model.

## module 3. Project for TripAdvisor:

### Task:
One of the company's problems is dishonest restaurants that inflate their ratings. One way to find such restaurants is to build a model that predicts the restaurant's rating. If the model's predictions are very different from the actual result, then perhaps the restaurant is not playing fair and should be checked out.

#### Stages of the project:
    Add new data to the original dataset.
    Do reconnaissance of new attributes. Use visualisation, search for unique values, cleanup and look for outliers where appropriate.
    Include the new features in the analysis of the main variables, assess their importance and contribution to the model, consider whether new features can be generated from the added ones.
    Obtain a new ROC AUC value for the new model and try to improve its results based on fitting regularisation parameters.

## module 4. Project for a regional bank:

### Task:
Write a scoring model for predicting default of bank customers.

#### Project steps:
    Add new data to the original dataset.
    Do exploration of new features. Use visualisation, search for unique values, cleaning and outlier search where appropriate.
    Include the new features in the analysis of the main variables, assess their importance and contribution to the model, consider whether new features can be generated from the added ones.
    Obtain a new ROC AUC value for the new model and try to improve its results based on fitting regularisation parameters.

## module 5. Project for a company that sells used cars in Moscow:

### Task:
To find favourable offers (buy below market, sell above market) as quickly as possible. The company's management asks to create a model that will predict the cost of a car based on its characteristics. This will significantly speed up the work of managers and increase the company's profit.

### The result of the work
As a result of training different models, the best result was shown by XGBRegressor with the parameter reg_lambda=1.5 In the work we managed to create a model that predicts the cost of a car by its characteristics. This model can be used to identify favourable offers when the seller's desired price is lower than the predicted market price.
