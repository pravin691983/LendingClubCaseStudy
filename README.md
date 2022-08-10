# Lending Club Case Study - Loan Dataset
> Identification of risky loan applicants using EDA is the aim of this case study, so that such loans can be reduced thereby cutting down the amount of credit loss..

<p>
<img src ="https://cdn.upgrad.com/UpGrad/temp/7afbce98-8ecc-41c6-96d8-981cba7d343f/Loan_image.png" alt='Figure 1'>
<center> <b>Figure 1. Loan Data Set</b> </center> 
 </br>  
</p>

## Table of Contents
* [Overview Business Understanding](#overview-business-understanding)
* [Problem Statement Business Objectives](#problem-statement-business-objectives)
* [Data in depth](#data-in-depth)
* [Approach](#approach)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Overview Business Understanding
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. 
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). 
- Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. 
- In this case, the customers labelled as 'charged-off' are the 'defaulters'. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. 
- Identification of such applicants using EDA is the aim of this case study.

## Problem Statement Business Objectives
Identification of risky loan applicants using EDA is the aim of this case study, so that such loans can be reduced thereby cutting down the amount of credit loss.

### Want to
 * Understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. 
 * The company can utilise this knowledge for its portfolio and risk assessment.

## Data in depth
-  We are going to analyze loan datasets, 
- The datasets contains details information related of the loans such as loan amount, funded amount, interest rate, repay terms in months etc. 
- The dataset comprises of 38717 observations of 111 columns. Below is a table showing names of the few columns.

## Approach
  #### Understanding the Dataset
  - To gain insights from data we must look into each aspect of it very carefully. We will start with observing few rows and columns of data both from the starting and from the end.
  #### Preprocessing
  - We will deal with erroneous, missing and outliers values of columns.
  - Correlation between different columns
  - See how preprocessing have transformed our dataset.
  - Derive new data from existing data to get more insite 
  #### Exploratory Data Analysis on Loan Dataset
  - Try to find out answers of some set of questions


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Based on our analysis there is high probability if applicants taking loan:
 - for 'debt consolidation' and have income of 31k -58k
 - whose home ownership is RENT and have income of 31k -58k
 - when grade is B and loan amount is between 31k -58k
 - when dti is between 12-18 and loan amount is between 31k -58k
 - tenure of 36 months have have high chances to be defaulters
 - maximum number of defaults occured when the loan was sanctioned/issued in Dec


### We can see loan amount & interest rate, installment, repayment term, home ownership, loan purpose, residential state and income group plays an important role's to decide loan defaulters.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python
- Numpy
- Panda
- Matplotlib
- Seaborn
- Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@pravin691983] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
