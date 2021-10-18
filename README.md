# House-price-prediction
Predicting house prices using Linear Regression and Gradient Boosting Regressor
1)Importing our dependencies , for linear regression we use sklearn (built in python library) and import linear regression from it.
2)then initialize Linear Regression to a variable reg.
3)Now we know that prices are to be predicted , hence we set labels (output) as price columns and we also convert dates to 1’s and 0’s so that it doesn’t influence our data much . We use 0 for houses which are new that is built after 2014.
6)again import another dependency to split our data into train and test.
7)I’ve made my train data as 90% and 10% of the data to be my test data , and randomized the splitting of data by using random_state.
8)So now , we have train data , test data and labels for both let us fit our train and test data into linear regression model.
8)After fitting our data to the model we can check the score of our data ie , prediction. in this case the prediction is 73%. 

Srisai G 
sriscout10@gmail.com

Thank you
