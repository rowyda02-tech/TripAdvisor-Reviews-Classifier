**Abstract**

This project focuses on the Text Classification of tripadvisor reviews based on the rating associated with it. 
Different steps were considered to make this project a reality. First, we pre-processed the dataset to have a cleaner dataframe and to make it easier for the model to interpret the data. 
We used some of the following techniques: removing punctuations, stopwords (with exceptions), stemming procedure, tokenization,etc. 
Second, we split the data into training and testing sets and then tested multiple models to find the most suitable one for our project, settling for logistic regression. 
In addition, we also chose to represent the text using Tf-idf to help build the text classification model. 
Next, we decided to define a parameter grid for the hyper parameter tuning and then perform a GridSearchCV to find the best hyperparameters for the logistic regression model. 
Then, we trained the final model on the entire dataset using the best hyperparameters we found and also evaluated it on the test set. 
Next, we interpret the model by calculating some statistics to show which words contributed the most to our model(in our case they were mostly the negative words). 
Finally, we allowed the user to insert their own reviews and receive the rating based on the previous steps applied to the original data.
