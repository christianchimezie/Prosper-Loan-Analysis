# (Prosper Loans Analysis)
## by (Christian Chimezie)


## Dataset

> The prosper loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), loan status, borrower income, borrower employment status, borrower credit history, and the latest payment information. 

### Data Analysis Steps
> - I cleaned and selected 14 features from the dataset after understanding the features provided in the Prosper variables definitions file.
> - I used Question-Visualization-Observations framework to narrate by exploration
> - I defined functions to avoid repetitive coding.
> - I extracted a sample of 1000 observations for some multivariate analysis to get a clearer picture.
> - I saved the cleaned data as *prosper_loan_master.csv*


## Summary of Findings

> Most of the loans are intermediate term loans with a repayment period of 1 to 5 years which are mostly used for debt consolidation (amount received from the new loan is used to pay off other debts). When consolidating debt, your credit is checked, which can lower or improve your credit score. Hence the normal distribution of the prosper rating. One of the biggest disadvantages of debt consolidation is that it is not accessible to everyone. From the analysis, most of the loans are given to employed persons with an income range of $25,000 and above. It is also observed that there is a steady increase in loan disbursements from 2009 till date after the global financial crisis. I am most interested in figuring out what features are best for predicting the borrower's Annual Percentage Rate and Loan Amount.


## Key Insights for Presentation

> - Relationship between the main features(BorrowerAPR and Loan Amount):The BorrowerAPR helps a borrower determine the true cost of the loan. From analysis there was a negative relationship which means that one variable tends to cause a decrease in another variable. The more money you borrow, the lower your BorrowerAPR
> - Prosper Rating Effect on Relationship between BorrowerAPR and Loan Amount: ProsperRating is a significant measure of loan amount and BorrowerAPR. ProsperRating tells us how risky the borrower is. Having a good ProsperRating can help to increase a borrower’s loan amount and improve BorrowerAPR. Since most of the loans is for debt consolidation, the ProsperRating is normally distributed.
> - Term Effect on Loan Amount: There is positive correlation between Term and Loan Amount. The higher the loan, the longer the term. 
> - IncomeRange effect on Loan Amount and BorrowerAPR: The income of borrowers played a significant role in determining the loan amount which also affects the BorrowerAPR. Borrowers with good sources of income can borrow large loans.