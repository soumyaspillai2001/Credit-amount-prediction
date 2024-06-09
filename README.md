# Credit-amount-prediction
Bank Customers Credit amount is predicted based on trained model on the credit amount data of the customers.

The objective of this problem is to predict the credit amount of each customer. The solution must be presented in the form of a csv with predicted values of the response variable credit_amount along with it’s corresponding serial number.

Description of Dataset columns:- 
a.  serial number : unique identification key

b. account_info : Categorized details of existing accounts of the individuals. The balance of money in account provided is stated by this variable

c. duration_month : Duration in months for which the credit is existing

d. credit_history : This categorical variable signifies the credit history of the individual who has taken the loan

    A30 signifies that no previous loans has been taken or all loans taken have been payed back.
    A31 signifies that all loans from the current bank has been payed off. Loan information of other banks are not available.
    A32 signifies loan exists but till now regular installments have been payed back in full amount.
    A33  signifies that significant delays have been seen in repayment of loan installments.
    A34 signifies other loans exist at the same bank. Irregular behaviour in repayment.

e. purpose: This variable signifies why the loan was taken

f. credit amount: The numerical variable signifies the amount credited to the individual (in units of a certain currency)

g. savings_account: This variable signifies details of the amount present in savings account of the individual:

h. employment_st: Categorical variable that signifies the employment status of everyone who has been alloted loans 

    A71 signifies that the individual is unemployed
    A72 signifies that the individual has been employed for less than a year
    A73 signifies that the individual has been employed for more than a year but less than four years
    A74 signifies that the individual has been employed more than four years but less than seven years
    A75 signifies that the individual has been employed for more than seven years

i. poi: This numerical variable signifies what percentage of disposable income is spent on loan interest amount.

j. personal_status: This categorical variable signifies the personal status of the individual

    A91 signifies that the individual is a separated or divorced male
    A92 signifies female individuals who are separated or divorced
    A93 signifies unmarried males
    A94 signifies married or widowed males
    A95 signifies single females

k. guarantors: Categorical variable which signifies if any other individual is involved with an individual loan case

    A101 signifies that only a single individual is involved in the loan application
    A102 signifies that one or more co-applicant is present in the loan application
    A103 signifies that gurantors are present.

l. resident_since: Numerical variable that signifies for how many years the applicant has been a resident

m. property_type: This qualitative variable defines the property holding information of the individual


    A121 signifies that the individual holds real estate property
    A122 signifies that the individual holds a building society savings agreement or life insurance
    A123 signifies that the individual holds cars or other properties
    A124 signifies that property information is not available

n. age: Numerical variable that signifies age in number of years

o. installment_type: This variable signifies other installment types taken

    A141 signifies installment to bank
    A142 signifies installment to outlets or stores
    A143 signifies that no information is present

p. housing_type: This is a categorical variable that signifies which type of housing does a applicant have.

    A151 signifies that the housing is on rent
    A152 signifies that the housing is owned by the applicant
    A153 signifies that no loan amount is present on the housing and there is no expense for the housing) 

q. credits_no: Numerical variable for number of credits taken by the person

r. job_type: Signifies the employment status of the person 

A171 signifies that the individual is unemployed or unskilled  and is a non-resident
A172 signifies that the individual is unskilled but is a resident
A173 signifies that the individual is a skilled employee or official
A174 signifies that the individual is involved in management or is self-employed or a highly qualified employee or officer

s. liables: Signifies number of persons dependent on the applicant

t. telephone: Signifies if the individual has a telephone or not

u. foreigner: Signifies if the individual is a foreigner or not (considering the country of residence of the bank)
