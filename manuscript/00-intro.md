
# Introduction

A bank has provided you with a dataset of Unsecured Personal Loans (UPLs) collected over the past two years. A description of all the variables is given in Table 1. 

{title = "Table 1"}
|--------------------|-----------------------------------------------------------------------------|
|purpose             |0: standard credit card; 1: balance transfer                                 |
|age                 |applicant age (in years)                                                     |
|marital             |1 if applicant is married; 0 otherwise                                       |
|employment          |1 employed full time                                                         |
|                    |2 employed part time                                                         |
|                    |3 self employed                                                              |
|                    |4 temporary employment                                                       |
|                    |5 homemaker                                                                  |
|                    |6 retired                                                                    |
|annual_income       |annual gross income                                                          |
|debt_to_income      |ratio of existing liabilities to annual income                               |
|market_value        |market value of property                                                     |
|own_property        |1 if applicant is a property owner; 0 otherwise                              |
|late_repayments     |1 if applicant delayed any debt repayment during the last year; 0 otherwise  |
|repossess           |1 if applicant has had private property repossessed in the past; 0 otherwise |
|conviction          |1 if applicant has ever been convicted; 0 otherwise                          |
|bankruptcy          |1 if applicant has declared bankruptcy; 0 otherwise                          |
|unspent_convictions |1 if applicant has unspent convictions; 0 otherwise                          |
|credit_applications |number of applications for credit in the past 12 months                      |
|credit_line_age     |age of longest credit line (in months)                                       |
|exist_customer      |1 if applicant is an existing customer                                       |
|**bad**             |1 bad customer                                                               |
|                    |0 good customer                                                              |

A bad customer is someone who has missed three or more payments during the first year of the loan. Identifying bad customers is very important for the bank because the loss from each bad customer is on average five times larger than the profit from a good customer. So even if the number of bad customers in the dataset is relatively small they have a large impact on profits. Your objective is to conduct a thorough analysis of the data and recommend a model to identify customers with a high risk of being '**bad**'.
- What is the maximum proportion of good customers that can be granted loans while ensuring that x% of the bad customers are correctly identified.
- What is the maximum proportion of the overall population that can be granted loans while ensuring that x% of the bad customers are correctly identified.