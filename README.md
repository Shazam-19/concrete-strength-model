# concrete-strength-model
A neural network model using the deep learning Keras library for predicting concrete strength and testing different network parameters.

Final project of [Introduction to Deep Learning & Neural Networks with Keras](https://www.coursera.org/learn/introduction-to-deep-learning-with-keras) course on [Coursera](https://www.coursera.org/)

This project uses a neural network with _adam_ *optimizer* and _mean squared error (MSE)_ as *loss function* and compares the model evaluation with different numbers of epochs and with new layers added to the network.

### How the model is being trained?
-Step 1: The model is trained 50 times on different samples of data(30% of the data for validation) 
-Step 2: Each loop we evaluate the model using _MSE_ and store the result in a list of mean squared errors
-Step 3: After the model is trained and evaluated 50 times, we calculate the mean and standard deviation of the list of mean squared errors
-Step 5: Repeat the steps again(from Step 1), using different epochs and adding new layers to the neural network

I got a full grade of 20/20 after my _peers_ in the course reviewed my submission which matched the required points were given in the description of the project.

![Screenshot_1](https://user-images.githubusercontent.com/80653174/173262660-f3565d4d-f446-4395-87e9-d7dce237b819.png)
