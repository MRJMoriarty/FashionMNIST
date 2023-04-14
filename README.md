# FashionMNIST
Established two simple models to achieve classification of the Fashion MNIST dataset (accuracy>90%)

In this project, a 1D convolutional model and a 2D convolutional model were established to achieve classification of the Fashion MNIST dataset.

Run train_1Dmodel.model1d(mode='train') to train 1D model, and generate the weight of 1D model. Then, move the best weight .pth file into 'weight' folder, and rename it's name as '1Dmodel.pth'. Finally, train_1Dmodel.model1d(mode='test') can calculate the confusion matrix and accuracy on test set of this model.

Run train_2Dmodel.model2d(mode='train') to train 2D model, and generate the weight of 2D model. Then, move the best weight .pth file into 'weight' folder, and rename it's name as '2Dmodel.pth'. Finally, train_2Dmodel.model2d(mode='test') can calculate the confusion matrix and accuracy on test set of this model.

FashionMNIST folder contains the Fashion MNIST data set, you don't need to download it again.
