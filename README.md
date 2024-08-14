# Lesson 6-Task 1 Build and Train a Simple ANN Model



Nimal has started his own mobile company in Sri Lanka. He wants to be a challenge to  big companies like Apple, Samsung, etc. However, he does not know how to estimate the price of mobile phones that his company creates. In this competitive mobile phone market, you cannot simply assume things. To solve this problem, he has collected sales data for  mobile phones of various companies. Nimal wants to find a relationship between the features of a mobile phone (eg:- RAM, internal memory, etc.) and its selling price. As he is not very good at machine learning, he needs your help to solve this problem.

You are given a csv file as the dataset, and it contains the necessary attributes to evaluate the price range. Here are the  2 price ranges:  high(1) and low(0).

Use your ML knowledge and try to develop a small ANN model and save weights using TensorFlow which will be important for future prediction of the price for given mobile phone specifications.

Steps

1. Read the data in CSV file
2. Split the data set into training and testing data where it contains 75% of the data as training and rest as testing data
3. Ann model architecture: – You can have the ANN with 2 hidden layer
  1stlayer with 8 neurons/nodes
  2nd layer with 4 neurons/nodes
3. Compile the model 
4. Fit, train the model for 100 epoch with batch size of 32
5. Save the weights file.
