# Prosper-Loan-Dataset
### by David Alobo

## Introduction

This project is a Data Visualization project with Python, which is an important skill that is used in many parts of the data analysis process. This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process, which are:

-	Part I: Exploratory data visualization, that involved the use of Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. Exploratory data visualization generally occurs during and after data wrangling process, and it is the main method I deployed in understanding the patterns and relationships present in the data. This understanding helped me approach the statistical analyses and helped in building conclusions and findings. This process also illuminated additional data cleaning tasks to be performed.
-	
-	Part II: Explanatory data visualization, that involved the production of a short presentation that illustrates interesting properties, trends, and relationships that is discovered in any given dataset. The primary method of conveying my findings was through transforming the exploratory visualizations from the first part into polished, explanatory visualizations. Explanatory data visualization techniques are used after generating key findings, and are used to help communicate results to others.

## Datasets

The Dataset for this is the Prosper Loan Data (Download here). This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. About 10 -15 variables were explored for this project.

## Key Findings

- From this analysis we discovered that the factors that affect a loan's outcome was the amount of money borrowed and the interest rate of the loan.
- The correlation heat matrix helped to focus on the variables that had the biggest impact on the borrower's interest rate. Although there was little association between any of the variables, the credit score was the highest. The interest rate falls as the borrower's credit score rises.
- The "Not employed" or "1-24,999" categories in the income range category correlate with higher borrower interest rates. In a similar vein, unemployed people exhibit higher loan interest rates. This is because the higher the risk, the higher the interest rate. Cosmetic operations had the highest average interest rate for loan categories, followed by housing spending. The greatest loan amounts appear to be for debt consolidation and child adoption, and the greater the loan appeared to be, the more money people made.
- The average loan amount for the defaulted or past due dataset was less than the dataset as a whole, but it was interesting to note that the interest rate for those loans was 0.04 percent higher.
- The amount borrowed and the loan's interest rate appeared to have the biggest effects on a loan's outcome. Loans with higher interest rates and greater values appear to be more prone to default. The biggest spread was found among employed people, which makes sense given that I believe employed people are more likely to apply for and be approved for loans.
- The interest rate falls as the borrower's credit score rises. The interest rate represents the risk and therefore, the lower the risk, the lower the interest. There are a few cases when the loan size can also have an impact on the interest rate, although it's not as noticeable.

## Conclusions

The amount borrowed and the loan's interest rate appeared to have the biggest effects on a loan's outcome. Loans with higher interest rates and higher values appear to be more prone to default. The statistics showed that employed people had the widest spread. After limiting the data to loans that were just past due or in default, the means of loan amount and borrower interest rate were compared. Below are some of the findings:

- The average loan amount for the entire dataset is USD 8337.01.
- For the entire dataset, the mean borrower interest rate was USD0.19.
- For the dataset with solely defaulted or past-due loans, the mean borrower interest rate was USD0.23.

The correlation heat matrix was used to identify the elements that had the biggest impact on the borrower's interest rate. None of the features showed a particularly strong association, but the credit score was the highest. The interest rate falls with a higher credit score for the borrower. The loan quantity does have some influence on the interest rate in a few other cases, but it's not as noticeable.
The greatest loan amounts tend to be for debt consolidation and child adoption, and the more money people made, the bigger the loan appears to be.
