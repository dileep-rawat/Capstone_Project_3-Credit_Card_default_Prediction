# Capstone_Project_3-Credit_Card_default_Prediction

<p align="center">
  <img width="500" height="300" src="https://github.com/dileep-rawat/Capstone_Project_3-Credit_Card_default_Prediction/blob/main/credit%20card%20Default.jpeg">
</p>

# Statement
The purpose of this project is to conduct quantitative analysis on credit card default risk by using machine learning models with accessible customer data, instead of credit score or credit history, with the goal of assisting and speeding up the human decision making process.

# Attribute Information: 

### This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:
*  X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
*  X2: Gender (1 = male; 2 = female).
*  X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
*  X4: Marital status (1 = married; 2 = single; 3 = others).
*  X5: Age (year).
*  X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
*  X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
*  X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

# Overview
This project aims to build a classification model that can predict whether or not a customer will default on their credit card. From the perspective of risk management, understanding the customer characteristics that lead to this outcome can aid creditors in deciding reasonable credit limits to prevent this. After cleaning the data, handling class imbalance, feature engineering and tuning hyperparameters, the final XG Boost model achieved with a F1 score of 0.928.


