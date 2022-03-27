
# Feature Extraction and Classification using KNN

This project introduce how to extract a discriminant feature from the data and work on it.
Here, I'm working with MNIST dataset. The discriminant feature I used is the centroid.
Strategy is to divide each image into blocks, calculate the centroid of each block, and use the blocks' centriod values as a discriminant feature vector of the image.
Images with the same number will have roughly similar centroid values.
## Data
MINIST dataset.
With 10,000 training samples and 1,000 test samples.
You can download csv file from here:
https://www.kaggle.com/datasets/oddrationale/mnist-in-csv