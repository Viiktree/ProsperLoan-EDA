# ProsperLoan Data Exploration
## by Okechukwu Victory


## Dataset

Prosper was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Through Prosper, people can invest in each other in a way that is financially and socially rewarding. Borrowers apply online for a fixed-rate, fixed-term loan. Individuals and institutions can invest in the loans and earn attractive returns. Prosper handles all loan servicing on behalf of the matched borrowers and investors.

The prosper loan data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

## Summary of Findings

From my investigation it shows that indeed the borrower rates has the highest effect on the Loan status, the higher the rates the more likely it is to have missing payments or deliquency of loans. this is more evident when looking at the different loan term categories. it shows clearly in the 36 months term that with higher borrower rate the days of deliquency increases but defaulted or charged off loans are lower. where as in the longer term category which is the 60 months term that the defaulted and charged off loans have the highest borrowers rate. It also shows that the borrowers working full time in the 36 months term have the highest defaulted and charged off loans


## Key Insights for Presentation
In my presentation i focus on the effect of borrowers rate and loan term categories on the the main variable loan status to determine the causes of missing payments. I start by introducing the counts for the categories of loan status variable, because the data was highly skewed a logarithm transform was used. Followed by a plot of thehistogram distribution of the borrowers rate variable.

Then a lineplot was introduced to show the counts of the various loan status categories across the various loan term categories. lastly a boxplot for the borrowers rate of the different categories was plotted across different loan term categories. a color palette was used to differentiate the various loan status categories.