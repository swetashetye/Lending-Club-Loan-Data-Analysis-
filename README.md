# Lending Club Loan Data Analysis
Lending Club (LC) is the world’s largest online marketplace connecting borrowers and investors. It is transforming the banking system to make credit more affordable and investing more rewarding. Lending Club operates at a lower cost than traditional bank lending programs and pass the savings on to borrowers in the form of lower rates and to investors in the form of solid risk-adjusted returns.

## OBJECTIVE
We are expected to play with the data provided by LC, conduct a set of exploratory analysis and try to apply various machine learning techniques to predict whether or not a loan will be default using the historical data.

## DATA
Kaggle has the perfect one for us - [Lending Club Loan Data](https://www.kaggle.com/swetashetye/lending-club-loan-data-imbalance-dataset).

There are 14 data attributes in total, however, not all of them can contribute to data analysis or can be used as features for machine learning techniques.

A quick look at what the columns in the dataset represent:

1. credit.policy: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.

2. purpose: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").

3. int.rate: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.

4. installment: The monthly installments owed by the borrower if the loan is funded.

5. log.annual.inc: The natural log of the self-reported annual income of the borrower.

6. dti: The debt-to-income ratio of the borrower (amount of debt divided by annual income).

7. fico: The FICO credit score of the borrower.

8. days.with.cr.line: The number of days the borrower has had a credit line.

9. revol.bal: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).

## STEP-BY-STEP PROBLEM SOLVING APPROACH
1. Import and clean data
2. Exploratory data analysis
3.	Data preprocessing
4.	Develop machine learning model
5.	Conclusion 

As you will see  this dataset is highly imbalanced and includes a lot of features that make this problem more challenging.
