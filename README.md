# Digit-recognizer
Deep Convolutional Network model submitted to the "digit recognizer" competition on Kaggle using the MNIST dataset.

Data was standarized using Z-score with mean and deviation of 0.5. 35000 samples used in training and 7000 in validation.

Internal architecture consists of 2 convolutional and pooling layers and 3 fully connected layers with ReLU activation functions and an output layer with softmax function.

Learning rate 0.02
Dropout 0.35 (35%)
Epochs 12
Weight decay 0.001
Batch size 100
Optimizer SGD

Score: 0.97125
Submission: https://www.kaggle.com/nicolassilveira/mnist-classifier-p1-cnn
