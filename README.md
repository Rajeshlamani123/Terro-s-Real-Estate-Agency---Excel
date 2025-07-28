# Terro-s-Real-Estate-Agency---Excel
## Problem Statement (Situation):
### “Finding out the most relevant features for pricing of a house”
Terro’s real-estate is an agency that estimates the pricing of houses in a certain locality. The pricing is
concluded based on different features / factors of a property. This also helps them in identifying the
business value of a property. To do this activity the company employs an “Auditor”, who studies
various geographic features of a property like pollution level (NOX), crime rate, education facilities
(pupil to teacher ratio), connectivity (distance from highway), etc. This helps in determining the price
of a property.
The agency has provided a dataset of 506 houses in Boston.

### Dataset Used:
[Dataset](https://d2fs5ql1w4aws3.cloudfront.net/account_1/attachments/965291/Dataset-%20Terro%2527s_REA.xlsx?response_content_disposition=attachment%3B+filename%3D%22Terro%27s_REA.xlsx%22%3B+filename%2A%3DUTF-8%27%27Terro%2527s%255FREA.xlsx&Expires=1753549381&Signature=xuNFBQ5m5gRFJwQJM1smeK~t5qG7EAF5OcVysA2QTXUqJfcDPBzeRXpRPiyHjXxhdwnvRRDUxOr4GpODlW3SaEy0XxH4gl8mYppuW3uFiptBNZg4XvRdEx2W73DqwtJjstfmxyiwZF8V4opHHZBOGD~WF5QJN7lbp6ssQEAS6mCPHOsi1jTuSDsS9iTkWrevDTptOgZ9CR0u12vPWjpTsXkM2fhdgaUFd7duhIVwOqizCPy7bAdYAyAqV8gPZBAu9S1QLlbJJThX~NX7E3v5OoRkiBTmELwye4EnGVsPopydA5-oB4x79qcBjBYSMeUCQcLobtLUeOofNDvOwnvtNA__&Key-Pair-Id=K2UFIFWGO8GS9H) 

#### Source: Great Learning

Following are the details of the dataset:
## Data Dictionary:
| Attribute   | Description                                                             |
|-------------|-------------------------------------------------------------------------|
| CRIME RATE | Per capita crime rate by town                                           |
| INDUSTRY   | Proportion of non-retail business acres per town (percentage)           |
| NOX        | Nitric oxides concentration (parts per 10 million)                      |
| AVG_ROOM   | Average number of rooms per house                                       |
| AGE        | Proportion of houses built before 1940 (percentage)                     |
| DISTANCE   | Distance from employment centers/highways (in miles)                    |
| TAX        | Full-value property-tax rate per $10,000                                |
| PTRATIO    | Pupil-teacher ratio by town                                             |
| LSTAT      | % of lower status population                                            |
| AVG_PRICE  | Average value of homes in $1000's   

## Objective (Task):
Your job, as an auditor, is to analyze the magnitude of each variable to which it can affect the price of a house in a particular locality.

To do the analysis, you are expected to solve these questions:

1) Generate the summary statistics for each variable in the table. Write
down your observation.

2) Plot a histogram of the Avg_Price variable. What do you infer?

3) Compute the covariance matrix. Share your observations.

4) Create a correlation matrix of all the variables.       
 a) Which are the top 3 positively correlated pairs and                                    
 b) Which are the top 3 negatively correlated pairs.

5) Build an initial regression model with AVG_PRICE as ‘y’ (Dependent variable) and LSTAT variable as Independent Variable. Generate the residual plot.                                                                                                                                                                                                                        
 a) What do you infer from the Regression Summary output in terms of variance explained,
 coefficient value, Intercept, and the Residual plot?                                      
 b) Is LSTAT variable significant for the analysis based on your model?

6) Build a new Regression model including LSTAT and AVG_ROOM together as Independent variables
and AVG_PRICE as dependent variable.                                                                                                                                                                                                                                                 
 a) Write the Regression equation. If a new house in this locality has 7 rooms (on an average)    and has a value of 20 for L-STAT, then what will be the value of AVG_PRICE? How does it compare
 to the company quoting a value of 30000 USD for this locality? Is the company Overcharging/
 Undercharging?                                                                        
 b) Is the performance of this model better than the previous model you built in Question 5?
 Compare in terms of adjusted R-square and explain.

7) Build another Regression model with all variables where AVG_PRICE alone be the Dependent
Variable and all the other variables are independent. Interpret the output in terms of adjusted Rsquare, coefficient and Intercept values. Explain the significance of each independent variable with respect to AVG_PRICE.                                                   

8) Pick out only the significant variables from the previous question. Make another instance of the Regression model using only the significant variables you just picked and answer the questions below:                                                                                                                                                                              
 a) Interpret the output of this model.                                                    
 b) Compare the adjusted R-square value of this model with the model in the previous question,
 which model performs better according to the value of adjusted R-square?
 c) Sort the values of the Coefficients in ascending order. What will happen to the average       price if the value of NOX is more in a locality in this town?                              
 d) Write the regression equation from this model.

## Learning Outcome (Result):
● Implementation of Exploratory Data Analysis helps you to understand the nature of different
data-attributes.                                                                      
● You will understand how to use various statistical/analytical tools in MS Excel like Summary
  statistics, Histogram, correlation table, Regression analysis (using Data analysis tool pack).
