# Petrol_Price_Prediction-
 We are expecting an unstable increase  in prices of petrol. Hence various regression algorithms can be  used to predict the price of petrol in future. The algorithm used here is SVR (Support Vector Regression), RBF  model. It gives a testing accuracy of 99.3% and training accuracy of  98.21%. Hyper-parameters being C=50 and gamma=20. We see the actual values and predicted values of the model are  almost the same. We adjust the accuracy by varying/tuning the hyper-parameters.
 The approch used here is to predict the petrol price in next 30 days (a variable which can be changed).In the csv file we have entries of petrol price for certain dates. Date col is not really neccessary hence we drop it. In order to predict the price after 30 days we need to have a relationship b/w day 1 and day 31. Therefore, we shift the data from 31st row in csv file to a new col so as to build the relationship b/w the input and target. Later on, the model is build to predict the price.
 
