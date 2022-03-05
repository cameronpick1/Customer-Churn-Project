Customer Churn- My research questions were: 
i. Is there a relationship between demographic variables and a customer leaving? 

ii. Is there a relationship between the company’s product variables and a customer leaving? 

iii. Which one has the great effect, (1) or (2), and what is the correlation between those variables and customer attrition? 

iv. Lastly, can I predict when a customer will leave based on variables from (1) or (2)?

The variables are-
Attrition-Dependent variable
Age
Gender
How many dependents
Education
Marital Status
Income
Card Category
Months on book
Total number of products held by the customer
Number of  months inactive 
Number of contacts count
Credit limit
Total revolving balance
Average open to buy(The difference between the credit limit assigned to a cardholder account and the present balance on the account)
Change in Transaction Amount (Q4 over Q1)
Total Transaction Amount (Last 12 months)
Total Transaction Count (Last 12 months)
Change in Transaction Count (Q4 over Q1)
Average utilization ratio
Naive Bayes 1
Naive Bayes 2

There was a lot of variables, and after some analysis, many were dropped. SMOTE was chosen as a way to balance this dataset for this project. This method involves addressing imbalanced datasets by oversampling the minority class. The simplest approach involves duplicating examples in the minority class, although these examples don’t add any new information to the model. R has a built in function for this. Then, logistic regression model created for the dataset.
