# Lending Club Case Study
>This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

>Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

>If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#contributors)

## General Information
- When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- So, company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knownledge for its portfolio and risk assessment. 

## Technologies Used
- Python - version 3.0
- Library used - Pandas, Numpy, Matplotlib, Seaborn

## Conclusions
- Lending club should reduce the high interest loans for 60 months tenure, they are prone to loan default.
- Lending club shouldn't give loan to those borrowers whose loan status is ‘Verified’ as they taken high amount of loan with 60 months tenure.
- Borrower’s will be defaulted when they are having home ownership as ‘Rent’ and they take loan for the purpose of debt consolidation for Credit card payments.
- Borrower’s whose annual income is low i.e. between 20k are more defaulted.
- Lending club shouldn't give loans to thoses borrowers, who takes loan amount in the range 0 to 14000.
- Borrower’s who receive interest at the rate of 15-20%, will be defaulted more.
- Borrower who takes loan for the purpose of small business, Debt consolidation and cedit card payments are more defaults.
- Grades are good metric for detecting defaulters. Lending club should examine more information from borrowers before issuing loans to Low grade (G to A).
- Lending Club shouldn't provide loans to these states i.e. NV, AK, TN, SD, as most of the people are defaulted from these places only.
- Those borrowers whom employment length is less than and equals to 1 are more prone to defulater, Lending club should aware of these while giving loans.


## Contributors
* [Aakash Sharma](#aakash804)
* [Sweta Samant](#Sweta)
