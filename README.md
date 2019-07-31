# PyTorch-Deep-Learning-With-Python-Bootcamp-ANN

Part 2 of Jose Portilla's course.
We will be looking at Artificial Neural Networks.

<img src="https://www.researchgate.net/profile/Sandra_Vieira5/publication/312205163/figure/fig1/AS:453658144972800@1485171938968/a-The-building-block-of-deep-neural-networks-artificial-neuron-or-node-Each-input-x.png" alt="(a) The building block of deep neural networks â artificial neuron or node. Each input x i has an associated weight w i . The sum of all weighted inputs, x i w i , is then passed through a nonlinear activation function f, to transform the preactivation level of the neuron to an output y j . For simplicity, the bias terms have been omitted. The output y j then serves as input to a node in the next layer. Several activation functions are available, which differ with respect to how they map a pre-activation level to an output value. The most commonly activation functions used are the rectifier function (where neurons that use it are called rectified linear unit (ReLU)), the hyperbolic tangent function, the sigmoid function and the softmax function. The latter is commonly used in the output layer as it can compute the probability of multiclass labels. (b) Example of a feedforward multilayer neural network (also referred to as multilayer perceptron) with two classes, in which the nodes in one layer are connected to all neurons in the next layer (fully connected network). For each neuron j in the first hidden layer, a nonlinear function is applied to the weighted sum of the inputs. The result of this transformation (y j ) serves as input for the second hidden layer. The information is propagated through the network up to the output layer, where the softmax function yields the probability of a given observation belonging to each class. Â "/>

Recall the definition of artificial: 
- made or produced by human beings rather than occurring naturally, especially as a copy of something natural

Thus, in this project, we will be working on constructing a neural network by human intellect such that we control the features to predict what would be the fare price. We want to study patterns such as distance traveled, and see it's relation to an increase in fare price.

In the process of completing this section. I currently uploaded the files on GitHub, but will be studying by coding along and implementing use of comments to help me understand. This project is inspired by "PyTorch Deep Learning with Python Bootcamp," and is taught by Jose Portilla.

My progress:
Studied theory, and understood how to perform feature engineering to predict fare prices. Separated features into both categorical and continuous variables. This is to help in classifying data. 

Ex: Given data in the following format: Hour:Min:Sec,
Performed feature extraction and displayed a column of hours.
Then, used "if then" statement to produce "AM or PM" categorical variables, vs. continuous variables.
Now, we can do some predictive modeling using binary classification.
We also noted that pickup_longitude, pickup_latitude and dropff_longitude and dropoff_latitude contained variables that we very similar to each other. Thus, we did feature engineering to instead work with distance traveled and subtracted pickup and dropoff distances.

NOTE: Will be the following online repository to help me code:

https://repl.it/@jameshizon/UsedPeacefulDestination-1

