# LOAN REJECTION FACTORS - SQL

## BUSINESS PROBLEM
To determine whether a loan will be approved, banks or finance companies consider many factors in a single application, including demographics, financial health, loan amount, interest rate, ... Based on this, businesses can develop a scale to assess risk and optimize loan financing. First, they need to consider: 
- Do these factors impact the decision?
- Which factors are most important?
- Are there any gray areas (applications that are difficult to decide on)?
## DATASET
Description: The blinkit dataset is LOAN_PROJECT.CSV
- 4000 rows (0 dulicates, 0 missing)
- 14 columns: ID,	Age, Income, Employment_Years, Married, Dependents, Loan_Amount, Loan_Term, Credit_Score, Existing_Loans, Debt_to_Income, Payment_History, Purpose_loan, Loan_Approval.

Source: https://www.kaggle.com/datasets/ckskaggle/loan-approval-data (train dataset)  

## WHAT I DID:
The SQL commands used to execute this project include:
- DDL: Create dataset, table and import values.
- DML: Delete invalid data
- DQL: Analysis from overall data, assess factors, identify the gray area (JOIN, Subquery, CTE, Window functions)

## INSIGHTS:
- Loan approval is driven primarily by strong financial foundations, such as high income and superior credit scores, rather than demographic factors.
- The system prioritizes safety and repayment stability by favoring applicants with low debt-to-income ratios (0.2–0.6) and those in the 36–55 age bracket.
- Loan purposes shift across the life cycle, with prime-age adults focusing on business and debt consolidation, while younger and older groups prioritize education.
- Strategic Growth: While financial security remains the priority, refining criteria for "gray cases" presents a key opportunity to boost sales without compromising overall profitability.

## RECOMMENDATIONS
- Segmented Marketing: Focus "Business/Debt" ads on middle age and "Education" on younger/older groups.
- High-Value Leads: Prioritize leads with proven payment history to maximize the approval potential.
- Designing an internal credit scoring system: transforming data into a specific number, helping the sales and approval departments work more consistently.
