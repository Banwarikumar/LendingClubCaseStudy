# Project Name: Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

### Project Information

> The project is a data science project that uses the lending club data set to predict whether a loan will be defaulted or not.

### Project Background

> Lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). The credit loss is the amount of money lost by the lender when the borrower refusesto pay or runs away with the money owed.  

> The main objective is to be able to identify these risky loan applicants,  then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.   

> Perform an analysis to understand the driving factors (or driver variables) behind loan default, i.e.the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.

> This company is the largest **online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures**. Borrowers can easily access lower interest rate loans through a fast online interface. Like most other lending companies, lending loans to **‘risky’** applicants is the largest source of financial loss (called credit loss). **Credit loss** is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

### Project Statement

> Find the driving factors which lead to the defaulted loans which are major source of loss for the company.

### Data Set

> The data set is a csv file with the loan data for the Lending Club.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:
  1. DTI
  2. Grades
  3. Verification Status
  4. Annual income
  5. Pub_rec_bankruptcies
- Other considerations for 'defaults' :
  1. Burrowers from large urban cities like california, new york, texas, florida etc.
  2. Burrowers having annual income in the range 50000-100000.
  3. Burrowers having Public Recorded Bankruptcy.
  4. Burrowers with least grades like E,F,G which indicates high risk.
  5. Burrowers with very high Debt to Income value.
  6. Burrowers with working experience 10+ years.
  7. Applicants having house_ownership as 'RENT'
  8. Applicants who use the loan to clear other debts
  9. Applicants who receive interest at the rate of 13-17%
  10. Applicants who have an income of range 31201 - 58402
  11. Applicants who have 20-37 open_acc
  12. Applicants with employement length of 10
  13. When funded amount by investor is between 5000-10000
  14. Loan amount is between 5429 - 10357
  15. Dti is between 12-18
  16. When monthly installments are between 145-274
  17. Term of 36 months
  18. When the loan status is Not verified
  19. When the no of enquiries in last 6 months is 0
  20. When the number of derogatory public records is 0
  21. When the purpose is 'debt_consolidation'
  22. Grade is 'B'
  23. And a total grade of 'B5' level.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Pandas - version 1.3.4
- NumPy - version 1.20.3
- Seaborn - version 0.11.2
- MatplotLib - version 3.4.3
- Plotly - version 5.7.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

> This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Created by [@Banwarikumar] - feel free to contact me!

<!-- Optional -->

<!-- ## License -->

## License

This project is open source and available without restrictions.

<!-- You don't have to include all sections - just the one's relevant to your project -->
