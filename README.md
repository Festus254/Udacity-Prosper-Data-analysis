# Prosper Dataset
## by Festus Kipsang Sambu


## Dataset

The dataset consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status etc. The dataset can be found here, with feature documentation available here


## Summary of Findings

During exploration, I did a deep dive on our variable of interest, Borrower's APR and found out that it had a negative correlation with LoanOriginalAmount where borrowers with High APR tend to get low loans and vice versa. Borrowers with their income verified tend to have a slightly lower APR compared to unverified borrowers. The same observation can also be seen with borrower's who own homes. It was interesting to see how borrowers with creditScore category AA and A(low risk borrowers), there APR tend to increase with increased term length compared to higher risk borrowers D and E where 12 months term tend to have highest APR and it reduces for the other groups. 

Outside our main variable of interest, we found out that the variable LoanOriginalAmount was positively skewed and did some data cleaning where I found some similar Columns and errornous rows which were removed. we found out that most of the borrowers are employed and the incomeRange for most customers is between 25000  75000(56% if the customer Base). 51% of the borrower's have homes and 92% have their income verified. I discovered that LoanOriginalAmount had a positive correlation with StatedMonthlyIncome, CreditScoreRangeLower and MonthlyLoanPayment. 


## Key Insights for Presentation

For the presentation, I just focus on features that could affect the borrower APR. I showed the distribution of Borrower's APR, followed by revealing the relationship between our focus variable with 3 variables(Loan Original Amount, MonthlyLoanPayment, CreditScoreRangeLower). Then, I checked how APR is affected by CreditRisk Score Group and finally showed the effect of creditScore Group on relationship between our focus Variable and Term. 