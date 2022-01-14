# LendingClub_Analysis

## Explanation document for columns

*__credit.policy__: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.

*__purpose__: The purpose of the loan (takes values "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").

*__int.rate__: The interest rate of the loan, as a proportion (a rate of 11% would be stored as 0.11). Borrowers judged by LendingClub.com to be more risky are assigned higher interest rates.

*__installment__: The monthly installments owed by the borrower if the loan is funded.

*__log.annual.inc__: The natural log of the self-reported annual income of the borrower.

*__dti__: The debt-to-income ratio of the borrower (amount of debt divided by annual income).

*__fico__: The FICO credit score of the borrower.

*__days.with.cr.line__: The number of days the borrower has had a credit line.

*__revol.bal__: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).

*__revol.util__: The borrower's revolving line utilization rate (the amount of the credit line used relative to total credit available).

*__inq.last.6mths__: The borrower's number of inquiries by creditors in the last 6 months.

*__delinq.2yrs__: The number of times the borrower had been 30+ days past due on a payment in the past 2 years.

*__pub.rec__: The borrower's number of derogatory public records (bankruptcy filings, tax liens, or judgments).