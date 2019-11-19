# Machine-Learning---Credit-Fraud-Detection

Credit card fraud is a wide-ranging term for theft and fraud committed using or involving a payment card,
such as a credit card or debit card, as a fraudulent source of funds in a transaction.
The purpose may be to obtain goods without paying or to obtain unauthorized funds from an account.
Credit card fraud is also an adjunct to identity theft.
According to the United StatesFederal Trade Commission,
while the rate of identity theft had been holding steady during the mid-2000s, it rose by 21 percent in 2008.
However, credit card fraud, that crime which most people associate with ID theft,
decreased as a percentage of all ID theft complaints for the sixth year in a row.


Using machine learning to detect financial fraud dates back to the early 1990s and has advanced over the years.
Researchers train models to extract behavioral patterns from past transactions, called “features,” that signal fraud.
When you swipe your card, the card pings the model and, if the features match fraud behavior, the sale gets blocked.

This Machine Learning project utilizes various of advanced Machine Learning Libraries (such as TensorFlow, Skitlearn, Karnas, 
etc.) in order to detect the credit card frauds.

I utilized a transaction history of a bookstore to build a credit card fraud detection system. I used a publicly available data set of a bookstore, which sells its books online. This data contains over three hundred thousand transactions. For example, let’s say if the user’s IP address is from China; however, the credit card was issued in the US, and the user’s address in the UK, it’s most probably fraudulent transaction. This machine learning program detects potential credit card frauds with an accuracy of 86%. In my project, for the Pre-processing part: I used the sklearn package of sci-kit-learn library and import StandardScaler class to standardize the data. To process the data, I used a deep neural network with Keras library. I used supervised learning algorithms to train the data, and I split the data into training(70 %) and test tests (30%) with the sklearn library. I used random forest(using so many trees make the best decision) and decision tree algorithms of the classification model. Lastly, I visualized the performance of the project by the confusion matrix. According to the Wall Street Journal, almost 1 % of online credit card transactions are fraudulent in the United States. The estimated cost of fraud in the US last year alone is over $9 Billion, and this number is increasing year by year.
