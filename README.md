# Lending Club Case Study
## Table of Contents
* [Project Description](#project-description)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#contributors)

# Project Description
The project involves working for a consumer finance company that specializes in lending loans to urban customers. When the company receives a loan application, it needs to make a decision on whether to approve the loan or not based on the applicant's profile. The decision is crucial because it involves two types of risks:

    * Loss of business: If the applicant is likely to repay the loan but the loan is not approved, it results in a loss of business for the company.
    * Financial loss: If the applicant is not likely to repay the loan (i.e., likely to default), but the loan is approved, it may lead to a financial loss for the company.

The goal of the project is to analyze historical data of past loan applicants and their repayment behavior (whether they defaulted or not) to identify patterns and factors that influence the likelihood of defaulting. This analysis, performed through Exploratory Data Analysis (EDA), aims to uncover insights into consumer attributes and loan attributes that can be used to make informed decisions such as denying loans, reducing loan amounts, or lending to risky applicants at higher interest rates.

The loan decisions made by the company can result in three scenarios:

    * Loan accepted: If the company approves the loan, three possibilities can arise:
        * Fully paid: The applicant has fully paid the loan, including the principal amount and the interest rate.
        * Current: The applicant is in the process of paying the loan installments, and the loan tenure is not yet completed. These applicants are not labeled as defaulted.
        * Charged-off: The applicant has not paid the loan installments on time for an extended period, indicating a default on the loan.

    * Loan rejected: The company rejects the loan application, usually due to the applicant not meeting their requirements or other factors. Since the loan is rejected, there is no transactional history available for these applicants in the company's dataset. 



## Technologies Used
- NumPy - version 1.23.5
- Pandas - version 1.5.3
- Matplotlib - version 3.7.0
- Seaborn- version 0.12.2

## Conclusions
 - Identification of strong drivers for loan default
    - Term size
    - Income
    - Loan amount
    - Purpose
    - Public records
    - Total credit lines (derived closed credit lines)
    - Credit utilization
    - Debt to income ratio
    - State

## Contributors
* [Chaitanya Vootla](https://github.com/ChaitanyaVootla )
* [Mohith Gutha](https://github.com/MohithGutha)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->