# Neural_Network_Charity_Analysis

## Overview of the analysis: 

1. Compare the differences between the traditional machine learning classification and regression models and the neural network models.
2. Describe the perceptron model and its components.
3. Implement neural network models using TensorFlow.
4. Explain how different neural network structures change algorithm performance.
5. Preprocess and construct datasets for neural network models.
6. Compare the differences between neural network models and deep neural networks.
7. Implement deep neural network models using TensorFlow.
8. Save trained TensorFlow models for later use.

## Purpose:

Alphabet Soup, who is a foundation wants to predict where to make investments. The goal is to use machine learning and neural networks to apply features on the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful or not if funded by Alphabet Soup. The initial file has 34,000 organizations and a number of columns that capture metadata about each organization from past successful fundings.

## Results: 

Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing

1. What variable(s) are considered the target(s) for your model?
Checking to see if the target is marked as successful in the DataFrame, indicating that it has been successfully funded by AlphabetSoup.

2. What variable(s) are considered to be the features for your model?
The IS_SUCCESSFUL column is the feature chosen for this dataset.

3. What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN and NAME columns will not increase the accuracy of the model and can be removed to improve code efficiency.

### Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?

Were you able to achieve the target model performance?

What steps did you take to try and increase model performance?

## Summary: 

Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
