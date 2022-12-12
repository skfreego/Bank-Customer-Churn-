# Bank-Customer-Churn-
### Classification
## Customer Churn Prediction

### What is churn prediction?
	Churn is the metric that measures the rate at which a business will lose customers.
Examples of churn are:
    Unsubscribing from a service
    Shopping with a competitor
    Not renewing of a contract
Churn can be measured yearly, quarterly, or monthly, but for most SaaS companies whose services renew every month, it is the latter. 
The method for calculating churn rate is very simple: dividing the total number of customers churned at the end of the month by the total number of customers at the beginning of the month. 



Customer churn rate:- is the defined as the rate at which customer are leaving the bank.

Churn rate is calculated by using the following formula:-

Churn rate = (Customer at the beginning of the month - Customer at the end of the month)/(Customer at the beginning of the month)

churn, used as the target. 1 if the client has left the bank during some period or 0 if he/she has not.

### Aim is to Predict the Customer Churn for ABC Bank.

’ A common example is people cancelling Spotify/Netflix subscriptions. So, Churn Prediction is essentially predicting which clients are most likely to cancel a subscription i.e ‘leave a company’ based on their usage of the service.

From a company point of view, it is necessary to gain this information because acquiring new customers is often arduous and costlier than retaining old ones. Hence, the insights gained from Churn Prediction helps them to focus more on the customers that are at a high risk of leaving

That makes it a classification problem where you have to predict 1 if the customer is likely to churn and 0 otherwise

Introduction

Churn prediction is probably one of the most important applications of data science in the commercial sector. The thing which makes it popular is that its effects are more tangible to comprehend and it plays a major factor in the overall profits earned by the business.

Let’s get started!

3D illustration of customers churn analysis
What exactly is Churn Prediction?

Churn is defined in business terms as ‘when a client cancels a subscription to a service they have been using.’ A common example is people cancelling Spotify/Netflix subscriptions. So, Churn Prediction is essentially predicting which clients are most likely to cancel a subscription i.e ‘leave a company’ based on their usage of the service.

From a company point of view, it is necessary to gain this information because acquiring new customers is often arduous and costlier than retaining old ones. Hence, the insights gained from Churn Prediction helps them to focus more on the customers that are at a high risk of leaving.

churn rate which is the rate at which customers stop doing business with an entity vector

The output in the case of Churn prediction is a simple yes or a no. That makes it a classification problem where you have to predict 1 if the customer is likely to churn and 0 otherwise.
Why does Churn occur?

Many factors influence the reasons for a customer to Churn. It may be the fact that there’s a new competitor in the market offering better prices or maybe the service they are getting has not been up to the mark, so on and so forth.

Hence, there is no correct answer as to why exactly the customer wants to churn because as you can see there are many influencing factors

##### Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

##### To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

To detect early signs of potential churn, one must first develop a holistic view of the customers and their interactions across numerous channels, including store/branch visits, product purchase histories, customer service calls, Web-based transactions, and social media interactions, to mention a few.

As a result, by addressing churn, these businesses may not only preserve their market position, but also grow and thrive. More customers they have in their network, the lower the cost of initiation and the larger the profit. As a result, the company's key focus for success is reducing client attrition and implementing effective retention strategy. 

#### Feature Description:

    Customer ID - Unique ID given to identify a particular customer.
    Credit Score - It is the score which determines the creditworthiness of a customer.
    Country - The country where customer lives.
    Gender - The Sex of customer.
    Age - The age of customer.
    Tenure - Number of years the customer has Bank Account in that Bank.
    Balance - Amount of money present in customer's bank.
    Products Number - Number of Products from that Bank.
    Credit Card - Does the customer own a credit card of that Bank.
    Active Member - Whether the customer is an active member of that Bank.
    Estimated Salary - Total Income of the Customer.
    Churn - Churn (Loss of existing customers) of the Bank

##### Data Insights
	As we can see there are a total of 12 columns in our data set.
	There is no null values.
	There are 10 quantitative feature and 2 qualitative feature
	There is no correlation between any variables

##### Observations:
	Around 20% of the customers have Churned
	Age has the highest positive correlation with the Churned Customers. Hence we can say that older customers are more likely to churn than the younger ones.
	Females have churned more than Males
	Customers with credit card have churned more than people who do not have it. May be because credit card influences your spending habits in a negative way.
	 People who are active member of bank have churned less than those who are'nt.
	 Credit Score and Estimated Salary are almost same for both churned and not churned people.
	 The percent of French people churned is least and that of German is most.

