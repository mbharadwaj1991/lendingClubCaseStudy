# LendingClubCaseStudy
> Apply EDA technique to minimise risk of losing money while lending to customer

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#Contributors)


## General Information

Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed.  

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study. 

Perform an analysis to understand the driving factors (or driver variables) behind loan default, i.e.the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

Using following steps for data processing.

- Step 1: Data Cleaning
- Step 2: Univariate Analysis
- Step 3: Bivariate Analysis
- Step 4: Results/Conclusion


## Technologies Used
- Pandas library
- Numpy library 

## Conclusions

Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:
 - DTI
 - Grades
 - Annual income
   
Other considerations for 'defaults' :
 - Borrowers from large urban cities like california, new york, texas, florida etc.
 - Borrowers having annual income in the range 50000-100000.
 - Borrowers with least grades like E,F,G which indicates high risk.
 - Borrowers with very high Debt to Income value.
 - Lending club should reduce the high interest loans for 60 months tenure, they are prone to loan default.
 - Loans with a term of 36 months tended to be defaulted a lot more than loans with a term of 60 months, Choose a loan with a 60-month term.

## Contributors
- Mayank Bharadwaj

Developed as part of the Exloratory Data Analysis Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
