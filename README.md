# Project Name
> Lending_Club_Case, [EDA for an online loan marketplace company, facilitating personal loans,]


## Table of Contents
* [Business Problem Overview](#Business Problem Overview)
* [Data Overview](#Data Overview)
* [Data Cleaning](#Data Cleaning)
* [Exploratory Data Analysis](#Exploratory Data Analysis)
* [Insights and Recommendations](#Insights and Recommendations)

<!-- You can include any other section that is pertinent to your problem -->

## Business Problem Overview
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.process, earn more through the interest on loans.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Data Overview
- The data contains information about 39717 customers and their  information with 111 columns.
- The details for each customer includes ID, loan_amnt, installment, purpose of the loan request, Annual income, the status of the loan in two types of decisions:
* Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
* Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
* Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
* Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan.
- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset).All the provided variables are numerical and no  conversion is needed.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Insights and Recommendations
- The highlighted point on the presentation can be used to have a general idea of any customer requested a loan to estimate his pattern.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
Created by [@yassineelhallaoui] - feel free to contact me!
