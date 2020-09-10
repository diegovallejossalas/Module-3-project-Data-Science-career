
Welcome to my presentation for module 3 project for data science career at flatiron school.

This meeting has the purpose to guide you on the way to retain more customers. Nowadays there are many companies improving their services, so customer have more and more options and they can leave a company and choose another very easily.
 	Big Bug consulting has acceded to your data base in order to identify why our customers are leaving us.
 	We used different algorithms to create a model who predicts churn potential of risk.
 	We followed the OSEMN process.
 	Let’s double click on this.

We can see that 14.5% of your clients have churned.
International plans, Customer service calls and Total charge are strongly correlated with churn. 
Customer’s charge was divided by day, evening, night and international. We added them in a single column because we wanted to figure out if high charges are correlated with churn.


Customer service calls are highly correlated with churn too. As soon as our customer calls more than 3 times it has more than 50% of chances to churn.
Churn rate is higher on customer with international plan.


We performed 4 different algorithms having the following results:
Random forest with a 96 percent accuracy
Decision trees with a 95 percent accuracy
Adaboost with a 92 percent accuracy
Logistic regression with an 85 percent accuracy

In this case, due to the nature of the problem we decided to choose Logistic Regression as the best algorithm because it gives us a bigger number of false positives, which means the number of observations where the model predicted the customer will churn (1), but they actually not (0).

We have some questions that could give us some more insights:
•	Do we need to offer international service calls plans?
•	Are your customers paying more than they should?
•	Our competitors have better plans?
•	Are you able to solve customer problems quickly?
•	Is our customer service enough good?
•	Do you have issues with International plans?


Recommendations:

•	We need a better system to track customer service calls, their problems should be fixed as soon as possible.
•	We need to look at our competitors international plans, maybe they are offering better deals. Should we sell international plans knowing that people are using communication apps to make long distance calls?
•	We can offer different prices depending on the necessities of customers

Future work

We got some insights, but it would be a great idea to get some more information about:
1.	Surveys with information about why the customer churned.
2.	We need to improve our logistic regression algorithm in order to improve accuracy.
3.	Churn rate of our competitors.

