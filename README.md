# Deep-Learning-Challenge

![Logo](https://github.com/ernestosm23/deep-learning-challenge/blob/976101f0270b7fa692fa4a4b987accfc37871d73/small_business_funding.jpg)

Overview:
Alphabet Soup is a nonprofit foundation that is searching for a tool that can help it select applicants for funding with the best chance of success in its ventures. The purpose of this analysis is to develop a binary classifier that utilizes the features within the provided dataset to predict the likelihood of success for applicants funded by Alphabet Soup. To accomplish this, deep learning techniques, specifically deep neural networks, will be employed to extract data features and design target-oriented algorithms.

Results: 
Data Preprocessing:
Prior to inputting the data into the deep learning model, the dataset underwent several preprocessing steps to ensure the data's suitability and integrity. The primary focus of the model will be the 'IS SUCCESSFUL' column; since it's what we are attempting to predict. The model is also working on the numerical values; which we will have to convert some of the variables from categorical data with the use of the get dummies tool. The EIN and name columns are removed since they are neither targets nor features. 

Compiling, Training, and Evaluating the Model: 
For the neural network model was run with two dense layers of 80 & 30 neurons each. Having two layers allows the model to learn and capture different levels of abstraction in the data. The first layer with 80 neurons can help the model extract high-level features and patterns from the input data, and the remainder should be picked up by the 30 neurons to capture more specific details. 


Summary:
The deep learning model achieved a classification accuracy of 73%, demonstrating its ability to predict with reasonable accuracy whether applicants funded by Alphabet Soup will be successful.
