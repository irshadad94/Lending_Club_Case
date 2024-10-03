# LENDING CLUB CASE STUDY
> Lending club is the consumer finance company which specializes in lending various types of loans to urban customers. LC is the largest online loan marketplace, facilitating Personal loans, Business loans, and Financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. This case study analyses the loan data. 

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

**BACKGROUND**

Lending club is the consumer finance company which specializes in lending various types of loans to urban customers. LC is the largest online loan marketplace, facilitating Personal loans, Business loans, and Financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.


**PROBLEM STATEMENT**

- Lending companies face significant financial challenges due to credit loss, primarily stemming from borrowers who default on their loans. Identifying these 'risky' applicants those likely to become 'charged-off' or default can help lenders mitigate financial losses and optimize their lending strategies.
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders.

**OBJECTIVE**

- Identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. through consumer attributes and loan attributes which influence the tendency of default.
- Identifying the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.

**APPROACH**
- Understand Business Need
- Understand the Data
- Data Cleaning
- Handling Data Imbalance
- Data Exploration
- Data Visualization
- Observations and Insights



**DATASET**

Dataset : 
The dataset contains the complete loan data for all loans issued through the duration 2007 to 2011. 
The inputs contain:
- Dataset file – loan.csv
- Data dictionary - Data_Dictionary.xlsx
Data understanding : 
- The step involves details manual inspection of dataset file.
- Go through the data dictionary document and understand the data content
- Check if all columns specified in data dictionary are available in data set (4 columns found missing. Same are not being taken into consideration)
- Brief through the dataset file to understand the data spread
- Identify the ‘target variable’
Target column : 
- The primary column based on which the results need to be predicted is identified as  ‘loan_status’
- The variable in loan_status are : 
	- ‘Fully paid’ - Applicant has fully paid the loan (the principal and the interest rate)
	- ‘Current’ - Applicant is in the process of paying the instalments
	- ‘Charged off’ - Applicant has not paid the instalments in due time for a long period of time


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Annual income of loan applicants are falling between 30,000 and 70,000 indicating that mid-range salary drawer may tend to buy more loans.
- Applicants having 10+ years of experience and less than 1 year may tend to buy more loans.
- Chances are, applicants may default due to other monthly debts, in other words increase it debt-to-income ratio. It also includes that their home ownership is rented or mortgage.
- Applicants with grade E, F and G may tend to pay more interest as they fall under high-risk profiles.
- State CA, NY and FL records the most loan buyers.
- Applicant profile may get riskier when the number of inquires increases.
- Major purpose for the loan is debt consolidation, credit card and others.
- More the annual income, more the revolving balance and more the loan amount.
- Annual income source verified is lower charged off applicant when compared with verified.
- As the grade increases, the average annual income, loan amount, and revolving balance also increase.
- More the loan amount, loan enquiries and open accounts, the chances of loan defaulting increases.

To minimize the credit loss, Lending club can monitor below parameters:
Higher loan amounts, 
More inquiries, 
Open accounts 
High-risk profiles (grades E, F, G) 
High debt-to-income ratios.
Geographical patterns


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.2.2
- matplotlib - version 3.8.4
- seaborn - version 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This case study is to understand and explore the EDA techniques to identify the hidden pattern of defaulters
- It is faciliated by IIIT - Bangalore through the AI/ML program
- This project was based on risk analytics


## Contact
Created by [@irshadad94] - feel free to provide your inputs!

