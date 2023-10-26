# Personal-Finance-Advisor-Solvd

## Project Description
    Welcome to financial advisor application.
    Users can input their salary, preferred currency, and desired annual interest rate.
    The system calculates the maximum loan amount they can obtain, the repayment plan,
    and the total interest paid over the loan term.

# Table of Conntents

1. [Technologies overview](#Technologies-overview)
2. [Input Data](#input-data)
3. [Output](#output)
4. [Installation and Running](#installation-and-running)
    - [Install guide](#install-guide)
    - [Run guide](#run-guide)


## Technologies overview 

* Main - JavaScript
    - Node version - v20.7.0
* Framework - express
* DataBase - mySQL
* Additional - Docker

## Input Data

Here's Data you can provide to reach more percise result from my Finance Advisor

* Salary - Monthly Income that we'll work with to give you an advice on managing them

* Currency - Wise choise of currency affects the success of investments.
 At least pay attention on: 
    - stability (market confidence in the external value of a currency)
    - liquidity (a currency pair's ability to be bought and sold without 
                 causing a significant change in its exchange rate)
    - reputation (the level of trust and acceptance that a specific currency enjoys
                  among individuals, businesses, and governments)

* Annual Interest Rate - Common practise is to divide Interest Rate
 Expectations into three categories
    - Conservative ( income < 5% )
    - Moderate ( 5% < income < 10% )
    - Aggressive ( income > 10% )


## Output

Here is the information that can be provided by Advisor
    
* the maximum loan amount they can obtain
* the repayment plan
* the total interest paid over the loan term.

## Installation and Running:

## Install guide

Clone the repo -> Get in to the project folder -> Install Dependencies
```
git clone git@github.com:timosheyka/Personal-Finance-Advisor-Solvd.git
```
```
cd Personal-Finance-Advisor-Solvd
```
```
npm install
```

## Run guide
```
node index.js
```