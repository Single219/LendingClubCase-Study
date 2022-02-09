# LendingClubCaseStudy

## Objective
#### The objective of this exercise is to identify patterns that indicate a person is likely to default, which can then be used to take  steps such as refusing the loan, lowering the loan amount, or lending (to riskier applicants) at a higher interest rate.

## Steps followed in this exercise
1. Data Cleaning
    a. Remove columns that contain no valuable data and have a high number of null values
    b.Identify null rows and delete or replace them with pertinent data. 
2. Identify outliers and delete those rows.
3. Create additional columns
4. Univariate Data Analysis
5. Bivariate Data Analysis
6. Multivariate Data Analysis

## Observations
1. Distribution of  loan amount and funded amounts are almost same
2. Most of the loans are taken with the interest rates between 10 -15%
3. Most of the loans are taken for the debt consolidation purpose
4. Most of the loans are taken by the people living in rent house or to mortgage  their home. Charged Off is high from these categories
5. Most of the loans are taken with less duration and charged off portion is high with less duration loans
6. The charged-off part is significantly higher in low-income households. As revenue grows, the charged-off share decreases
7. Charged off portion is. increasing with high interest loans
8. Charged off portion is increasing as the loan amount increased.

## Recommendations:
1. Avoid high-interest loans, particularly those with a rate greater than 15%.
2. Avoid lending to individuals who have previously defaulted.
3. Provide less loans to persons who are unemployed or have been unemployed for less than a year.
4. Avoid providing high-grade loans at a high interest rate to individuals seeking financing for small businesses. 
5. Provide less loans to persons who are staying in the rented house

## Frameworks and Libraries used
1. Python
2. Pandas
3. numpy
4. seaborn
5. matplotlib