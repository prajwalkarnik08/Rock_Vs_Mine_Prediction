# Rock_Vs_Mine_Prediction
In this project, I have used sonar data to predict whether a given object is Rock or Mine.
I have imported the libraries for
i) Data preprocessing, in this I have utilized numpy and pandas
ii) Training the machine learning model, I have used sklearn to train Logistic Regression model
and finally I have checked the accuracy score for train and test data.
                   Accuracy score is nothing but the ratio between the number of correct predictions and total number of predictions.
I have loaded the data using pandas.
Then, I have processed the data.
I have splitted the data into the training and test set. The test set contains 10% of total number of observations.
Then, I fitted my machine learning model which is known for classification Logistic Regression model.
As my Logistic Regression model is already trained on the train data, it gave maximum accuracy score i.e. 84%.
The test data is new to my Logistic Regression model, so it gave accuracy score of 76% which is less than the accuracy score of train data.
Lastly,
I have made a predictive system which predicts whether the data entered is of Rock or Mine.
For this, I have converted a list(which is used for inputting the feature of Rock or Mine) to a numpy array(which is used to speed up processing power).
Then, reshaped the numpy array to an instance because the model.fit() function requires an instance to make a prediction.
Then, used if-else condion to arrive at a decision which is given by the Logistic Regression model.
