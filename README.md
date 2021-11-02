# ExpressionDetection
Detect emotional Expressions from the Fer2013 dataset found here https://www.kaggle.com/deadskull7/fer2013

# Method

PCA preprocessing using 250 principal components of a 48x48 unrolled image.
Feeds into an ANN with three layers, and one hidden layer.


The Convolutional Neural Network at 1000 epochs achieved 99% classification on original data and 50% classification on new data.


The FFNN, which preprocessed using PCA, achieved 90% accuracy of known data at 1000 epochs and about 14% classification of new data. However, this ran much faster.