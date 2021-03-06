# Deep Learning with Python and PyTorch
I used Python and its popular libraries such as NumPy and Pandas, as well as the PyTorch Deep Learning library. I then applied them to build Neural Networks and Deep Learning models.

## 1. Tensors and Gradients
- **Tensors**: Tensors are an essential part of PyTorch; there are complex mathematical objects in and of themselves. Fortunately, most of the intricacies are not necessary. In this section, I compared them to vectors and numpy arrays.

- **Derivatives**: In this section, took a look at simple derivatives and partial derivatives. And went over a cool hack that allows you to calculate the derivative of a function for multiple values using PyTorch Library.

- **Dataset**: In this section, I constructed a basic dataset by using PyTorch and learnt how to apply basic transformations to it. Also, used a prebuilt dataset and then used some prebuilt dataset transforms.

## 2. Fundamentals of Linear Regression
- **1D Training One Parameter**: In this section, I trained a model with PyTorch by using data that I created. The model only has one parameter: the slope

- **1D Training Two Parameter**: In this section, I trained a model with PyTorch by using the data that I created. The model will have the slope and bias. And l reviewed how to make a prediction in several different ways by using PyTorch

- **Stochastic Gradient Descent**: In this section, I practiced training a model by using Stochastic Gradient descent and compared it with Batch Gradient Descent we used in earlier section.

- **Mini-Batch Gradient Descent**: In this section, l practiced training a model by using Mini-Batch Gradient Descent.

- **PyTorch Way**: I created a model the PyTorch way in this section, this helps as models get more complicated.

- **Training and Validation Data**: In this section, I learnt to select the best learning rate by using validation data.

- **Early Stopping**: In this section, I performed early stopping and save the model that minimizes the total loss on the validation data for every iteration. (*Note*: Early Stopping is a general term. We will focus on the variant where we use the validation data. You can also use a pre-determined number iterations.)

- **Multi Linear Regression**: I performed Linear Regression involving multiple parameters as well as output using nn,Modules.

## 3. Logistic and Softmax Regression
- **Logistic Regression Prediction**: In this section, we will cover logistic regression using PyTorch.

- **Logistic Regression Training**: I see what happens when we use the root mean square error cost or total loss function using random initialization for a parameter values and also by selecting a bad initialization value for the parameter values and then try to solve issue with cross entropy.

- **Softmax Regression**: In this section, I used Softmax to classify three linearly separable classes, the features are in one dimension and then I used a single layer Softmax to classify handwritten digits from the MNIST database.

## 4. Feed Forward Neural Network
- **Neural Network**: In this section, I used a single-layer neural network to classify non linearly seprable data in 1-D database. Also, I explored how many neurons it takes to classify a noisy XOR data with one hidden layer neural network. Then I used a single layer neural network to classify handwritten digits from the MNIST database.

- **Activation Functions**: I compared different Activation Functions i.e. Sigmoid, Relu & Tanh by using them on MNIST.

- **Deeper Neural Network**: In this section, I created a Deeper Neural Network with nn.ModuleList()

## 5. Deep Networks
- **Dropout**: I see how adding dropout to my model decreases overfitting

- **Intialization**: I tested PyTroch Default Initialization, Xavier Initialization and Uniform Initialization on the MNIST dataset. Also I tested the Uniform Initialization, Default Initialization and He Initialization on the MNIST dataset with Relu Activation

- **Momentum**: In this section, I deal with several problems associated with optimization and see how momentum can improve your results. I also generated data that will produce a Loss Function with a High Condition Number. I created two models; one with the momentum term and one without the momentum term & then I saw how different values for the momentum parameters affect the convergence rate of a neural network.

- **Batch Normalization**: I built a Neural Network using Batch Normalization and compare it to a Neural Network that does not use Batch Normalization. I used the MNIST dataset to test my network

## 6. Introduction to Networks for Computer vision 
- **Convolution Intro**: I studied convolution and reviewed how the different operations change the relationship between input and output. I learnt two important components in building a convolutional neural network. The first is applying an activation function, which is analogous to building a regular network. Other is max pooling which reduces the number of parameters and makes the network less susceptible to changes in the image.

- **Convolution Neural Network**: In this section, I used a Convolutional Neural Network to classify handwritten digits from the MNIST database. I also reshaped the images to make them faster to process
