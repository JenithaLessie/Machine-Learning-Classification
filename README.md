Our client, a grocery retailer, sent out mailers in a marketing campaign for their new delivery club. This cost customers $100 per year for membership, and offered free grocery deliveries, rather than the normal cost of $10 per delivery.

For this, they sent mailers to their entire customer base (apart from a control group) but this proved expensive. For the next batch of communications they would like to save costs by only mailing customers that were likely to sign up.

Based upon the results of the last campaign and the customer data available, we will look to understand the probability of customers signing up for the delivery club. This would allow the client to mail a more targeted selection of customers, lowering costs, and improving ROI.

Let's use Machine Learning to take on this task!


We firstly needed to compile the necessary data from tables in the database, gathering key customer metrics that may help predict delivery club membership.

Within our historical dataset from the last campaign, we found that 69% of customers did not sign up and 31% did. This tells us that while the data isn't perfectly balanced at 50:50, it isn't too imbalanced either. Even so, we make sure to not rely on classification accuracy alone when assessing results - also analysing Precision, Recall, and F1-Score.

As we are predicting a binary output, we tested four classification modelling approaches, namely:

Logistic Regression, 

Decision Tree, 

Random Forest, 

K Nearest Neighbours (KNN)

For each model, we will import the data in the same way but will need to pre-process the data based up the requirements of each particular algorithm. We will train & test each model, look to refine each to provide optimal performance, and then measure this predictive performance based on several metrics to give a well-rounded overview of which is best.
