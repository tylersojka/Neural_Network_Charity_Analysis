# Neural_Network_Charity_Analysis

![erfquake](images/../Images/vectorstock_19081013.png)
*****
*****

* By: Tyler Sojka
* February 2020
* Using neural networks to help create a binary classifier that is capable of predicting whether applicants will be successful.
  
*****
*****

## Tools

* Pandas
  * In computer programming, pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series.

## Overview

Using neural networks, we will use the features in the provided dataset to help Beks create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

Using Pandas and the Scikit-Learn’s StandardScaler(), we will preprocess the dataset in order to compile, train, and evaluate the neural network. We will bin diverse features, drop unnecessary columns, encode categorical variables, and finally scale the data.

Using our knowledge of TensorFlow, we will design a neural network, or deep learning model, to create a binary classification model that can predict if an Alphabet Soup–funded organization will be successful based on the features in the dataset. We will then compile, train, and evaluate our binary classification model to calculate the model’s loss and accuracy.

Using our knowledge of TensorFlow, we will optimize our model in order to try and achieve a target predictive accuracy higher than 75%.

## Results

* Data Preprocessing
  * What variable(s) are considered the target(s) for your model?
    - The target for my model are is the "IS_SUCCESSFUL" column. 
  * What variable(s) are considered to be the features for your model?
     - All of the included features except "EIN" and "NAME" were included at first then 'STATUS','SPECIAL_CONSIDERATIONS', and 'INCOME_AMT' were dropped in attempts to optimize the model.
  * What variable(s) are neither targets nor features, and should be removed from the input data?
    - "EIN" and "NAME" are neither.
* Compiling, Training, and Evaluating the Model
  * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - shape of one of the better tries at optimization, why? general trial and error, because we are not taught any actual strategies. 
     ![shape](Images/Screen%20Shot%202021-02-15%20at%209.28.22%20AM.png)
  * Were you able to achieve the target model performance?
    -  no
  * What steps did you take to try and increase model performance?
    - adjusted the amount of hidden layers, the amount of nodes in each layer, activation fuctions for each layer, optimizer functions, binning categorical features differently, dropping columns.

## Summary

The results were pretty underwhelming. Couldn't get above 72.7% accuracy. Something that might help in the future would be to have been taught methods to optimize, some kind of plan of attack other than just trial and error. A different model might have worked better also.