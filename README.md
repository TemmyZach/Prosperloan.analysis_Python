# Prosperloan.analysis_Python
This is an Exploratory Data Analysis (EDA) performed on the Prosper Loan Dataset to understand borrower behaviours and their impact on the trends in the loan market. Prosper Loan is a leading marketplace lending company in the United States that has funded over $9 billion in loans. It's loan listing dataset which was sourced from Udacity contains information on the loan origination, borrowers characteristics and lenders activities from 2005 to 2015. With this dataset, a proper analysis can be done to understand borrower behaviours and their impact on the trends in the loan market.

#  Features and Structures
Some notable features of interest in this dataset includes: 
Loan Amount, Borrower APR, Loan Status, and Borrower characteristics like employment status, occupation, and credit score range. 
The dataset contains 113,937 rows and 81 columns.

# Summary of Findings
The analysis provides an understanding of borrower behaviors and how they are impacted by interest rates. The Borrower APR (Annual Percentage Rate) distribution chart for example, shows that borrowers are less willing to pay higher interest rates. Likewise, the relationship between borrower APR and lender yield indicates that fewer borrowers are willing to accept higher APRs. It will be adviseable in this instance to suggest that Prosper Loan should reconsider adjusting or lowering their APRs to attract more borrowers. 

One interesting finding is the high number of defaulted and charged-off borrowers. I investigated the potential cause of this negative outcome, and I came to the conclusion that borrowers who did not indicate their employment status or whose income range falls between $25,000 to $49,999 have higher likelihood of defaulting or charged-off loan status. This indicates that Prosper Loan should reconsider their loan approval policies and loan recovery approaches. Although, correlation does not necessarily imply causation and other factors may also be at play.

Homeownership on the other hand, has a positive correlation with a higher likelihood of having a current loan status as well as negatively correlated with a higher likelihood of having a charged-off or defaulted loan status. This suggests that home ownership may be a factor in a borrower's ability to make timely loan payments, while non-homeownership could be factor borrowers take out loans.

# Key Insights
Based on the analysis provided above, borrower characteristics and status play a significant role in determining a borrower's loan status. The study found that borrowers with high credit scores, low debt-to-income ratios, and stable employment status are more likely to have their loan applications approved and receive lower interest rates because  they are more likely to repay their loans. On the other hand, borrowers with low credit scores, high debt-to-income ratios, and inconsistent employment history are more likely to have their loan applications denied or receive higher interest rates.

Furthermore, the analysis suggests that loan default rates are higher among borrowers with low credit scores, high debt-to-income ratios, and limited credit histories. These findings suggest that lenders are likely to rely heavily on borrower characteristics and status in making loan approval decisions and setting interest rates.

