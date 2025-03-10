This project is a fruit classification model developed using a Convolutional Neural Network (CNN) with TensorFlow and Keras. The model is trained on the Fruit-262 dataset, which contains images of various fruit types. The goal of this model is to classify fruit images into their respective categories with high accuracy.

The dataset used for this project is the Fruit-262 dataset, which contains 262 different fruit classes. The images were split into training, validation, and test sets for model training and evaluation.

Training Set: 80% of the dataset
Validation Set: 10% of the dataset
Test Set: 10% of the dataset
The images were resized to 256x256 pixels to optimize training performance.

The model utilizes a Convolutional Neural Network (CNN) with the following architecture:

Data Augmentation: Random flip, rotation, and zoom to increase dataset diversity
Convolution Layers: Three layers with ReLU activation and max pooling
Flatten Layer: Converts the feature maps into a 1D vector
Dense Layers:
Hidden layer with 128 neurons and ReLU activation
Output layer with softmax activation to classify into 262 categories
The model uses Adam optimizer and sparse categorical crossentropy loss function.
