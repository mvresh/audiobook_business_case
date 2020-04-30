# audiobook_business_case
Data from an audio book app has been collected,from public sources. 

Logically, it relates to the audio versions of books ONLY.  Each customer in the database has made a purchase at least once, that's why he/she is in the database.

Idea is to create a machine learning algorithm based on the available data that can predict if a customer will buy again from the Audiobook company. 

The main idea is that if a customer has a low probability of coming back, there is no reason to spend any money on advertising to him/her. If efforts are focused SOLELY on customers that are likely to convert again, great savings can be made. 

Moreover, the objective is to identify the most important metrics for a customer to come back again. Identifying new customers creates value and growth opportunities.

From .csv file, data can be summarised. There are several variables:  

Customer ID, ), 

Book length overall (sum of the minute length of all purchases), 

Book length avg (average length in minutes of all purchases), 

Price paid_overall (sum of all purchases) , 

Price Paid avg (average of all purchases),

Review (a Boolean variable whether the customer left a review),

Review out of 10 (if the customer left a review, his/her review out of 10,

Total minutes listened, Completion (from 0 to 1),

Support requests (number of support requests; everything from forgotten password to assistance for using the App),

and Last visited minus purchase date (in days). 

These are the inputs (excluding customer ID, as it is completely arbitrary. It's more like a name, than a number). 

The targets are a Boolean variable (0 or 1). Data is available for a period of 2 years based on which predictions will be done. 

So,aim is to find if: based on the last 2 years of activity and engagement, a customer will convert in the next 6 months. If they don't convert after 6 months, chances are they've gone to a competitor or didn't like the Audiobook way of digesting information. 

The task is : create a machine learning algorithm, which is able to predict if a customer will buy again.   This is a classification problem with two classes: won't buy and will buy, represented by 0s and 1s. 
