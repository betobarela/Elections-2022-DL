# Revisiting the 2022 Presidential Elections project with Keras and TensorFlow

Once more we seek a model to predict the ratings of Candidate 1 in the second round of the 2022 Brazilian Elections, but now through a deep neural network with the help of Keras and Tensorflow. 

We test several configurations for weight initialization, activation functions, autodiff optimization, loss function, regularization, learning rate scheduling, and much more. 

The hyperparameter tuning is effected through Hyperopt. 

Although a self-normalizing net, with a selu activation and a lecun initialization presents itself as great contender, the a combination of lecun initialization with an elu activation appears to perform better. 

Note that the mean absolute error of the ML models we constructed in scikit-learn is already beat. 

This project is a work in progress and I still update it as time allows.
