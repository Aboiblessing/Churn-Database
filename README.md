# Churn-Database
## A Report documenting the analysis process, key findings, and recommendations
## Problem statement
The financial services industry's ecosystem is dynamic and multidimensional, characterized by a complex interplay of factors that influence consumer behaviors. In this complex environment, the ability to retain customers is more than a strategic advantage; it is a requirement for long-term growth and sustainability. The inherent challenges of customer attrition for financial institutions include substantial revenue loss and the erosion of brand loyalty.

As a result, a Canadian bank facing challenges in retaining its customer base reached out to Datafied Technologies. The bank is experiencing customer churn, impacting overall customer satisfaction and revenue, as well as they lack insights into the factors influencing customer decisions to leave or stay with the bank. There is a need to identify and address factors contributing to customer churn proactively and to do that, they provided a churn database containing information on 10,000 bank customers over six months. 
## Dataset Information
The data contains information on 10,000 Canadian bank customers who left or remained with the bank during a six-month period. The attributes are:
* CustomerId: Each customer has a specific identification called a CustomerId. 
*  Surname: This serves as the client's last name. It is a categorical variable
* Credit Score: This is the customer's credit score, which measures their creditworthiness numerically. Since a customer with a better credit score is less likely to quit the bank, a higher credit score often implies a lower credit risk and can affect customer turnover.
* Geography: This feature indicates the country of residence of the customer. 
* Gender: This feature represents the gender of the customer and can be either Male or Female. 
* Age: The customer's age, in years
* Tenure: The number of years that the consumer has been a bank client is shown by this characteristic
* Balance: The balance shows how much money is in their bank account.
* NumOfProducts: This feature shows how many distinct banking products the client has with the bank. It accepts values between 1 and 4. 
* HasCrCard: This variable indicates if the client has a credit card on file with the bank. The binary variable has the values 0 for "No" and 1 for "Yes." 
* IsActiveMember: This feature indicates if the consumer is an active bank member. It's a binary variable once more, with 0 denoting "No" and 1 denoting "Yes." 
* EstimatedSalary: This field contains data about the client's earnings. 
* Churned: This variable tells us whether or not the consumer left (churned). The variable is binary, with 0 denoting "No" (the consumer stayed) and 1 denoting "Yes" (the customer left or "churned").

  Data Source :[Data Dictionary]( https://docs.google.com/spreadsheets/d/1uaklnnc7yeQFgHBR4cP9w91QJcUypdRZWud-MMk8FQM/edit?usp=classroom_web&authuser=0)
  ## Objectives
   Addressing customer churn is critical for maintaining a stable customer base and sustaining the bank's financial health. This analysis will empower the bank to proactively implement retention strategies, enhancing customer satisfaction and loyalty.
   As a data analyst at Datafied Technologies, my task is to leverage Power BI for exploratory data analysis in order to provide valuable insight as to the factors influencing customer churn based on various demographic and banking behavior attributes,
  give a clear understanding of customer demographics, behaviors, and churn patterns, identify key features influencing customer churn and Provide strategic recommendations for the bank based on data-driven insights.
  ## Business Questions And Metrics
  In a bid to understand the requirements and objectives from the business problem, i identified key areas  to focus on and the questions the business needs answers to. The questions include:
  * What is our current customer churn rate, and how does it compare to industry benchmarks?
  * Which customer segments are most likely to churn, and what are the underlying reasons?
  *  Can we identify early warning signs of customer churn, and if so, what are they?
  *  How can customer experiences and satisfaction levels impact churn rates?
  ## Define the metrics and Key Performance Indicators (KPIs) that will help answer the business questions.
    * Total Bank Customer
    * Churn Rate Distribution
    * Churn Status
    * Demographic Distribution Analysis
 ## Data Modelling And Relationship
 New tables for identified dimensions were created and additional features that will help generate insights and add robustness to the analysis were added.
The data model was designed using the Star Schema where the different dimensions were connected to the Facts table in a one-to-many relationship.
 ![ER Diagram](https://github.com/user-attachments/assets/32b200ed-b8eb-4040-8b9a-82d0a9ced5a3)
## Data Visualization
Different charts were used to represent the metrics and insights.A drill-down was used to to make the dash board more interactive and also provide detailed information
![Dash Board](https://github.com/user-attachments/assets/6f25fd75-f1c0-4056-a4f5-9593b1ce404c)
## Insights
The following insights were generated from the dashboard metrics:
* 2,307 customers (20.4% of 10,000) have left the bank, resulting in a significant loss of revenue and potential long-term relationships.
* Out of the customers who churned, those with credit cards churned drastically.
* Majority of the bank customers are in the high income range,however over half of the customers who churned are high income earners.
* Most of the bank customers are Adults, however the young adults churned more.
* The bank had more customers with very good credit score who left the bank.
* Out of the churned customers, most of them were females.
## Recommendations
Below are my recommemndations tailored toward addressing the issues:
* Develop targeted marketing campaigns and service offerings focused on high-income customers' specific needs and preferences.
* Regularly solicit feedback from customers and promptly address any concerns or issues to prevent churn.
* Implement personalized marketing campaigns to target at-risk customers.
* Offer loyalty programs or rewards to long-term customers.
* Conduct regular customer feedback surveys to identify areas for improvement.
* Develop targeted offers, such as premium credit cards or exclusive loan rates, to retain customers with very good credit scores.
## Deployment And Documentatioin
Once the dashboard was finalized, it was deployed to Power BI service. The project process and deliverables are documented here on GitHub.

Interact with the final dashboard here:
[Churn Analysis](https://app.powerbi.com/groups/me/reports/91d25551-f30d-4bae-914d-c66473efcf92?experience=power-bi)












