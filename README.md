# Customer-Churn-Monthly-subscription

KKBOX is Asia’s leading music streaming service, holding the world’s most comprehensive Asia-Pop music library with over 30 million tracks. They offer a generous, unlimited version of their service to millions of people, supported by advertising and paid subscriptions. This delicate model is dependent on accurately predicting churn of their paid users.

The aim is to predict whether a user of the music streaming service KKBox will “churn”, i.e. leave this subscription-based service, by analysing the user’s behaviour on the website. For a subscription business, accurately predicting churn is critical to long-term success. Even slight variations in churn can drastically affect profits.

The task is to build an algorithm that predicts whether a user will churn after their subscription expires. Currently, the company uses survival analysis techniques to determine the residual membership life time for each subscriber. By adopting different methods, KKBOX anticipates they’ll discover new insights to why users leave so they can be proactive in keeping users dancing.

This dataset is from KKBOX  music streaming service. The data comes in the shape of five different files. Four of them contain the user IDs and properties:

In train.csv we find the IDs and whether these users have churned or not.

1. transactions.csv gives us details like payment method or whether the subscription was cancelled.

2. user_logs.csv contains the listening behaviour of a user in terms of number of songs played.

3. members.csv includes the user’s age, city, and such for users that have these membership information.

Finally, sample_submission_zero.csv serves as the test data set for the users for which we are tasked to predict their behaviour. Some of these files are large, with a maximum of about 6.65 GB for the user_logs data in a compressed form.

