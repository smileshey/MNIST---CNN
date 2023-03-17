## Problem
​
​
This project aims to develop a neural net machine learning model that can accurately classify images of fashion products. The data consists of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. 
​
​
## Processing
​
Normalized image data by scaling down pixel values to a range of 0 to 1
Used Sparse Categorical Cross-Entropy as a loss function in lieu of one hot encoding. 
We started with a simple model and added complexity as we went.
Did a lot of guess- and -check and tuning of hyperparameters to get the best validation accuracy score.
​
## Parameters
​
We tried many different combinations of hyperparameters to build the best performing model. 
​
- Learning rate
- Number of hidden layers: Convolutional Layers and Dense Layers
- Number of neurons per layer
- Activation functions: ReLU, Leaky ReLU
- Dropout rate
- Batch size
- Number of epochs
- Early Stopping
​
## Models
​
- Validation Accuracy Score : ~ 90%
​
- Tuned params:
- 1 Convolutional Layer w/ 64 nodes
- LeakyReLU activation(alpha =0.05)
- 1 Dense layer w/ 128 nodes
- ReLU activation
- Dropout of 0.6
- Batch size of 32
- Early Stopping w/ patience of 6
- 15 epochs
​
## Difficulties
​
Getting better accuracy scores.
Finding the best combination of hyperparameters.
Felt like the guess and check could go on forever. 
​
### Conclusions
​
- Our best model got about 90% accuracy.  
- It had the most difficulty correctly classifying tops (shirts, t–shirts, pullovers and coats) and footwear(sandals, sneakers, and ankle boots).
- It did best correctly classifying trousers.
With higher resolution data, we believe adding complexity to the model would improve accuracy. 