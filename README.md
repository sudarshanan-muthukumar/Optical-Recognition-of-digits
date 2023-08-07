# Optical-Recognition-of-digits
This aims to analyze the performance variances of 5 Classification algorithms across Machine Learning and namely, k-Nearest Neighbours, Support Vector Machine, Random Forest Classifier and Multi-Layer Perceptron on the Handwritten Digits dataset. Analysis is done based on the accuracy each model provides, defined as the percentage of correct classifications done by the model on the test subset/validation subset of the dataset.

Handwritten Digits dataset contains a collection of 8x8 pixel images of handwritten digits (0-9). It consists of a total of 5620 samples, where each sample is a grayscale image. Each image is represented as an array of 64 numerical features, where each feature represents the intensity of a pixel. The pixel intensities range from 0 to 16, with 0 indicating white and 16 indicating black. 4,496 records are used to train and 1,124 records to test the model. The records contain pixel values of each image along with the label.

In conclusion, two popular machine learning algorithms - Multilayer Perceptron (MLP) and Random Forest achieved high accuracy scores on the dataset. The MLP achieving an accuracy score of around 97% and the Random Forest achieving an accuracy score of around 97.5%.

The effect of changing the number of hidden layers in the MLP by adding more hidden layers did not always improve the performance of the model, indicating the importance of finding the right balance between model complexity and performance.

Overall, the optdigits dataset provides a good benchmark for evaluating the performance of classification algorithms, and the effectiveness of MLP and Random Forest for this task.
