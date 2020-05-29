# Hand-Written-Digit-Recogniser
The aim of the project was to detect and classify numbers(hand-written digits). It is build using keras as framework for building an artificial neural network to classify it and opencv to detect the numbers.
In this neural network model I have used a layer of ResNet in the final layer and a 2D convolution layer in early layers. With the include of a ResNet the Accuracy grows around 1% as compared to when tried with only simple convolutional layers.

Role of Opencv

In this project I have also used opencv to detect the digits written on a page which was fed to the neural networks to predict. It is further used to show the output of neural network just below the bounding box of number with the percentage of confidence in predicting that number.
