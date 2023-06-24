# ML-Project1
Machine Learning Model evaluation 


## 1. Evaluating Your Model on Test Data 

We trained and evaluated the model using your training data. Now you will evaluate the model again using only the test data to check if the model is really performing as well as our training metrics have us believing. 

### 1.1 Data Preparation 

### 1.1.1 Read Data 

To test the model, you must first load the entire data. 

Now you split the dataset exactly how we did during our training. 

Hint: Remember the random_state and test_size parameters we used previously. 

### 1.1.2 Clean Data 

Clean the data using the same processes you used before training your model. 

Check the test set for any missing values and replace or drop them like you did for your training dataset. 

### 1.1.3 Feature Engineering 

Now create the same features from the training set to ensure that your model will work with the same set of features. 

### 1.1.4 Feature Scaling 

Since our models were created using data from a specific range, you must ensure that your test data is in the same range. Scale the numerical and categorical data to their right scales using the pipelines you used earlier. 
 

## 1.2 Modelling 

At last! You are now ready to test your model. 

Note: Before you use your model ensure that your data is in the right shape (i.e., Properly split into features and labels with the same number of feature columns) 

### 1.2.1 Load Model 

Re-load your model using the code from the learning material. 

### 1.2.2 Predict Values 

Make predictions with your model based on your test dataset. 

### 1.2.3 Evaluate Model 

Check the errors based on the values your model predicted and the actual values from the test dataset. 

### Author : Rose Kamau
