# keras_imdb_classification

Simple binary classification model using the IMDB movie review dataset from Keras. It downloads the dataset, vectorizes the sequences, defines a model architecture with two hidden layers and an output layer, compiles the model with binary cross-entropy loss and accuracy metrics, trains the model on the training data, evaluates it on the test data, and makes predictions on the test data.

The model achieves a test accuracy of 87.8% and a test loss of 0.31. The loss and accuracy plots show that the model suffers from overfitting, as the training loss continues to decrease while the validation loss plateaus and then starts to increase after about 4 epochs
