# Neural_Network
## Introduction

I was challenged with building a machine learning model that would be able to predict the success of a venture paid by finctional corporation, Alphabet soup. My trained model will be used to determine the future decisions of the company. The projects likely to be a success will receive future funding from Alphabet Soup.

- Implement neural network models using TensorFlow. <br>
- Preprocess and construct datasets for neural network models. <br>
- Compare the differences between neural network models and deep neural networks. <br>
- Implement deep neural network models using TensorFlow. <br>
- Save trained TensorFlow models for later use. <br>

## Goals
- Import, analyze, clean, and preprocess a “real-world” classification dataset. <br>
- Select, design, and train a binary classification model of your choosing. <br>
- Optimize model training and input data to achieve desired model performance. <br>

## Materials
- Python 3 <br>
- Jupyter Notebok <br>
- charity_data.csv <br>

## Analysis
#### How many neurons and layers did you select for your neural network model?
For my neural network model I I used 2 hidden layers. On the first hidden layer I used 80 neurons and on the second layer I used 30 neurons.

#### Were you able to achieve target model performance? 
No, Unfortuently I was unable to achieve the target predictive accuracy of 75% or higher. 

#### What steps did you take to try and increase model performance?
Through experimentation, I increased the amount of epochs from 50 to 100 and finally 200. This however did not significantly inprove the accuracy of the model. The range that I was able to achieve was between 72-73.6% Additionally, I increased the ammount of layers up six with little difference in accuracy. I experienced the same range, between 72-73%.

#### If you were to implement a different model to solve this classification problem, which would you choose and why?
If I were to implement a different model it woild be the Random Forest model. The Random Forest model is similar to the neural network in that it can process large datasets for predictive analysis, but is faster with learning ,requires less preprocessing and works very well with tabular data. 

