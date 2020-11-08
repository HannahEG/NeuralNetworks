# NeuralNetworks

### Training a Neural Network for optimal accuracy & reasonings:

######
This neural network consists of two hidden layers, the first with 44 neurons and the second with 22 neurons. The reason for this was to start out with a number of neurons similar in quantity to the number of inputs evaluated followed by half the number of inputs evaluated. Initially, there was concern that this might lead to overfitting. However, this was not the case. This neural network model did not read the desired accuracy rate of 75%. The highest percent reached was 72.5%, which was a nominal increase from the initial accuracy rate of 72.4%.

The optimization strategies utilized included adding a third hidden layer for added processing, but the accuracy rate did not improve; in fact it decreased to 72.3%. The high accuracy attained occurred after adjusting the number of epochs from 100 to 250. The final attempt to optimize included the re-binning of the initial input data. This method resulted in a decreased accuracy percentage as well. 

Out of concern for over-fitting the epochs were limited, though perhaps and increase double fold from 250 to 500 may have resulted in better accuracy scores. Another model that could potentially be used to evaluate the data would potentially be the Random Forest Model. It evaluates many parameters and compiles many smaller, weaker predictors into one larger stronger outcome, in some ways similar to the neural network with its multiple neurons and hidden layers.