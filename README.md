# Customer Churn Analysis
Keeping customers is just as important as getting new ones.  So, being able to predict their spending habits and decision making is an incredibly valuable skill for businesses to practice.  This dataset provides informaation gathered from user accounts of a central american telecom company.  In this exercise I use the customer profile data, which includes information like, number of calls each month, number of minutes used, payment history, etc... to predict whether the customer would cancel their service in the next month.  

## The process
The initial exploratory data analysis showed several categorical variables which were then encoded using pandas. Once the data had been engineered into a format that the SKLearn library would work with, it was used to create several models whose accuracy was then compared.  The Random Forrest Model was by far the most accurate at 95%  
