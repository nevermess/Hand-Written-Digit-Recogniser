# Hand-Written-Digit-Recogniser
The aim of the project was to detect and classify numbers(hand-written digits). It is build using keras as framework for building an artificial neural network to classify it and opencv to detect the numbers.
In this neural network model I have used a layer of ResNet in the final layer and a 2D convolution layer in early layers. With the include of a ResNet the Accuracy grows around 1% as compared to when tried with only simple convolutional layers.

Role of Opencv

In this project I have also used opencv to detect the digits written on a page which was fed to the neural networks to predict. It is further used to show the output of neural network just below the bounding box of number with the percentage of confidence in predicting that number.

NOTE:

The Final_keras_hand_written.ipynb is the main code python notebook that contains the code for creating model and other helper function.

The Prediction.ipynb is the notebook that is being used to predict the numbers written on a page.

Test Images.zip contains 3 sample pictures of digits written on a paper which is used in Prediction.ipynb for making prediction.
