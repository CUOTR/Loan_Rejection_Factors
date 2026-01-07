# LOAN REJECTION FACTORS ANALYSIS PROJECT

## OVERVIEW

This project analyzes factors influencing loan rejection using a loan applications dataset.  
It identifies patterns in approved/rejected loans and suggests policy improvements.  
Analysis uses SQL; results presented in a report.  

**SOURCE**: https://www.kaggle.com/datasets/ckskaggle/loan-approval-data (train dataset)  

**Tools**: SQL (MySQL-compatible).  

## 1.Insights from overall data

**Key Insights**:  
- Approved: Higher income/credit than rejected.  
- High credit correlates with more borrowing/higher debt-to-income.  
- Approved favor low new_dti (0.2-0.6) for repayment.  
- Purposes vary: Education for young/old; business/debt consolidation for 25-65.  

## 2. Factors Assessment

**Key Insights**:  
- Age 36-55 most approved; marriage no impact.  
- Good payment history strong positive (6x in approved).  
- Constraints: Financial > Demographic > Loan; Safety > Profitability.  

## 3. Identifying the Gray Area

**Key Insights**: Gray cases exist; refine criteria for sales boost.  

## 4. Conclusion and Recommendations

- All factors influence (except marriage); finance key.  
- Prioritize business/debt consolidation.  
- Re-evaluate criteria for improvements.  
